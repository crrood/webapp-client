<template>
  <nav
    class="flex gap-4 p-2 bg-primary text-white"
    role="navigation"
    aria-label="main navigation"
  >
    <div class="">
      <router-link
        class=""
        to="/"
      >
        <img
          class="w-24 h-24"
          src="https://placebear.com/96/96"
        >
      </router-link>
    </div>

    <div class="flex justify-start place-items-center gap-8 text-2xl">
      <router-link
        class=""
        to="/resourceA"
      >
        WebApp
      </router-link>
    </div>
  </nav>
</template>