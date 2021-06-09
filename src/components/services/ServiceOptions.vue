<template>
  <div class="flex justify-between items-center gap-8 mt-20 mx-10">
    <div
      class="text-center"
      v-for="(service, index) in services"
      :key="`service${index}`"
    >
      <span class="block text-lg text-gray-700 mb-8">{{ service.name }}</span>
      <span class="block text-gray-500 text-base">{{ service.info }}</span>
    </div>
  </div>
</template>

<script>
export default {
  name: "ServiceOptions",
  data() {
    return {
      services: [
        {
          name: "Web Design",
          info:
            "Consectetur adipiscing elit. Praesent molestie urna hendrerit erat tincidunt tempus. Aliquam a leo risus. Fusce a metus non augue dapibus porttitor at in mauris. Pellentesque commodo...\n"
        },
        {
          name: "Web Development",
          info:
            "Consectetur adipiscing elit. Praesent molestie urna hendrerit erat tincidunt tempus. Aliquam a leo risus. Fusce a metus non augue dapibus porttitor at in mauris. Pellentesque commodo...\n"
        },
        {
          name: "SEO Analysis",
          info:
            "Consectetur adipiscing elit. Praesent molestie urna hendrerit erat tincidunt tempus. Aliquam a leo risus. Fusce a metus non augue dapibus porttitor at in mauris. Pellentesque commodo...\n"
        }
      ]
    };
  }
};
</script>

<style scoped>
/* (1366x768) WXGA Display */

@media screen and (min-width: 1366px) and (max-width: 1919px) {
}

@media (min-width: 1198px) and (max-width: 1365.9px) {
}

/* Normal desktop :992px. */

@media (min-width: 992px) and (max-width: 1197px) {
}

/* Normal desktop :991px. */

@media (min-width: 768px) and (max-width: 991px) {
}

/* small mobile :576px. */

@media (min-width: 576px) and (max-width: 767px) {
}

/* extra small mobile 320px. */

@media (max-width: 575px) {
}

/* Large Mobile :480px. */

@media only screen and (min-width: 480px) and (max-width: 575px) {
}

@media only screen and (max-width: 575px) and (min-width: 480px) {
}
</style>
