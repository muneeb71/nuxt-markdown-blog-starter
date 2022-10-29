<template>
  <div
    class="flex flex-wrap items-center justify-around md:justify-center my-8"
  >
    <router-link
      :to="{ name: 'Home' }"
      class="border block mr-0 md:mr-4 px-3 py-2 rounded-md text-base font-medium"
      :class="
        $route.name == 'Home'
          ? 'bg-yellow-500 hover:bg-yellow-700 text-white b'
          : 'bg-gray-100 hover:bg-gray-300 text-gray-800 '
      "
      aria-current="page"
      >ETH to MATIC</router-link
    >

    <router-link
      :to="{ name: 'Destination' }"
      class="border  block px-3 py-2 rounded-md text-base font-medium"
      :class="
        $route.name == 'Destination'
          ? 'bg-yellow-500 hover:bg-yellow-700 text-white'
          : 'bg-gray-100 hover:bg-gray-300 text-gray-800'
      "
      aria-current="page"
      >MATIC to ETH</router-link
    >
  </div>
</template>
