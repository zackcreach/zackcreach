<template lang="pug">
  h1.yep.yep--again Cool {{name}}
</template>

<script>
  export default {
    layout: "index",
    asyncData(context) {
      return {name: "Beans"}
    },
  }
</script>

<style lang="scss">
  .yep {
    color: blue;
    font-family: Roboto;
  }
</style>