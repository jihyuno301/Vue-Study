<template lang="html"> <!--화면에 표시할 요소들을 정의하는 영역 ex)HTML+Vue data binding-->
  <div>
    <span>
      <button type="button" name="button"> {{message}}</button>
    </span>
  </div>
</template>

<script> //뷰 컴포넌트 내용을 정의하는 영역 ex)template, data, methods
export default {
  data : {
    message : 'click this button'
  }
}
</script>

<!--템플릿에 추가한 HTML태그의 CSS스타일을 정의하는 영역-->
<style lang="css" scoped>
  span {
    font-size: 1.2em;
  }
</style>
