<template>
    <div style="margin-left: 25px; margin-top: 10px;">
        <weather
            api-key="e3b9aba95a64dc7d97f3d54f2142554c"
            title="Canterbury"
            latitude="51.280233"
            longitude="1.0789088"
            language="en"
            units="uk">
        </weather>
    </div>
</template>

<script>
  import VueWeatherWidget from 'vue-weather-widget'
  import 'vue-weather-widget/dist/css/vue-weather-widget.css'

  export default {
    components: {
      'weather': VueWeatherWidget
    }
  }
</script>

<style>
  .fe_container {
    min-height: calc(100vh - 123px);
    max-width: 100%;
  }
</style>
