<template>
  <div class="hello">
    <VueUEditor @ready="editorReady" ueditorPath="../../static/ueditor1_4_3_3/" class="ueditor-box"></VueUEditor>
  </div>
</template>

<script>
import VueUEditor from 'vue-ueditor'
export default {
  name: 'HelloWorld',
  components: {
    VueUEditor
  },
  data () {
    return {
      msg: ''
    }
  },
  methods: {
    editorReady (editorInstance) {
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.ueditor-box {
  height: 700px;
  text-align: left;
}
</style>
