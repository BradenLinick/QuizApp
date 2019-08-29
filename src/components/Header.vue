<template>
  <div>
    <b-nav tabs>
      <b-nav-item disabled><b>The Quiz App</b></b-nav-item>
      <b-nav-item disabled><span>Counter: {{ numCorrect }}/{{ numTotal }}</span></b-nav-item>
      <b-nav-item disabled><span>Category: {{ category.category }}</span></b-nav-item>
    </b-nav>
  </div>
</template>

<script>
export default {
  props: {
    numCorrect: Number,
    numTotal: Number,
    category: Object
  }
}
</script>

<style>
  b {
    color: white;
  }

  span {
    color: white
  }
</style>