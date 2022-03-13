<template>
  <div id="app">
    <div id="header">
        <img alt="IBG logo" src="./assets/ibg-logo.jpg">
        <div id="information">
            <strong>
            Join us on Meetup for time and location information.</strong>
        </div>
        <Menu />
    </div>
    <router-view/>
  </div>
</template>

<script>
import Menu from './components/Menu'

export default {
    name: 'start',
    components: {
        Menu
    }
}
</script>

<style>
@import './assets/style.css';
</style>
