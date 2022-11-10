<template> 
    <div class="w-60 h-auto shadow-lg bg-emerald-600 rounded-lg hover:bg-emerald-500 border-solid border-2 border-emerald-700 scale-100 hover:scale-105  relative top-2 left-2
                text-blue-100 text-center mx-4 my-4">
        <div class="flex justify-center ">
        <a href="http://www.google.com" class="cursor-pointer">
            <img  src="../assets/images/default.jpg" alt="" class=" w-52 h-52 rounded-full shadow-lg "/>
        </a>
        </div>
        <div class="p-6">
    <h5>{{name}}</h5>
    <h1>{{nickname}}</h1>
    <h3>{{team}}</h3>
        </div>
    </div>
</template>
<script>    
    export default{
        props:{
            name: {
                type: String,
                default: "name"
            },
            nickname: {
                type: String,
                default: "AnotherName"
            },
            team: {
               type: String,
               default : "NoTeam" 
            },
            profile: {
                type: String,
                default: "https://thumbs.dreamstime.com/b/default-avatar-profile-vector-user-profile-default-avatar-profile-vector-user-profile-profile-179376714.jpg"
            }
            
        },
        imagePath(image){
            let url;
            url = new URL(image);
            return url;
        }


    }
</script>