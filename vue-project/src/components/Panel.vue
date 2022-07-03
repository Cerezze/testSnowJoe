<template>
<div class = "Panel">
    <div>
        <p>{{question.question}}</p>
        <Question :choices = "question.choices" :questionsArray = "questionsArray"/>
    </div>
</div>
</template>

<script>
import Question from './Question.vue';

export default{
    
    name: 'Panel',
    props: {
        question: Object,
        questionsArray: Array
    },
    components: {
        Question
    }
}
</script>

<style scope>
</style>
