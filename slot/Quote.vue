<!--Quote.vue - child-->
<template>
  <div>
    <slot name="title"></slot> <!--이 부분에 <h1>The Quote</h1><p>Hello world!</p>가 온다.-->
    <slot name="content"></slot>
  </div>
</template>

<script>
export default {
}
</script>
<!-- slot으로 넘기는 코드들은 컴파일되어 전달된다. 따라서 모든 Control은 parent component에서 진행된다. -->
<!--
multiple slots : vue.jssms unnamed slot을 default slot으로 다룬다.
slot에 이름을 주고, slot attribute를 이용한다.
-->
<style lang="css" scoped>
</style>
