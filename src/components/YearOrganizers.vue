<template>
    <div>
        <h2>{{ year }}</h2>
        <p>
            <strong>Chairman</strong>
            <span class="name">{{chairman}}</span>
            <strong>Treasurer</strong>
            <span class="name">{{treasurer}}</span>
            <strong>Secretary</strong>
            <span class="name">{{secretary}}</span>
            <strong>Meetup manager</strong>
            <span class="name">{{meetupManager}}</span>
            <strong>Controller</strong>
            <span class="name">{{controller}}</span>
            <strong>Election committee</strong>
            <span class="name" v-for="name in electionCouncil" :key="name">
                {{name}}
            </span>
        </p>
    </div>
</template>

<script>
export default {
  name: 'YearOrganizers',
  props: {
    year: String,
    chairman: String,
    treasurer: String,
    secretary: String,
    meetupManager: String,
    controller: String,
    electionCouncil: Array
  }
}
</script>

<style scoped>
strong {
    letter-spacing:1px;
    padding-top:10px;
    display:block;
}
.name {
    display: block;
    margin-left: 20px;
}
</style>