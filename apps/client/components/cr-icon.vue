<style lang="stylus">
  cr-icon
    font-family 'IcoMoon'
    speak none
    font-style normal
    font-weight normal
    font-variant normal
    text-transform none
    line-height 1
    -webkit-font-feature-settings "liga"
    -moz-font-feature-settings "liga=1"
    -moz-font-feature-settings "liga"
    -ms-font-feature-settings "liga" 1
    -o-font-feature-settings "liga"
    font-feature-settings "liga"
    -webkit-font-smoothing antialiased
    -moz-osx-font-smoothing grayscale
</style>

<template>
    <cr-icon>
      <content></content>{{type}}
    </cr-icon>
</template>

<script>
  module.exports = {
    props: [
      { name: 'type', type: String }
    ],
    replace: true
  };
</script>