<template>
  <div class="home">
    <Header/>
  </div>
</template>

<script>

import Header from '../components/header'
import Common from '../components/common.css'
export default {
  name: 'home',
  components: {
      Header,
      Common
  }
}
</script>
