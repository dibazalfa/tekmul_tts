<template>
  <header>
    <div class="global-container">
      <nav class="flex items-center justify-between flex-wrap bg-yellow-50 p-6">
  <div class="flex items-center flex-shrink-0 text-indigo-900 mr-6">
    <!-- <svg class="fill-current h-8 w-8 mr-2" width="54" height="54" viewBox="0 0 54 54" xmlns="http://www.w3.org/2000/svg"><image xlink:href="/assets/cakaralogo.png" width="100%" height="100%"/></svg> -->
    <span class="font-semibold text-xl tracking-tight">Cakap Aksara</span>
  </div>
  <div class="block lg:hidden">
    <button class="flex items-center px-3 py-2 border rounded text-teal-200 border-teal-400 hover:text-white hover:border-white">
      <svg class="fill-current h-3 w-3" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><title>Menu</title><path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"/></svg>
    </button>
  </div>
  <div class="w-full block flex-grow lg:flex lg:items-center lg:w-auto">
    <div class="text-sm lg:flex-grow">
      <!-- <RouterLink to="/" href="#responsive-header" class="block mt-4 lg:inline-block lg:mt-0 text-teal-200 hover:text-white mr-4">
        Cakara Text-to-Speech
      </RouterLink> -->
    </div>
    <div>
      <RouterLink to="/" class="inline-block text-sm px-4 py-2 leading-none border rounded text-indigo-900 border-indigo-900 hover:border-transparent hover:text-teal-500 hover:bg-white mt-4 lg:mt-0" style="margin-right:10px;">Home</RouterLink>
    </div>
    <div>
      <RouterLink to="/about" class="inline-block text-sm px-4 py-2 leading-none border rounded text-indigo-900 border-indigo-900 hover:border-transparent hover:text-teal-500 hover:bg-white mt-4 lg:mt-0">About Us</RouterLink>
    </div>
  </div>
</nav>
    <link rel="stylesheet">
    <RouterView />
      <nav>
        <RouterLink to="/"></RouterLink>
        <RouterLink to="/about"></RouterLink>
      </nav>
    </div>
  </header>
</template>
