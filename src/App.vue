
<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div class="block max-xl:hidden bg-slate-50 col-start-1 col-end-2" id="lef"></div> <!-- Левая заглушка -->
  <div class="block max-xl:hidden col-start-6 col-end-7" id="ref"></div> <!-- Правая заглушка -->
  <div class="max-sm:fixed max-sm:w-full max-sm:flex justify-center items-center max-sm:bottom-0 bg-slate-50 xl:col-start-2 xl:col-end-3 lg:col-start-1 lg:col-end-2 row-start-1 row-end-2 p-2" id="left_menu">
    <a></a>
    <nav class="max-sm:flex justify-center items-center text-slate-500 sticky">
      <a href="#" class="hover:text-slate-900 max-lg:flex-col max-md:text-[.8175rem]" id="stateact"><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="h-6 pr-4 max-lg:pr-0">
        <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 12l8.954-8.955c.44-.439 1.152-.439 1.591 0L21.75 12M4.5 9.75v10.125c0 .621.504 1.125 1.125 1.125H9.75v-4.875c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125V21h4.125c.621 0 1.125-.504 1.125-1.125V9.75M8.25 21h8.25" />
      </svg>
        Главная</a>
      <a href="#" class="hover:text-slate-900 max-lg:flex-col max-md:text-[.8175rem]"><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="h-6 pr-4 max-lg:pr-0">
        <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 12h16.5m-16.5 3.75h16.5M3.75 19.5h16.5M5.625 4.5h12.75a1.875 1.875 0 010 3.75H5.625a1.875 1.875 0 010-3.75z" />
      </svg>
        Cписок</a>
      <a href="#" class="hover:text-slate-900 max-lg:flex-col max-md:text-[.8175rem]"><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="h-6 pr-4 max-lg:pr-0">
        <path stroke-linecap="round" stroke-linejoin="round" d="M12 6.042A8.967 8.967 0 006 3.75c-1.052 0-2.062.18-3 .512v14.25A8.987 8.987 0 016 18c2.305 0 4.408.867 6 2.292m0-14.25a8.966 8.966 0 016-2.292c1.052 0 2.062.18 3 .512v14.25A8.987 8.987 0 0018 18a8.967 8.967 0 00-6 2.292m0-14.25v14.25" />
      </svg>
        Каталог</a>
    </nav>
    <div id="userinfo" class="max-sm:static absolute max-lg:p-2 p-4 box-border">
      <div class="avatar" style="background-image: url('https://sun9-53.userapi.com/impg/4R7XF21Onz9PnRVHzC90S9RSl5GGmiTetH_4Zw/LV5xwrvAAbo.jpg?size=1125x1109&quality=96&sign=350e44c3d7691d95bac76e7202faf4ce&type=album')"></div>
    </div>
  </div>
  <main class="col-start-4 col-end-5 max-sm:w-11/12 max-sm:m-auto max-xl:col-start-3 max-xl:col-end-4 row-start-1 row-end-2">
    <input type="search" class="block p-2 m-auto mt-1 text-sm mb-1 max-sm:w-full w-3/6 focus:outline-slate-500 focus:text-slate-500" placeholder="&#x1F50D;&#xFE0E;  Поиск...">
    <div>тут уже контент</div>
  </main>
</template>

<style scoped>

</style>
