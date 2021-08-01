<template>
  <div id="app">
    <div id="header">
        <img alt="IBG logo" src="./assets/ibg-logo.jpg">
        <div id="information">
            <strong>During COVID-19 we are playing online instead.<br />
            Join us on Meetup for more information.</strong>
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
