<template>
  <div class="bg-gray-200 px-4 py-2">
      <!-- Breadcrumbs -->
      <section class="text-gray-600 body-font">
        <div class="container px-5 py-10 mx-auto flex items-center md:flex-row flex-col">
          <div class="flex flex-col md:pr-10 md:mb-0 mb-6 pr-0 w-full md:w-auto md:text-left text-center">
            <div class="container px-5  mx-auto">
                  <nuxt-link to="/" class="hover:underline text-yellow-600">All</nuxt-link>
                  <nuxt-link :to="{ name: 'Bags' }" class="text-gray-600 hover:text-yellow-600">/Bags & Backpacks</nuxt-link>
                  <nuxt-link :to="{ name: 'Decoration' }" class="text-gray-600 hover:text-yellow-600">/ Decoration</nuxt-link>
                  <nuxt-link :to="{ name: 'Essentials' }" class="text-gray-600 hover:text-yellow-600">/ Essentials</nuxt-link>
                  <nuxt-link :to="{ name: 'Interior' }" class="text-gray-600 hover:text-yellow-600">/ Interior</nuxt-link>
              </div>
          </div>
          <div class="relative flex md:ml-auto md:mr-0 mx-auto items-center flex-shrink-0 space-x-4">
          <a :to="{ name: 'Essentials' }" class="text-gray-600 hover:text-yellow-600" @click="open = !open">Filter</a>
       <!-- Breadcrumbs -->
            <a :to="{ name: 'Interior' }" class="text-gray-600 hover:text-yellow-600"><span>/</span> Search
            </a>
          </div>
        </div>
      </section>
      <!---filter section---->
         <!---filter--->
         <div v-if="open" class="container px-5 py-24 absoulate w-full mt-12bg-gray-100 border-t mx-auto flex md:items-center lg:items-start md:flex-row md:flex-nowrap flex-wrap flex-col">
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
  <!---filter----> 
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

<style>

</style>