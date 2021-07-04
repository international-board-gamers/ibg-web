<template>
    <div>
        <Year
            year = "2021 (2021 July - 2022 June)" 
            chairman = "Simon Forsberg"
            treasurer = "Gustav Örtenberg"
            secretary = "Charlotta Fredriksson"
            controller = "Stefan Kuhns"
            :electionCouncil = "[
                'Aleksandra Kempińska',
                'Asad Sayeed',
                'Hanna Kraft'
            ]"
        />

        <Year
            year = "2020 (2020 July - 2021 June)" 
            chairman="Simon Forsberg"
            treasurer = "Gustav Örtenberg"
            secretary = "Charlotta Fredriksson"
            meetupManager = "Andreas Löfman"
            controller = "Stefan Kuhns"
            v-bind:electionCouncil = "[
                'Aleksandra Kempińska',
                'Jesus Berjano Pena',
                'Nils Gerstner'
            ]"
        />

        <Year
            year = "2019 (2019 July - 2020 June)" 
            chairman="David Gay-Perret"
            treasurer = "Cenny Davidsson"
            secretary = "Simon Forsberg"
            meetupManager = "Stefan Kuhns"
            controller = "Gustav Örtenberg"
            :electionCouncil = "[
                'Andreas Löfman',
                'Derrick Eriksson',
                'Jesus Berjano Pena'
            ]"
        />

        <Year
            year = "2018 (2018 July - 2019 June)" 
            chairman="David Gay-Perret"
            treasurer = "Cenny Davidsson"
            secretary = "Simon Forsberg"
            meetupManager = "Fanny Pelletier"
            controller = "Robin Larsson"
            :electionCouncil = "[
                'Andreas Löfman',
                'Derrick Eriksson',
                'Veronika Fedorova'
            ]"
        />

        <h2>Special thanks</h2>
        <p>
            To our founder <em>David Gay-Perret</em> who single handedly ran this as a meetup for a long time before starting the IBG organization for which he brought on 7 more people as organizers.
        </p>
    </div>
</template>

<script>
import Year from '@/components/YearOrganizers'

export default {
    name: 'organizers',
    components: {
        Year
    }
}
</script>

<style scoped>
strong {
    letter-spacing:1px;
    padding-top:10px;
    display:block;
}
.names {
    display: block;
    margin-left: 20px;
}
</style>