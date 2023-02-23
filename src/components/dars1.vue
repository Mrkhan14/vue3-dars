<script setup>
// import { reactive } from 'vue'

// const state = reactive({ count: 0 })

// function increment() {
//   state.count++
// }
/*****************************************************************/ 


// // chuqur Reactive 
// import { reactive } from 'vue'
// const obj = reactive({
//   nested: { count: 0 },
//   arr: ['foo', 'bar']
// })
// function mutateDeeply() {
//   obj.nested.count++
//   obj.arr.push('baz')
// }
/*****************************************************************/ 

// import { reactive } from 'vue'
// const state = reactive({ count: 0 })
// function increment() {
//   state.count++
// }
// let n = state.count
// n--

/*****************************************************************/ 


import { ref } from 'vue'
const state = ref(0)
function increment() {
  state.value++
}
let n = state.value
n++
</script>

<template>
  <div>
    <!-- <div>
      count {{ state.count }}
    </div>
    <button class="btn btn-warning" @click="increment">
      add
    </button> -->
  <!-- /*****************************************************************/ -->

    <!-- {{ obj.nested.count }}
    {{ obj.arr.join(' ') }}
    <button class="btn btn-warning" @click="mutateDeeply">
      add
    </button> -->
  <!-- /*****************************************************************/ -->

      <!-- count {{ state.count }}
      {{ n }}
      <button class="btn btn-warning" @click="increment">
        add
      </button> -->

  <!-- /*****************************************************************/ -->
  
      Ref {{ state }}
      {{ n }}
      <button class="btn btn-warning" @click="increment">
        add
      </button>
    </div>
</template>

