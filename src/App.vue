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

#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    color: #2c3e50;
    width: 700px;
    margin-left: auto;
    margin-right: auto;
    margin-bottom: 100px;
}
#header {
    text-align: center;
}
#header img {
    width: 50%;
}
h1, h2 {
    color: darkgoldenrod;
}
#information {
    background-color:khaki;
    border: solid 1px black;
    padding: 10px;
}
#information span {
    font-weight: bold;
    position:relative;
    top:-10px;
    display:block;
    width:70px;
}
</style>
