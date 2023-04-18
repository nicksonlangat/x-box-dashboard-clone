<template>
  <div class="bg-center bg-cover w-full"  :style="{ 'background-image': 'url(' + require('../assets/halo.jpeg') +')', 'height':'100vh'}">
     <div class="container mx-auto flex justify-between">
        <div class="flex gap-4">
           <img class="rounded-full h-8 mt-6" src="../assets/gamer.jpeg" alt="">
           <h3 class="font-bold text-white mt-6 cursor-pointer text-xl">Nick Langat</h3>
        </div>
        <div class="mr-8 flex gap-6">
           <div class="relative flex items-center mt-6">
              <span class="absolute">
                 <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6 mx-3 text-gray-400">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M21 21l-5.197-5.197m0 0A7.5 7.5 0 105.196 5.196a7.5 7.5 0 0010.607 10.607z" />
                 </svg>
              </span>
              <input type="text" placeholder="Search" class="block w-full py-2.5 text-white placeholder-white bg-gray-800/60 pl-11 pr-5 rtl:pr-11 rtl:pl-5 focus:outline-none focus:ring-0">
           </div>
           <div class="mt-6 bg-gray-800/60 px-0.5 py-0.5 cursor-pointer text-white">
              <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-10 h-10">
                 <path stroke-linecap="round" stroke-linejoin="round" d="M9.594 3.94c.09-.542.56-.94 1.11-.94h2.593c.55 0 1.02.398 1.11.94l.213 1.281c.063.374.313.686.645.87.074.04.147.083.22.127.324.196.72.257 1.075.124l1.217-.456a1.125 1.125 0 011.37.49l1.296 2.247a1.125 1.125 0 01-.26 1.431l-1.003.827c-.293.24-.438.613-.431.992a6.759 6.759 0 010 .255c-.007.378.138.75.43.99l1.005.828c.424.35.534.954.26 1.43l-1.298 2.247a1.125 1.125 0 01-1.369.491l-1.217-.456c-.355-.133-.75-.072-1.076.124a6.57 6.57 0 01-.22.128c-.331.183-.581.495-.644.869l-.213 1.28c-.09.543-.56.941-1.11.941h-2.594c-.55 0-1.02-.398-1.11-.94l-.213-1.281c-.062-.374-.312-.686-.644-.87a6.52 6.52 0 01-.22-.127c-.325-.196-.72-.257-1.076-.124l-1.217.456a1.125 1.125 0 01-1.369-.49l-1.297-2.247a1.125 1.125 0 01.26-1.431l1.004-.827c.292-.24.437-.613.43-.992a6.932 6.932 0 010-.255c.007-.378-.138-.75-.43-.99l-1.004-.828a1.125 1.125 0 01-.26-1.43l1.297-2.247a1.125 1.125 0 011.37-.491l1.216.456c.356.133.751.072 1.076-.124.072-.044.146-.087.22-.128.332-.183.582-.495.644-.869l.214-1.281z" />
                 <path stroke-linecap="round" stroke-linejoin="round" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z" />
              </svg>
           </div>
           <div class="text-white mt-6 cursor-pointer">
              <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-10 h-10">
                 <path stroke-linecap="round" stroke-linejoin="round" d="M12 18.75a6 6 0 006-6v-1.5m-6 7.5a6 6 0 01-6-6v-1.5m6 7.5v3.75m-3.75 0h7.5M12 15.75a3 3 0 01-3-3V4.5a3 3 0 116 0v8.25a3 3 0 01-3 3z" />
              </svg>
           </div>
           <div class="text-white mt-6 cursor-pointer">
              <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-10 h-10">
                 <path stroke-linecap="round" stroke-linejoin="round" d="M21 10.5h.375c.621 0 1.125.504 1.125 1.125v2.25c0 .621-.504 1.125-1.125 1.125H21M4.5 10.5h6.75V15H4.5v-4.5zM3.75 18h15A2.25 2.25 0 0021 15.75v-6a2.25 2.25 0 00-2.25-2.25h-15A2.25 2.25 0 001.5 9.75v6A2.25 2.25 0 003.75 18z" />
              </svg>
           </div>
           <div class="text-white text-xl mt-8">
              4:55 pm
           </div>
        </div>
     </div>

     <div class="container mx-auto mt-20">
      <h3 class="text-white text-2xl font-bold">Jump back in</h3>
      <div class="grid mt-6 grid-cols-6 gap-x-4">
        <div class="cursor-pointer">
          <img src="../assets/halo_infinite_cover.jpeg" alt="">
        </div>
        <div class="cursor-pointer">
          <img src="../assets/cyber.jpeg" alt="">
        </div>
        <div class="cursor-pointer">
          <img src="../assets/forza.jpeg" alt="">
        </div>
        <div class="cursor-pointer">
          <img src="../assets/a-plague-tale-innocence-cover-cd-keys-discount.jpeg" alt="">
        </div>
        <div class="cursor-pointer">
          <img src="../assets/elden.jpeg" alt="">
        </div>
        <div class="cursor-pointer">
          <img src="../assets/wiw.jpeg" alt="">
        </div>
      </div>
     </div>


     <div class="container mx-auto mt-6">
      <div class="flex gap-2">
        <div class="bg-green-800/60 cursor-pointer w-48 h-48">
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-10 h-10 mt-12 text-white ml-6">
  <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 7.125C2.25 6.504 2.754 6 3.375 6h6c.621 0 1.125.504 1.125 1.125v3.75c0 .621-.504 1.125-1.125 1.125h-6a1.125 1.125 0 01-1.125-1.125v-3.75zM14.25 8.625c0-.621.504-1.125 1.125-1.125h5.25c.621 0 1.125.504 1.125 1.125v8.25c0 .621-.504 1.125-1.125 1.125h-5.25a1.125 1.125 0 01-1.125-1.125v-8.25zM3.75 16.125c0-.621.504-1.125 1.125-1.125h5.25c.621 0 1.125.504 1.125 1.125v2.25c0 .621-.504 1.125-1.125 1.125h-5.25a1.125 1.125 0 01-1.125-1.125v-2.25z" />
