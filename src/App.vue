<script setup>
import { ref } from "vue";
import { reactive } from "vue";

// const red = ref(0);
// const green = ref(0);
// const blue = ref(0);

// const red = 0;

// const color = ref({
//   red: 0,
//   green: 0,
//   blue: 0,
// })

const color = reactive ({
  red: 0,
  green: 0,
  blue: 0,
})
</script>

<template>
  <main :style="{ backgroundColor: `rgb(${color.red}, ${color.green}, ${color.blue})` }">
    <div>
      <input type="number" placeholder="red" v-model="color.red" id="" />
      <input type="number" placeholder="green" v-model="color.green" id="" />
      <input type="number" placeholder="blue" v-model="color.blue" id="" />
    </div>
  </main>
</template>

<style scoped>
main {
  background-color: rgb(50, 248, 255);
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
}

div {
  display: flex;
  flex-direction: column;
}
</style>
