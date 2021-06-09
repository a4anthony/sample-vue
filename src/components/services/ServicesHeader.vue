<template>
  <div class="text-center space-y-3">
    <span class="block font-bold text-2xl text-gray-700 capitalize"
      >services</span
    >
    <span class="block text-gray-500"
      >In order to help you grow your business, our carefully selected experts
      can advise you in in the following areas:
    </span>

    <div>
      <button @click="surprise('Tony')" class="btn-blue">
        Click me
      </button>
    </div>
  </div>
</template>

<script>
export default {
  name: "ServicesHeader",
  methods: {
    surprise(name) {
      alert(`surprise ${name}, you've clicked me`);
    }
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
