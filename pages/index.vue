<template>
  <full-page :options="{ licenseKey: '98DCED20-01AA410B-98E959B2-BED07DE8' }">
    <div class="section text-gray-600 dark:text-white">
      <lighting-switcher />
      <p>
        First section ...
      </p>
    </div>
    <div class="section text-gray-600 dark:text-white">
      <p>
        Second section ...
      </p>
    </div>
  </full-page>
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
