<template>
    <div class="header">
        <div class="dell" @click="fn">{{ msg }}</div>
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
      this.msg = 'hello wrold'
    }
  }
}
</script>
<style scoped>
.dell {
    height:50px;
    line-height:50px;
    font-size:40px;
    background:#d00;
    color:#dd0;
}
</style>
