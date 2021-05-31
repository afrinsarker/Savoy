<template>
  <div>
    <header class="text-gray-600 body-font bg-green-100">
    <div class="container mx-auto flex flex-wrap p-5 flex-col md:flex-row items-center">
      <nav class="flex lg:w-2/5 flex-wrap items-center text-base md:ml-auto">
        <a href="#" class="mr-5 hover:text-gray-900">Shop</a>
        <a href="#" class="mr-5 hover:text-gray-900">Categories<sup><small class="mx-2">NEW</small></sup></a>
        <a href="#" class="mr-5 hover:text-gray-900">Pages</a>
        <a href="#" class="hover:text-gray-900">Elements</a>
      </nav>
      <a href="#" class="flex order-first lg:order-none lg:w-1/5 title-font font-medium items-center text-gray-900 lg:items-center lg:justify-center mb-4 md:mb-0">
        <span class="ml-3 text-2xl text-gray-700 font-semibold uppercase tracking-widest">Savoy</span>
      </a>
      <div class="lg:w-2/5 inline-flex lg:justify-end ml-5 lg:ml-0">
        <span class="text-gray-400  inline-flex items-center  ml-auto leading-none text-sm pr-3 py-1 ">
          <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
              <path fill-rule="evenodd" d="M3.172 5.172a4 4 0 015.656 0L10 6.343l1.172-1.171a4 4 0 115.656 5.656L10 17.657l-6.828-6.829a4 4 0 010-5.656z" clip-rule="evenodd" />
          </svg>
        </span>
        <a href="#" class="mr-5 hover:text-gray-900">Sign In</a>
        <a href="#" class="mr-5 hover:text-gray-900">Cart<sup class="mx-2 text-yellow-500">0</sup></a>
      </div>
    </div>
  </header>
  <!---dropdown practice
    <div class="container mx-auto px-6">
      <div class="relative text-left inline-flex flex-col">
        <button @click="open = !open" class="p-3 flex items-center bg-black text-white">Dropdown
          <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 ml-3" viewBox="0 0 20 20" fill="currentColor">
            <path fill-rule="evenodd" d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z" clip-rule="evenodd" />
         </svg>
        </button>

      </div>
    </div>
dropdown practice--->

