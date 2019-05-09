<!--props를 통해 parent에서 child로 데이터를 전달하였는데 이보다 큰 컨텐츠(html코드 덩어리)를  넘기고자 할 때
slot을 이용한다.-->
<!-- 특정 모양을 가진 공통프레임에 컨텐츠만 다르게 들어갈 component를 만들 때 유용하다. -->
<!-- App.vue - parent-->
<template>
    <div>
      <app-quote>
        <h1 slot="title">The Quote</h1>
        <p slot="content">Hello world!</p>
      </app-quote>
    </div>
</template>

<script>
import Quote from 'Quote.vue';

export default {
  components : { appQuote : Quote }
}
</script>

<style lang="css" scoped>
</style>
