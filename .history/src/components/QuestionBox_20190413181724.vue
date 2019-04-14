<template>
   <div class="question-box-container">
  <b-jumbotron header="Bootstrap Vue" lead="Bootstrap 4 Components for Vue.js 2">
    <template slot="header">Bootstrap Vue</template>

    <template slot="lead">
      {{currentQuestion.question}}
    </template>

    <hr class="my-4">

    <p>
      It uses utility classes for typography and spacing to space content out within the larger
      container.
    </p>

    <b-button variant="primary" href="#">Submit</b-button>
    <b-button variant="success" href="#">Next</b-button>
  </b-jumbotron>
</div>
</template>

<script>

export default{
   props :{
      current
   }
}
</script>
