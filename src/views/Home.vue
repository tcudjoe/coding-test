<template>
  <div class="home">
    <Navbar/>
    <Projects/>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'
import Navbar from '../components/Navbar.vue' // @ is an alias to /src
import Projects from '../components/Projects.vue' // @ is an alias to

@Component({
  components: {
    Navbar,
    Projects
  }
})

export default class Home extends Vue {}
</script>
