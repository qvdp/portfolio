<template>
  <div class="bg-gray-100 dark:bg-black">
    <div class="section">
      <lighting-switcher />
    </div>
    <div class="section">
      Second section ...
    </div>
  </div>
</template>

<script>
import LightingSwitcher from '@/components/template/LightingSwitcher'

export default {
  name: 'Home',
  components: {
    LightingSwitcher
  }
}
</script>
