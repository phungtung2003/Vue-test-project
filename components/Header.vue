<template>
  <header class="flex items-center">
    <div style="height: 54px" class="pr-5">
      <img src="/assets/images/gear.png" alt="logo" class="h-full" />
    </div>
    <ul class="flex items-center">
      <li>
        <NuxtLink
          class="text-white hover:text-teal-500 text-lg px-4 py-3"
          to="/"
        >
          Home
        </NuxtLink>
      </li>
      <li>
        <a class="text-white hover:text-teal-500 text-lg px-4 py-3" href="#"
          >Popular</a
        >
      </li>
      <li>
        <a class="text-white hover:text-teal-500 text-lg px-4 py-3" href="#"
          >Features</a
        >
      </li>
      <li>
        <a class="text-white hover:text-teal-500 text-lg px-4 py-3" href="#"
          >Newcomers</a
        >
      </li>
    </ul>
    <ul class="flex ml-auto items-center mt-2">
      <li>
        <NuxtLink
          to="/register"
          class="inline-block bg-transparent border-white border hover:bg-white hover:bg-opacity-25 text-white font-light w-40 text-center px-6 py-1 text-lg rounded-full mr-4"
        >
          Sign Up
        </NuxtLink>
      </li>
      <li>
        <NuxtLink
          to="/login"
          class="inline-block bg-transparent border-white border hover:bg-white hover:bg-opacity-25 text-white font-light w-40 text-center px-6 py-1 text-lg rounded-full"
        >
          My Account
        </NuxtLink>
      </li>
    </ul>
  </header>
</template>