</svg>

          <h3 class="text-white mt-2 font-bold ml-6">My games <br> & apps</h3>
        </div>
        <div class="bg-indigo-800/60 w-48 cursor-pointer h-48">
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-10 h-10 ml-6 mt-12 text-white">
  <path stroke-linecap="round" stroke-linejoin="round" d="M15.75 10.5V6a3.75 3.75 0 10-7.5 0v4.5m11.356-1.993l1.263 12c.07.665-.45 1.243-1.119 1.243H4.25a1.125 1.125 0 01-1.12-1.243l1.264-12A1.125 1.125 0 015.513 7.5h12.974c.576 0 1.059.435 1.119 1.007zM8.625 10.5a.375.375 0 11-.75 0 .375.375 0 01.75 0zm7.5 0a.375.375 0 11-.75 0 .375.375 0 01.75 0z" />
</svg>


          <h3 class="text-white mt-2 font-bold ml-6">Microsoft <br> store</h3>
        </div>

        <div class="bg-emerald-800/60 cursor-pointer w-64 h-48">
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-10 h-10 text-white mt-12 ml-6">
  <path stroke-linecap="round" stroke-linejoin="round" d="M14.25 6.087c0-.355.186-.676.401-.959.221-.29.349-.634.349-1.003 0-1.036-1.007-1.875-2.25-1.875s-2.25.84-2.25 1.875c0 .369.128.713.349 1.003.215.283.401.604.401.959v0a.64.64 0 01-.657.643 48.39 48.39 0 01-4.163-.3c.186 1.613.293 3.25.315 4.907a.656.656 0 01-.658.663v0c-.355 0-.676-.186-.959-.401a1.647 1.647 0 00-1.003-.349c-1.036 0-1.875 1.007-1.875 2.25s.84 2.25 1.875 2.25c.369 0 .713-.128 1.003-.349.283-.215.604-.401.959-.401v0c.31 0 .555.26.532.57a48.039 48.039 0 01-.642 5.056c1.518.19 3.058.309 4.616.354a.64.64 0 00.657-.643v0c0-.355-.186-.676-.401-.959a1.647 1.647 0 01-.349-1.003c0-1.035 1.008-1.875 2.25-1.875 1.243 0 2.25.84 2.25 1.875 0 .369-.128.713-.349 1.003-.215.283-.4.604-.4.959v0c0 .333.277.599.61.58a48.1 48.1 0 005.427-.63 48.05 48.05 0 00.582-4.717.532.532 0 00-.533-.57v0c-.355 0-.676.186-.959.401-.29.221-.634.349-1.003.349-1.035 0-1.875-1.007-1.875-2.25s.84-2.25 1.875-2.25c.37 0 .713.128 1.003.349.283.215.604.401.96.401v0a.656.656 0 00.658-.663 48.422 48.422 0 00-.37-5.36c-1.886.342-3.81.574-5.766.689a.578.578 0 01-.61-.58v0z" />
</svg>


          <h3 class="text-white mt-2 font-bold ml-6">Action-adventure <br> games</h3>
        </div>
        <div class="cursor-pointer">
          <img class="h-48 w-80" src="../assets/forza4.png" alt="">
        </div>
        <div class="cursor-pointer">
          <img class="h-48 w-80" src="../assets/forzak.jpeg" alt="">
        </div>
      </div>
     </div>
     <div class="container mx-auto mt-6">
      <div class="flex justify-between">
        <h3 class="text-white text-2xl font-bold">Recently added to game pass</h3>

        <div class="bg-gray-800/90 px-4 py-2 flex gap-6">
          <div class="bg-gray-900 cursor-pointer py-2 px-4 rounded-full">
            <p class="text-white font-bold">More options</p>
          </div>
          <div class="bg-gray-900 cursor-pointer py-2 px-4 rounded-full">
            <p class="text-white font-bold">Add to play later</p>
          </div>
          <div class="bg-gray-900 cursor-pointer py-2 px-4 rounded-full">
            <p class="text-white font-bold">Search</p>
          </div>
        </div>
      </div>
     </div>
  </div>
</template>

<script>

export default {
  name: 'HomeView',
  components: {
  }
}
</script>
