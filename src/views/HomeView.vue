<template>
  <div style="display:flex; flex-direction: column; align-items: center; justify-content: center; border:1px solid">
    <ComponentOne />
  </div>
</template>

<script>
import ComponentOne from '@/components/ComponentOne.vue';

export default {
  name: "HomeView",
  components: { ComponentOne },
  data() {
    return {
      userData: {
        name: "John Doe",
        avatar: "https://cdn.cloudflare.steamstatic.com/steamcommunity/public/images/avatars/1c/1cc0c6cfc7857d932a770dae33b8e0bf0b904267_full.jpg"
      }
    }
  },
  provide() {
    return {
      userData: this.userData
    }
  }
}
</script>
