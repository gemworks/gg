<template>
  <div>
    <router-view/>
  </div>
</template>

<script lang="ts">
import {defineComponent} from "vue";
export default defineComponent( {
  setup() {
    return {

    }
  }
})
</script>

<style>
* {
  font-family: 'Press Start 2P', monospace;
}
input[type='radio']:checked + span {
  @apply text-black;
}
</style>
