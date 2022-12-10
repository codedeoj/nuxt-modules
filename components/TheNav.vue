<template>
  <nav class="flex justify-around items-center shadow-xl p-4 bg-white text-black">
    <nuxt-link to="/" class="text-center text-xl">
      <Icon name="cib:xbox" color="green" size="50px"/>
      <p class="font-extrabold text-green-700">XBOX</p>
    </nuxt-link>
    <ul class="flex gap-10">
      <li>
        <NuxtLink to="/" class="text-xl font-semibold hover:underline">Games</NuxtLink>
      </li>
      <li>
        <NuxtLink to="devices" class="text-xl font-semibold hover:underline">Devices</NuxtLink>
      </li>
      <li>
        <NuxtLink to="play" class="text-xl font-semibold hover:underline">Play</NuxtLink>
      </li>
      <li>
        <NuxtLink to="community" class="text-xl font-semibold hover:underline">Community</NuxtLink>
      </li>
    </ul>
  </nav>
</template>