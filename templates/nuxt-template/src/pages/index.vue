<template>
  <div>
    <h1>HELLO WORLD</h1>
    
  </div>
</template>
<script>
export default {
  mounted() {
    this.test()
  },
  methods: {
    async test() {
      console.log("HELLO WORLD")
    }
  }
}
</script>
