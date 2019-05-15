<template>
  <div id="app">
    <div class="parent">
      <div class="child">
        <ProblemType></ProblemType>
      </div>
      <div class="child">
        <ProblemType></ProblemType>
      </div>
      <div class="child">
        <ProblemType></ProblemType>
      </div>
    </div>
  </div>
</template>
<script>
import ProblemType from './sample/lecture_type/problem__type.vue'

export default {
  components : {
    'ProblemType' : ProblemType,

  }
}

</script>


<style lang="less">
#app {
  margin-top: 1.5rem;
  line-height: 1.4285;
}
.parent {
  display : flex;
  flex-direction : row;
}
.child {
  flex : 1 1 50px;
}
</style>
