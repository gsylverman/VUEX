<template>
  <div>
    <button @click="plus">+</button>
    <button @click="minus">-</button>
  </div>
</template>

<script>
export default {
  methods: {
    plus() {
      this.$store.state.nr++;
    },
    minus() {
      this.$store.state.nr--;
    }
  }
};
</script>
