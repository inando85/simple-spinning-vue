<template lang="pug">
  .spinning
</template>

<script>
export default {
  name: 'SimpleSpinning',
}
</script>

<style lang="sass" scoped>

.spinning
  width: 100px
  height: 100px
  border: 3px solid #000
  border-top: 3px solid #84E
  border-radius: 50%
  animation: spinning 1s linear infinite

@keyframes spinning
  100%
    transform: rotate(360deg)

</style>