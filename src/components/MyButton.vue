<template>
  <div>
      <h2>good morning</h2>
      <button @click="count++">good了{{count}}次</button>
  </div>
</template>

<script>
export default {
    name: '',
    data() {
        return{
            count:0
        }
    }
}
</script>

<style>
    h2 {
        color:hotpink
    }
</style>