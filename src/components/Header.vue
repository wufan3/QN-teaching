<template>
    <div class="header">
        <h1 class="dell" @click="fn">{{ msg }}</h1>
    </div>
</template>
<script>
export default {
  name: 'Header',
  data () {
    return {
      msg: 'hello header'
    }
  },
  methods: {
    fn () {
      this.msg = 'hello world'
    }
  }
}
</script>
<style scoped>
  .dell{
    height:100px;
    background:#dd0;
    color:#d00;
    font-size:60px;
    line-height:100px;
  }
</style>
