<template>
HELLO
<Panels :questions="questions"/>
</template>

<script>
import Panels from './components/Panels.vue';
import data from './questions.json';

export default{
    data(){
      return{
        questions: data
      }
    },
    components: {
      Panels
    }
}
</script>

<style>
</style>
