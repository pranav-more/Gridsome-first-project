<template>
<div>
    <CustomLayout>
  <div class="w-full h-full p-6 mt-16 backgroundhero">
  <div class="font-bold pb-3 textcolor text-xl">Completed series</div>
  <div class="grid w-full grid-cols-5 gap-2">
    <!--  -->
    <span v-for="(item,index) in items" :key="index">
    <div class="bg-white p-3 flex flex-col gap-2 w-full h-48 relative">
      <div class="">
      <div class="absolute h-36 w-fit bottom-0 right-0">
        <g-image class="h-36 w-fit" :src="item.img" alt=""></g-image>
      </div>
      </div>
      <div class="text-xs text-red-500">{{item.tag}}</div>
      <div class="text-base font-bold z-20">{{item.title}}</div>
      <div class="text-xs z-20">{{item.subtitle}}</div>
      <div class="flex gap-1">
        <div class="text-xs font-semibold bg-black rounded-full h-8 w-8 flex justify-center items-center">
          <div class="text-xs text-green-400">New</div>
        </div>
        <div class="text-xs font-semibold bg-gray-100 rounded-full h-8 w-8 flex justify-center items-center">
          <div class="text-xs text-green-400">End</div>
        </div>
      </div>
      <div>
        <div class="flex gap-1">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 fill-green-400 text-green-400" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
          <path stroke-linecap="round" stroke-linejoin="round" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z" />
        </svg>
        <div class="text-sm font-semibold text-green-400">
        {{item.likes}}
        </div>
        </div>
      </div>
    </div>
    </span>
    <!--  -->

  </div>
</div>
</CustomLayout>
</div>
</template>

<script>
import CustomLayout from '../layouts/CustomLayout.vue'
export default {
  components: { CustomLayout },
data(){
    return{
        items:[{
            id:0,
            title:'Til Debt Do Us Part',
            subtitle:'janggreen / flowbee',
            tag:'Romance',
            likes:'198,013',
            img:'https://freepngimg.com/thumb/anime/26533-9-uchiha-sasuke-transparent-picture.png'
        },
        {
            id:0,
            title:'Til Debt Do Us Part',
            subtitle:'janggreen / flowbee',
            tag:'Romance',
            likes:'198,013',
            img:'https://freepngimg.com/thumb/anime/26533-9-uchiha-sasuke-transparent-picture.png'
        },
        {
            id:0,
            title:'Til Debt Do Us Part',
            subtitle:'janggreen / flowbee',
            tag:'Romance',
            likes:'198,013',
            img:'https://freepngimg.com/thumb/anime/26533-9-uchiha-sasuke-transparent-picture.png'
        },
        {
            id:0,
            title:'Til Debt Do Us Part',
            subtitle:'janggreen / flowbee',
            tag:'Romance',
            likes:'198,013',
            img:'https://freepngimg.com/thumb/anime/26533-9-uchiha-sasuke-transparent-picture.png'
        },
        {
            id:0,
            title:'Til Debt Do Us Part',
            subtitle:'janggreen / flowbee',
            tag:'Romance',
            likes:'198,013',
            img:'https://freepngimg.com/thumb/anime/26533-9-uchiha-sasuke-transparent-picture.png'
        },
        {
            id:0,
            title:'Til Debt Do Us Part',
            subtitle:'janggreen / flowbee',
            tag:'Romance',
            likes:'198,013',
            img:'https://freepngimg.com/thumb/anime/26533-9-uchiha-sasuke-transparent-picture.png'
        },
        {
            id:0,
            title:'Til Debt Do Us Part',
            subtitle:'janggreen / flowbee',
            tag:'Romance',
            likes:'198,013',
            img:'https://freepngimg.com/thumb/anime/26533-9-uchiha-sasuke-transparent-picture.png'
        },
        {
            id:0,
            title:'Til Debt Do Us Part',
            subtitle:'janggreen / flowbee',
            tag:'Romance',
            likes:'198,013',
            img:'https://freepngimg.com/thumb/anime/26533-9-uchiha-sasuke-transparent-picture.png'
        },
        {
            id:0,
            title:'Til Debt Do Us Part',
            subtitle:'janggreen / flowbee',
            tag:'Romance',
            likes:'198,013',
            img:'https://freepngimg.com/thumb/anime/26533-9-uchiha-sasuke-transparent-picture.png'
        },
        {
            id:0,
            title:'Til Debt Do Us Part',
            subtitle:'janggreen / flowbee',
            tag:'Romance',
            likes:'198,013',
            img:'https://freepngimg.com/thumb/anime/26533-9-uchiha-sasuke-transparent-picture.png'
        },
        {
            id:0,
            title:'Til Debt Do Us Part',
            subtitle:'janggreen / flowbee',
            tag:'Romance',
            likes:'198,013',
            img:'https://freepngimg.com/thumb/anime/26533-9-uchiha-sasuke-transparent-picture.png'
        },
        {
            id:0,
            title:'Til Debt Do Us Part',
            subtitle:'janggreen / flowbee',
            tag:'Romance',
            likes:'198,013',
            img:'https://freepngimg.com/thumb/anime/26533-9-uchiha-sasuke-transparent-picture.png'
        },
        {
            id:0,
            title:'Til Debt Do Us Part',
            subtitle:'janggreen / flowbee',
            tag:'Romance',
            likes:'198,013',
            img:'https://freepngimg.com/thumb/anime/26533-9-uchiha-sasuke-transparent-picture.png'
        },
        {
            id:0,
            title:'Til Debt Do Us Part',
            subtitle:'janggreen / flowbee',
            tag:'Romance',
            likes:'198,013',
            img:'https://freepngimg.com/thumb/anime/26533-9-uchiha-sasuke-transparent-picture.png'
        },
        {
            id:0,
            title:'Til Debt Do Us Part',
            subtitle:'janggreen / flowbee',
            tag:'Romance',
            likes:'198,013',
            img:'https://freepngimg.com/thumb/anime/26533-9-uchiha-sasuke-transparent-picture.png'
        },
        ]
    }
}
}
</script>

<style>

</style>