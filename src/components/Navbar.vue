<template>
  <div>
    <nav class="bg-white dark:bg-gray-900 fixed w-full z-20 top-0 left-0 border-b border-gray-200 dark:border-gray-600">
      <div class="max-w-screen-xl flex flex-wrap items-center justify-between mx-auto p-6">
        <a href="/" class="flex items-center">
          <img src="../assets/img/pokemon.png" class="h-8 mr-3" alt="Pokemon">
          <span class="self-center text-2xl font-semibold whitespace-nowrap dark:text-white"></span>
        </a>
        
            <router-link to="/tambah" >
              <svg class="h-8 w-8 text-red-500"  fill="none" viewBox="0 0 24 24" stroke="currentColor">
  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 4v16m8-8H4"/>
</svg>

</router-link>
      </div>
    </nav>

  </div>
</template>
