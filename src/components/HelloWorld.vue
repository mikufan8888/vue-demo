<template>
  <div class="hello">
    <h3>hello vue</h3>
    <p>{{message}}</p>
    <div>{{ reHtml }}</div>
    <div v-html="reHtml"></div>
    <div v-bind:id="dynamicId"></div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data() {
    return {
      message: "miku",
      reHtml: "<a href='htttps://www.baidu.com'>百度</a>",
      dynamicId: 10001
    }

  }
}
</script>