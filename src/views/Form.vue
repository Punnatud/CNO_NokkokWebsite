<template>
 <div>
    <button @click="dropdown=!dropdown" class="bg-red-500 p-6 font-bold text-lg text-center">toggle</button>
    <div v-if="dropdown" class="p-10 bg-gray-600">
    DropDown</div>
    <div>
        On Change
    </div>
    <input id="text" type="text" @change="getNumber()" class="p-2 border-2"/>
    <div>
        count: {{count}}
    </div>
 </div> 
</template>

<script>
import { toNumber } from '@vue/shared';

export default {
    data(){
        return{
            count: 0,
            dropdown: false
        }
    },
    getNumber(){
        let value = document.getElementById("text").value;
        value = parseInt(value);
        return count+= value; 
    }

}
</script>

<style>

</style>