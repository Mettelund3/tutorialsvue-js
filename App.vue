<script setup>
import { ref } from 'vue';
//kommentar//
const vandcykel = ref('');

function onSubmit () {
  alert(vandcykel.value);
}
</script>

<template>
  <!-- kommentar-->
  <input type="text" v-model="vandcykel"/>
  <button v-on:click="onSubmit">
    Dette er en knap
  </button>
  {{  vandcykel }}
</template>