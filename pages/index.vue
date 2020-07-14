<template>
  <full-page :options="{ licenseKey: '98DCED20-01AA410B-98E959B2-BED07DE8' }">
    <div class="section">
      <lighting-switcher />
    </div>
    <div class="section">
      Second section ...
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
