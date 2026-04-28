<script setup>
import Parent from './components/Parent.vue';

// import { reactive, ref } from "vue";


// const red = ref(0);
// const green = ref(0);
// const blue = ref(0);

// const red = 0;

// const color = ref({
//   red: 0,
//   green: 0,
//   blue: 0,
// })

// const color = reactive ({
//   red: 0,
//   green: 0,
//   blue: 0,
// })

// function generateColor() {
  // red.value = Math.floor(Math.random() * 256);
  // green.value = Math.floor(Math.random() * 256);
  // blue.value = Math.floor(Math.random() * 256);

//   color.red = Math.floor(Math.random() * 256);
//   color.green = Math.floor(Math.random() * 256);
//   color.blue = Math.floor(Math.random() * 256);
// }

// const refValue = ref('hello ');
// const reactiveValue = reactive({
//   greeting: 'world',
// });

// refValue.value = true;
// reactiveValue.greeting = false;
// console.log(refValue.value);
// console.log(reactiveValue);


</script>

<template>
  <main 
    >
    <!-- <div>
      <input type="number" placeholder="red" v-model="color.red" id="" />
      <input type="number" placeholder="green" v-model="color.green" id="" />
      <input type="number" placeholder="blue" v-model="color.blue" id="" />
      <button @click="generateColor()">Generate</button>
    </div> -->
  <Parent />

  </main>
</template>

<style scoped>
main {
  background-color: rgb(22, 152, 156);
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
