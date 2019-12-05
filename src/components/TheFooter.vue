<template>
  <footer id="footer-page">
    <ul class="footermenu">
      <li><router-link exact to="/contact">Contact</router-link></li>
    </ul>
    <ul class="footermenu">
      <li><router-link exact to="/imprint">Imprint</router-link></li>
    </ul>
    <div>
      <second-level />
    </div>
  </footer>
</template>

<script>
import SecondLevel from './SecondLevel.vue'

  export default {
    name: 'TheFooter',
    components: {
      SecondLevel
    }
  }
</script>
