<template>
    <div class="question-box-container">
        <b-jumbotron>
            <template v-slot:lead>
            {{ currentQuestion.question }}
            </template>

            <hr class="my-4">

            <p>
            List of answers
            </p>

            <b-button variant="primary" href="#" style="margin-right: 10px;">Submit</b-button>
            <b-button variant="success" href="#">Next</b-button>
        </b-jumbotron>
</div>
</template>

<script>
export default {
    props: {
        currentQuestion: Object
    }
}
</script>