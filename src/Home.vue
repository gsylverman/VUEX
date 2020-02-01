<template>
  <div>
    <div>NR : {{ num }}</div>
    <A></A>
  </div>
</template>

<script>
import A from "./A";

export default {
  data: function() {
    return {};
  },
  computed: {
    num() {
      return this.$store.state.nr;
    }
  },
  methods: {},
  components: {
    A
  }
};
</script>
