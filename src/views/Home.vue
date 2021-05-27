<template>
  <div>
    <Counter
      :year="2021"
      :month="4"
      :date="27"
      :hour="16"
      :minute="37"
      :second="44"
      :millisecond="31"
    />
  </div>
</template>

<script>
// @ is an alias to /src
import Counter from '@/components/Counter.vue'

export default {
  name: 'Home',
  components: {
    Counter
  },
}
</script>

<style lang="scss" scoped>
</style>
