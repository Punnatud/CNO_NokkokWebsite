<template> 
    <div class="w-60 h-auto shadow-lg bg-emerald-600 rounded-lg hover:bg-emerald-500 border-solid border-2 border-emerald-700 scale-100 hover:scale-105  relative top-2 left-2
                text-blue-100 text-center mx-4 my-4">
        <div class="flex justify-center ">
        <a href="http://www.google.com" class="cursor-pointer">
            <div class=" w-52 h-52 ">
                <div class="rounded-full h-full bg-cover bg-center bg-no-repeat shadow-lg" :style="imagePath(profile)"></div>
            </div>
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
                default: "/assets/images/default.jpg"
            }
            
        },

        methods:{

        imagePath(image){
            return {'background-image' : 'url("./src/'+ image +'")'};
        }
        }

    }
</script>