<!---filter--->
  <div v-if="open" class="absoulate w-full mt-12bg-white border-t border-grey-300 container px-5 py-24 mx-auto flex md:items-center lg:items-start md:flex-row md:flex-nowrap flex-wrap flex-col">
      <div class="w-64 flex-shrink-0 md:mx-0 mx-auto text-center md:text-left md:mt-0 mt-10">
          <h2 class="title-font font-medium text-gray-900 tracking-widest text-sm mb-3">Sort By</h2>
          <div class="px-0 pt-4 pb-2">
            <span class="inline-block bg-gray-900 rounded-full px-3  text-sm font-semibold text-gray-200 mr-2 mb-2">Bathroom</span>
            <span class="inline-block bg-gray-900 rounded-full px-3  text-sm font-semibold text-gray-200 mr-2 mb-2">Classic</span>
            <span class="inline-block bg-gray-900 rounded-full px-3  text-sm font-semibold text-gray-200 mr-2 mb-2">Contemporary</span>
            <span class="inline-block bg-gray-900 rounded-full px-3  text-sm font-semibold text-gray-200 mr-2 mb-2">Decor</span>
            <span class="inline-block bg-gray-900 rounded-full px-3  text-sm font-semibold text-gray-200 mr-2 mb-2">Essentials</span>
            <span class="inline-block bg-gray-900 rounded-full px-3  text-sm font-semibold text-gray-200 mr-2 mb-2">Grooming</span>
            <span class="inline-block bg-gray-900 rounded-full px-3  text-sm font-semibold text-gray-200 mr-2 mb-2">Interior</span>
            <span class="inline-block bg-gray-900 rounded-full px-3  text-sm font-semibold text-gray-200 mr-2 mb-2">Kitechen</span>
            <span class="inline-block bg-gray-900 rounded-full px-3  text-sm font-semibold text-gray-200 mr-2 mb-2">Leather</span>
            <span class="inline-block bg-gray-900 rounded-full px-3  text-sm font-semibold text-gray-200 mr-2 mb-2">Lighting</span>
            <span class="inline-block bg-gray-900 rounded-full px-3  text-sm font-semibold text-gray-200 mr-2 mb-2">Minimal</span>
            <span class="inline-block bg-gray-900 rounded-full px-3  text-sm font-semibold text-gray-200 mr-2 mb-2">Practical</span>
            <span class="inline-block bg-gray-900 rounded-full px-3  text-sm font-semibold text-gray-200 mr-2 mb-2">Tableware</span>
            <span class="inline-block bg-gray-900 rounded-full px-3  text-sm font-semibold text-gray-200 mr-2 mb-2">Travel</span>
          </div>
      </div>
    <div class="flex-grow flex flex-wrap md:pr-20 -mb-10 md:text-left text-center order-first">
      <div class="lg:w-1/3 md:w-1/2 w-full px-4">
        <h2 class="title-font font-medium text-gray-900 tracking-widest text-sm mb-3">Sort By</h2>
        <nav class="list-none mb-5">
          <li class="p-1">
            <a class="text-gray-600 hover:text-gray-800">Default</a>
          </li>
          <li class="p-1">
            <a class="text-gray-600 hover:text-gray-800">Popularity</a>
          </li>
          <li class="p-1">
            <a class="text-gray-600 hover:text-gray-800">Average rating</a>
          </li>
          <li class="p-1 hover:text-yellow-400">
            <a class="text-yellow-600 hover:text-yellow-300">Newness</a>
          </li>
          <li class="p-1">
            <a class="text-gray-600 hover:text-gray-800">Price: Low to High</a>
          </li>
          <li class="p-1">
            <a class="text-gray-600 hover:text-gray-800">Price: High to Low</a>
          </li>
        </nav>
      </div>
      <div class="lg:w-1/3 md:w-1/2 w-full px-4">
        <h2 class="title-font font-medium text-gray-900 tracking-widest text-sm mb-3">Price</h2>
        <nav class="list-none mb-5">
          <li class="p-1">
            <a class="text-yellow-600 hover:text-yellow-300">All</a>
          </li>
          <li class="p-1">
            <a class="text-gray-600 py-10 hover:text-gray-800">$0- $50</a>
          </li>
          <li class="p-1">
            <a class="text-gray-600 py-10 hover:text-gray-800">$50 - $100</a>
          </li>
          <li class="p-1">
            <a class="text-gray-600 mt-2 hover:text-gray-800">$100 - $150</a>
          </li>
          <li class="p-1">
            <a class="text-gray-600 mt-2 hover:text-gray-800">$200</a>
          </li>
        </nav>
      </div>
      <div class="lg:w-1/3 md:w-1/2 w-full px-4">
        <h2 class="title-font font-medium text-gray-900 tracking-widest text-sm mb-3">Color</h2>
        <nav class="list-none mb-10">
          <li>
            <a class="text-gray-600 hover:text-gray-800">Blue</a>
          </li>
          <li>
            <a class="text-gray-600 hover:text-gray-800">Grown</a>
          </li>
          <li>
            <a class="text-gray-600 hover:text-gray-800">Gray</a>
          </li>
          <li>
            <a class="text-gray-600 hover:text-gray-800">Green</a>
          </li>
          <li>
            <a class="text-gray-600 hover:text-gray-800">Orange</a>
          </li>
          <li>
            <a class="text-gray-600 hover:text-gray-800">White</a>
          </li>
        </nav>
      </div>
    </div>
  </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      open: false,
    }

  }
}
</script>
