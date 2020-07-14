<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <App msg="测试下ts的prop" />
  </div>
</template>

<script>
// @ is an alias to /src
import App from '@/components/App'

export default {
  name: 'Home',
  components:{App}
}
</script>
