<template>
  <div class="bg-white dark:bg-black">
    <navigation />
    <nuxt />
  </div>
</template>

<script>
import Navigation from '@/components/template/Navigation'

export default {
  name: 'Default',
  components: {
    Navigation
  }
}
</script>
