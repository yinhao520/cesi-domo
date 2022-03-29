<template>
<div>
  <addItion></addItion>
  <p>--------------------------</p>
  <subtrAction></subtrAction>

</div>
</template>

<script>
import addItion from './components/Addition.vue'
import subtrAction from './components/Subtraction.vue'
export default {
  components: {
    addItion,
    subtrAction
  }
}
</script>

<style>

</style>
