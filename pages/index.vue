<template>
  <full-page :options="options">
    <div :class="`display-${!loading}`" class="section text-gray-600 dark:text-white">
      <p>
        Welcome ...
      </p>
    </div>
    <div :class="`display-${!loading}`" class="section text-gray-600 dark:text-white">
      <p>
        About ...
      </p>
    </div>
    <div :class="`display-${!loading}`" class="section text-gray-600 dark:text-white">
      <p>
        Projects ...
      </p>
    </div>
    <div :class="`display-${!loading}`" class="section text-gray-600 dark:text-white">
      <p>
        Contact ...
      </p>
    </div>
  </full-page>
</template>

<script>
export default {
  name: 'Home',
  data () {
    return {
      loading: true,
      options: {
        licenseKey: '98DCED20-01AA410B-98E959B2-BED07DE8',
        // Accessibility
        keyboardScrolling: true,
        recordHistory: true,
        // Design
        controlArrows: true,
        paddingTop: '3em',
        anchors: ['', 'about', 'projects', 'contact'],
        lazyLoading: true
      }
    }
  },
  mounted () {
    this.display = false
  }
}
</script>

<style>
.display-true {
  display: block;
}
.display-false {
  display: none;
}
</style>
