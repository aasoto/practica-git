<script setup>
</script>
<template>
  <aside class="w-80 h-screen m-4 py-4 px-6 rounded-lg shadow-xl border-t-4 border-blue-800">
    <div class="flex flex-col gap-5">
      <h1 class="text-2xl font-bold text-center">The Weather App</h1>
      <hr class="border border-black">
      <ul>
        <li class="bg-none group hover:bg-blue-800 rounded-lg w-full px-4 py-2 flex justify-start items-center gap-3 cursor-pointer transition duration-200">
          <div class="w-10 h-10 flex justify-center items-center bg-blue-800 group-hover:bg-white text-white group-hover:text-blue-800 rounded-md">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
              <path stroke-linecap="round" stroke-linejoin="round" d="M12 3v2.25m6.364.386l-1.591 1.591M21 12h-2.25m-.386 6.364l-1.591-1.591M12 18.75V21m-4.773-4.227l-1.591 1.591M5.25 12H3m4.227-4.773L5.636 5.636M15.75 12a3.75 3.75 0 11-7.5 0 3.75 3.75 0 017.5 0z" />
            </svg>
          </div>
          <span class="text-xl text-black group-hover:text-white font-normal group-hover:font-bold transition duration-200">Weather</span>
        </li>
        <li class="bg-none group hover:bg-blue-800 rounded-lg w-full px-4 py-2 flex justify-start items-center gap-3 cursor-pointer transition duration-200">
          <div class="w-10 h-10 flex justify-center items-center bg-blue-800 group-hover:bg-white text-white group-hover:text-blue-800 rounded-md">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
              <path stroke-linecap="round" stroke-linejoin="round" d="M14.857 17.082a23.848 23.848 0 005.454-1.31A8.967 8.967 0 0118 9.75v-.7V9A6 6 0 006 9v.75a8.967 8.967 0 01-2.312 6.022c1.733.64 3.56 1.085 5.455 1.31m5.714 0a24.255 24.255 0 01-5.714 0m5.714 0a3 3 0 11-5.714 0M3.124 7.5A8.969 8.969 0 015.292 3m13.416 0a8.969 8.969 0 012.168 4.5" />
            </svg>
          </div>
          <span class="text-xl text-black group-hover:text-white font-normal group-hover:font-bold transition duration-200">Notifications</span>
        </li>
        <li class="bg-none group hover:bg-blue-800 rounded-lg w-full px-4 py-2 flex justify-start items-center gap-3 cursor-pointer transition duration-200">
          <div class="w-10 h-10 flex justify-center items-center bg-blue-800 group-hover:bg-white text-white group-hover:text-blue-800 rounded-md">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
              <path stroke-linecap="round" stroke-linejoin="round" d="M16.712 4.33a9.027 9.027 0 011.652 1.306c.51.51.944 1.064 1.306 1.652M16.712 4.33l-3.448 4.138m3.448-4.138a9.014 9.014 0 00-9.424 0M19.67 7.288l-4.138 3.448m4.138-3.448a9.014 9.014 0 010 9.424m-4.138-5.976a3.736 3.736 0 00-.88-1.388 3.737 3.737 0 00-1.388-.88m2.268 2.268a3.765 3.765 0 010 2.528m-2.268-4.796a3.765 3.765 0 00-2.528 0m4.796 4.796c-.181.506-.475.982-.88 1.388a3.736 3.736 0 01-1.388.88m2.268-2.268l4.138 3.448m0 0a9.027 9.027 0 01-1.306 1.652c-.51.51-1.064.944-1.652 1.306m0 0l-3.448-4.138m3.448 4.138a9.014 9.014 0 01-9.424 0m5.976-4.138a3.765 3.765 0 01-2.528 0m0 0a3.736 3.736 0 01-1.388-.88 3.737 3.737 0 01-.88-1.388m2.268 2.268L7.288 19.67m0 0a9.024 9.024 0 01-1.652-1.306 9.027 9.027 0 01-1.306-1.652m0 0l4.138-3.448M4.33 16.712a9.014 9.014 0 010-9.424m4.138 5.976a3.765 3.765 0 010-2.528m0 0c.181-.506.475-.982.88-1.388a3.736 3.736 0 011.388-.88m-2.268 2.268L4.33 7.288m6.406 1.18L7.288 4.33m0 0a9.024 9.024 0 00-1.652 1.306A9.025 9.025 0 004.33 7.288" />
            </svg>
          </div>
          <span class="text-xl text-black group-hover:text-white font-normal group-hover:font-bold transition duration-200">Help</span>
        </li>
      </ul>
    </div>
  </aside>
</template>