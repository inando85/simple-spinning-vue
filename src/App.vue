<template lang="pug">
  .app
    SimpleSpinning
</template>

<script>

import SimpleSpinning from './components/SimpleSpinning'

export default {
  name: 'App',
  components: {
    SimpleSpinning
  }
}
</script>

<style lang="sass" scoped>

.app
  width: 100%
  height: 100vh
  display: flex
  justify-content: center
  align-items: center

</style>
