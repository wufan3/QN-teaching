<template>
    <div class="header">
        <h1 class="dell">{{ msg }}</h1>
    </div>
</template>

<script>
export default {
  name: 'Header',
  data () {
    return {
      msg: 'hello header'
    }

  }
}
</script>

<style scoped>
.dell {
    background:#d00;
    color:#dd0;
}
</style>


