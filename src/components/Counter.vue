<template>
  <button class="bg-amber-50 z-50 cursor-pointer" @click="clk()">Click me: {{ count }}</button>
</template>
<script>
export default {
  data() {
    return {
      count: 0
    };
  },
  methods:{
    clk(){
      console.log(1);
      this.count++
    }
  }
}
</script>
