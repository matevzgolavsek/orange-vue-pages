<template>
</template>

<script>
  export default {
    name: 'basic',

    beforeCreate () {
      this.$router.push({ name: 'docs-components-basic-button' })
    }
  }
</script>
