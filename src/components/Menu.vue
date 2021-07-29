<template>
    <div id="nav">
        <ul>
            <li><router-link to="/">Start</router-link></li>
            <li>|</li>
            <li><router-link to="/Membership">Membership</router-link></li>
            <li>|</li>
            <li><router-link to="/Organizers">Organizers</router-link></li>
        </ul>
    </div>
</template>

<script>

</script>

<style scoped>
#nav {
    padding:5px;
}
#nav ul {
    list-style: none;
}
#nav li {
    display: inline;
    margin-right: 30px;
    color: darkgoldenrod;
}
#nav a {
    text-decoration: none;
    font-weight: bold;
    font-size: 18px;
    color: inherit;
}
#nav a.router-link-exact-active {
  color: forestgreen;
}
</style>