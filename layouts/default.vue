<template>
  <div class="bg-gray-100 dark:bg-black">
    <lighting-switcher />
    <nuxt />
  </div>
</template>

<script>
import LightingSwitcher from '@/components/template/LightingSwitcher'

export default {
  components: {
    LightingSwitcher
  }
}
</script>
