<i18n>
  {
  "en": {
  "title": "About"
  },
  "tr": {
  "title": "Hakkımda"
  }
  }
</i18n>

<template lang="pug">
  .Home
    h1.title {{ $t('title') }}

</template>

<script>
  export default {
    name: 'Home'
  }
</script>

<style lang="scss">
  @import "../../../stylesheet/config/variables";

  .Home {
    padding: 50px;
  }
</style>
