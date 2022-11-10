<template>
    <div class="flex justify-center min-h-screen bg-emerald-800 ">
    <div>
       <profileCard
        name = "Patinya Saichantadee"
        nickname = "tonnow"
        team = "CNO"
       ></profileCard> 
    </div>
    <div class="">
        <profileCard
        :name ="name"
        :nickname = "nickname"
        :team = "team"
        ></profileCard>
    </div>
    <div class="">
        <profileCard>
            name =""
        </profileCard>
    </div>
    </div>
</template>
<script>
import profileCard from '../components/Profile.vue'
    export default{
        data(){
            return{
                name: "Punnatud Duengkae",
                nickname: "Nokkok",
                team: "CNO"
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
