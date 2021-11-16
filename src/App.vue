<template>
  <router />
  <hr />
  <hr />
  <vuex />
</template>

<script>
import router from '@/router'
import vuex from '@/vuex'
export default {
  name: 'App',
  components: { router, vuex },
}
</script>
