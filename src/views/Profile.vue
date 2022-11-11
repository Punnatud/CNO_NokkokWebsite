<template>
    <div class=" min-h-screen bg-emerald-800 ">
     <div class="flex justify-center pt-32">
        <profileCard
        v-for="member in members" :key="member"
        :name="member.name"
        :nickname="member.nickname"
        :team="member.team"
        :profile="member.profile">
        </profileCard>
    </div>

    <div class="flex justify-center text-center p-10">
        <router-link to ="/" class="font-bold text-blue-100 p-10 bg-emerald-400 rounded-lg hover:bg-emerald-300 scale-100 hover:scale-105">
            Go back to sing a song
        </router-link>     
    </div>
    </div>
</template>
<script>
import profileCard from '../components/Profile.vue'
    export default{
        data(){
            return{
            members:[
                {
                    name: "Patinya Saichantadee",
                    nickname: "Cold",
                    team: "CNO",
                    profile: "/assets/images/cold.jpg"

                },
                {
                    name: "Punnatud Duengkae",
                    nickname: "Nokkok",
                    team: "CNO",
                    profile: "/assets/images/profile.jpg"
                },
                {
                    name: "Sittipong Hemloum",
                    nickname: "Ong",
                    team: "CNO",
                    profile: "/assets/images/ong.jpg"

                }
            ]
            }
        },
        components: {
            profileCard
        }
    }
</script>
<style>
    /* img {
    border-radius: 70%;
    width: 50%;
    } */
</style>
