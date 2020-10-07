<template>
  <section class="container">
    <div>
      <Counter></Counter>
      <hr />
      <Counter></Counter>
      <hr />
      <Counter></Counter>
      <hr />
    </div>
  </section>
</template>

<script>
import Counter from "~/components/Counter.vue";
import Logo from "~/components/Logo.vue";
import VuetifyLogo from "~/components/VuetifyLogo.vue";
export default {
  components: {
    Counter,
  },
};
</script>