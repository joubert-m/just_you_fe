<template>
  <div class="home">
    <Profile msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>

import Profile from '@/components/Profile.vue'

export default {
  name: 'Home',
  components: {
    Profile
  }
}
</script>
