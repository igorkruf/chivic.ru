<template >
  <div>
    <h1>Children1</h1>

    <button @click="test">test</button>
  </div>
</template>
<script>
import axios from "axios";
export default {
  methods: {
    test() {
      console.log("Тэст");
      axios.post("http://localhost:3001/test");
    },
  },
  //добавил комментарии в новой ветке 11111111111111111 222 333 444 555 666 777 888
};
</script>
<style>
</style>