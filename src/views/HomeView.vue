<script setup>
import TheWelcome from '../components/TheWelcome.vue'
</script>

<template>
  <div class="bg-slate-600 min-h-screen flex"> 
    <div class="p-10 w-1/5 bg-slate-700 min-h-screen basis-1/5">
      <h1 class="font-semibold text-5xl text-slate-200 bg-slate-600 flex min-h-fit justify-center p-5 border-solid border-2 border-slate-300 scale-100 hover:scale-105 hover:bg-slate-500 shadow-lg">CNO</h1>
      <div class="flex justify-center mt-10 shadow-lg">
        <img src="../assets/images/heres-johnny.jpg" alt="" class="scale-200"/>
      </div>
    </div>
    <div class="bg-slate-100 p-9 max-w-2xl  rounded-md ml-32 my-40 basis-1/2 shadow-lg">
    <p>
      I don't want a lot for Christmas
There is just one thing I need
I don't care about the presents
Underneath the Christmas tree
<br/>
I just want you for my own
More than you could ever know
Make my wish come true
All I want for Christmas is you, yeah
<br/>
I don't want a lot for Christmas
There is just one thing I need
And I don't care about the presents
Underneath the Christmas tree
<br/>
I don't need to hang my stocking
There upon the fireplace
Santa Claus won't make me happy
With a toy on Christmas Day
<br/>
I just want you for my own
More than you could ever know
Make my wish come true
All I want for Christmas is you
You, baby
<br/>
Oh, I won't ask for much this Christmas
I won't even wish for snow
And I'm just gonna keep on waiting
Underneath the mistletoe
<br/>
I won't make a list and send it
To the North Pole for Saint Nick
I won't even stay awake to
Hear those magic reindeer click
<br/>
'Cause I just want you here tonight
Holding on to me so tight
What more can I do?
Baby, all I want for Christmas is you
You, baby
<br/>
Oh, all the lights are shining so brightly everywhere
And the sound of children's laughter fills the air
<br/>
And everyone is singing
I hear those sleigh bells ringing
Santa, won't you bring me the one I really need?
Won't you please bring my baby to me?
<br/>
Oh, I don't want a lot for Christmas
This is all I'm asking for
I just wanna see my baby
Standing right outside my door
<br/>
Oh, I just want you for my own
More than you could ever know
Make my wish come true
Baby, all I want for Christmas is you
You, baby
<br/>
All I want for Christmas is you, baby [repeat with ad-libs until fade]
    </p>
    </div>
      <router-link to="/Profile" class="text-white mx-10 p-10 my-96 bg-red-600 max-h-28 relative top-80 rounded-lg scale-100 hover:scale-105 hover:bg-red-400 shadow-lg" >
        Go to Profile
      </router-link>
  </div>
</template>
