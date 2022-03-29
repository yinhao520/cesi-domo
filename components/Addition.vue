<template>
<div>
  <p>最新的值：{{$store.state.count}}</p>
  <button @click="add">+1</button>
</div>
</template>

<script>
export default {
  name: 'addItion',
  methods: {
    add () {
      this.$store.dispatch('addyb', 5)
    }
  }
}
</script>

<style>

</style>
