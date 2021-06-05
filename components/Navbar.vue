<template>
  <div>
    <header class="text-gray-600 body-font bg-green-100">
     <div class="container mx-auto flex flex-wrap p-5 flex-col md:flex-row items-center">
       <nav class="flex lg:w-2/5 flex-wrap items-center text-base md:ml-auto">
       <!---first dropdown---->
        <div class="relative group">
          <button class="flex flex-row items-center w-full px-4 py-4 mt-2 text-base text-right  bg-transparent rounded-lg md:w-auto md:inline md:mt-0 md:ml-4 focus:outline-none font-montserrat">
              <span>Shop</span>
          </button>
          <div class="absolute z-10 hidden bg-grey-200 group-hover:block">
              
              <div class="px-2 pt-2 pb-4  bg-gray-800 text-white shadow-lg">
                <div class="flex grid grid-cols-2 w-80 gap-4 md:grid-cols-2">
                  <div>
                    <p class="px-2 py-2">photo shop</p>
                    <ul class="list-none md:list-none">
                      <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Shop-Categories grid</a></li>
                      <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Shop-Fullscreen</a></li>
                      <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Shop-Header Search</a></li>
                      <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Shop-Infinite Scroll</a></li>
                      <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Shop-Masonry Grid</a></li>
                      <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Shop-Menus</a><sup class="bg-white text-gray-900"><span>New</span></sup></li>
                      <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Shop-Overlay</a></li>
                      <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Shop-Pagination</a></li>
                      <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Shop-Popup Filters</a></li>
                      <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Shop-Sidebar</a></li>
                    </ul>
                    <p class="px-2 py-2">Product Types</p>
                    <ul class="list-none md:list-none">
                      <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 px-2 py-2 hover:text-gray-100">Simple</a></li>
                      <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 px-2 py-2 hover:text-gray-100">Variable</a></li>
                      <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 px-2 py-2 hover:text-gray-100">Grouped</a></li>
                      <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 px-2 py-2 hover:text-gray-100">External/Affiliate</a></li>
                      <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 px-2 py-2 hover:text-gray-100">Out of stock</a></li>
                    </ul>
                  </div>
                  <div>
                    <p class="px-2 py-2">Product Layout</p>
                    <ul class="list-none md:list-none">
                      <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">No Background</a></li>
                      <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Switches & levels</a><sup class="bg-white text-gray-900"><span>New</span></sup></li>
                      <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Extend Description</a></li>
                      <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Gallery-Grid</a></li>
                      <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Gallery-Expnded</a></li>
                      <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Gallery-Horizon</a><sup class="bg-white text-gray-900"><span>New</span></sup></li>
                      <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Gallery-Scrolling</a></li>
                      <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Gallery-Scattered</a></li>
                      <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Featured Video</a></li>
                      <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Image Zoom</a></li>
                    </ul>
                    <p class="px-2 py-2">Shop Pages</p>
                    <ul class="list-none md:list-none">
                      <li><a href="#" class="text-sm text-gray-400 px-2 py-2 hover:text-gray-100">Cart</a></li>
                      <li><a href="#" class="text-sm text-gray-400 px-2 py-2 hover:text-gray-100">Checkout</a><sup class="bg-white text-gray-900"><span>New</span></sup></li>
                      <li><a href="#" class="text-sm text-gray-400 px-2 py-2 hover:text-gray-100">Order Tracking</a></li>
                      <li><a href="#" class="text-sm text-gray-400 px-2 py-2 hover:text-gray-100">My Account</a></li>
                      <li><a href="#" class="text-sm text-gray-400 px-2 py-2 hover:text-gray-100">Wishlist</a></li>
                    </ul>
                  </div>
                </div>
              </div>
          </div>
        </div> 
         <!---End 2nd dropdown---->
         <div class="relative group">
            <button class="flex flex-row items-center w-full px-4 py-4 mt-2 text-base text-right  bg-transparent rounded-lg md:w-auto md:inline md:mt-0 md:ml-4 focus:outline-none font-montserrat">
                <a href="#" class="mr-5 hover:text-gray-900">Categories<sup><small class="mx-2">NEW</small></sup></a>
            </button>
            <div class="absolute z-10 hidden bg-grey-200 group-hover:block">        
              <div class="px-2 pt-2 pb-4  bg-gray-800 text-white shadow-lg">
                <div class="flex grid grid-cols-2 w-80 gap-4 md:grid-cols-2">
                  <div>
                    <p class="px-2 py-2">photo shop</p>
                      <ul class="list-none md:list-none">
                        <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Shop-Categories grid</a></li>
                        <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Shop-Fullscreen</a></li>
                        <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Shop-Header Search</a></li>
                        <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Shop-Infinite Scroll</a></li>
                        <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Shop-Masonry Grid</a></li>
                        <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Shop-Menus</a><sup class="bg-white text-gray-900"><span>New</span></sup></li>
                        <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Shop-Overlay</a></li>
                        <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Shop-Pagination</a></li>
                        <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Shop-Popup Filters</a></li>
                        <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Shop-Sidebar</a></li>
                      </ul>
                    <p class="px-2 py-2">Product Types</p>
                      <ul class="list-none md:list-none">
                        <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 px-2 py-2 hover:text-gray-100">Simple</a></li>
                        <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 px-2 py-2 hover:text-gray-100">Variable</a></li>
                        <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 px-2 py-2 hover:text-gray-100">Grouped</a></li>
                        <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 px-2 py-2 hover:text-gray-100">External/Affiliate</a></li>
                        <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 px-2 py-2 hover:text-gray-100">Out of stock</a></li>
                      </ul>
                  </div>
                  <div>
                    <p class="px-2 py-2">Product Layout</p>
                      <ul class="list-none md:list-none">
                        <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">No Background</a></li>
                        <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Switches & levels</a><sup class="bg-white text-gray-900"><span>New</span></sup></li>
                        <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Extend Description</a></li>
                        <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Gallery-Grid</a></li>
                        <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Gallery-Expnded</a></li>
                        <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Gallery-Horizon</a><sup class="bg-white text-gray-900"><span>New</span></sup></li>
                        <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Gallery-Scrolling</a></li>
                        <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Gallery-Scattered</a></li>
                        <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Featured Video</a></li>
                        <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Image Zoom</a></li>
                      </ul>
                    <p class="px-2 py-2">Shop Pages</p>
                      <ul class="list-none md:list-none">
                        <li><a href="#" class="text-sm text-gray-400 px-2 py-2 hover:text-gray-100">Cart</a></li>
                        <li><a href="#" class="text-sm text-gray-400 px-2 py-2 hover:text-gray-100">Checkout</a><sup class="bg-white text-gray-900"><span>New</span></sup></li>
                        <li><a href="#" class="text-sm text-gray-400 px-2 py-2 hover:text-gray-100">Order Tracking</a></li>
                        <li><a href="#" class="text-sm text-gray-400 px-2 py-2 hover:text-gray-100">My Account</a></li>
                        <li><a href="#" class="text-sm text-gray-400 px-2 py-2 hover:text-gray-100">Wishlist</a></li>
                      </ul>
                  </div>
                </div>
              </div>
            </div>
          </div> 
         <!---End 3rd dropdown---->
         <div class="relative group">
          <button class="flex flex-row items-center w-full px-4 py-4 mt-2 text-base text-right  bg-transparent rounded-lg md:w-auto md:inline md:mt-0 md:ml-4 focus:outline-none font-montserrat">
              <a href="#" class="mr-5 hover:text-gray-900">pages</a>
          </button>
          <div class="absolute z-10 hidden bg-grey-200 group-hover:block">
              <div class="px-2 pt-2 pb-4  bg-gray-800 text-white shadow-lg">
                <div class="flex grid grid-cols-2 w-80 gap-4 md:grid-cols-2">
                  <div>
                    <ul class="list-none md:list-none">
                      <li class="px-2 py-1"><a href="#" class="text-sm text-gray-300 hover:text-gray-100">About Us</a></li>
                      <li class="px-2 py-1"><a href="#" class="text-sm text-gray-300 hover:text-gray-100">Blog</a></li>
                      <li class="px-2 py-1"><a href="#" class="text-sm text-gray-300 hover:text-gray-100">Blog-Classic+Sidebar</a></li>
                      <li class="px-2 py-1"><a href="#" class="text-sm text-gray-300 hover:text-gray-100">Blog-List</a></li>
                      <li class="px-2 py-1"><a href="#" class="text-sm text-gray-300 hover:text-gray-100">Blog-Infinite</a><sup class="bg-white text-gray-900 m-1"><span>New</span></sup></li>
                      <li class="px-2 py-1"><a href="#" class="text-sm text-gray-300 hover:text-gray-100">Blog-Single Post</a></li>
                      <li class="px-2 py-1"><a href="#" class="text-sm text-gray-300 hover:text-gray-100">Contact</a></li>
                      <li class="px-2 py-1"><a href="#" class="text-sm text-gray-300 hover:text-gray-100">Contact-Form</a></li>
                      <li class="px-2 py-1"><a href="#" class="text-sm text-gray-300 hover:text-gray-100">Fag</a></li>
                      <li class="px-2 py-1"><a href="#" class="text-sm text-gray-300 hover:text-gray-100">Portfolio</a></li>
                      <li class="px-2 py-1"><a href="#" class="text-sm text-gray-300 hover:text-gray-100">Portfolio-Single</a></li>
                      <li class="px-2 py-1"><a href="#" class="text-sm text-gray-300 hover:text-gray-100">404</a></li>
                    </ul>
                  </div> 
                </div>
              </div>
          </div>
          </div> 
         <!---End 3rd dropdown---->
          <!---4th dropdown---->
            <div class="relative group">
              <button class="flex flex-row items-center w-full px-4 py-4 mt-2 text-base text-right  bg-transparent rounded-lg md:w-auto md:inline md:mt-0 md:ml-4 focus:outline-none font-montserrat">
                  <a href="#" class="mr-5 hover:text-gray-900">pages</a>
              </button>
              <div class="absolute z-10 hidden bg-grey-200 group-hover:block">
                  <div class="px-2 pt-2 pb-4  bg-gray-800 text-white shadow-lg">
                    <div class="flex grid grid-cols-2 w-80 gap-4 md:grid-cols-2">
                      <div>
                        <p class="px-2 py-2">photo shop</p>
                        <ul class="list-none md:list-none">
                          <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Shop-Categories grid</a></li>
                          <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Shop-Fullscreen</a></li>
                          <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Shop-Header Search</a></li>
                          <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Shop-Infinite Scroll</a></li>
                          <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Shop-Masonry Grid</a></li>
                          <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Shop-Menus</a><sup class="bg-white text-gray-900"><span>New</span></sup></li>
                          <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Shop-Overlay</a></li>
                          <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Shop-Pagination</a></li>
                          <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Shop-Popup Filters</a></li>
                          <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Shop-Sidebar</a></li>
                        </ul>  
                      </div>
                      <div>
                        <p class="px-2 py-2">Product Layout</p>
                          <ul class="list-none md:list-none">
                            <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">No Background</a></li>
                            <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Switches & levels</a><sup class="bg-white text-gray-900"><span>New</span></sup></li>
                            <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Extend Description</a></li>
                            <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Gallery-Grid</a></li>
                            <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Gallery-Expnded</a></li>
                            <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Gallery-Horizon</a><sup class="bg-white text-gray-900"><span>New</span></sup></li>
                            <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Gallery-Scrolling</a></li>
                            <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Gallery-Scattered</a></li>
                            <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Featured Video</a></li>
                            <li class="px-2 py-1"><a href="#" class="text-sm text-gray-400 hover:text-gray-100">Image Zoom</a></li>
                          </ul>
                      </div>
                    </div>
                  </div>
              </div>
          </div> 
          
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

      <!---login modal--->
        <button class="text-white rounded bg-yellow-300 px-6 py-4 font-sans font-semibold shadow-lg hover:bg-yellow-800 outline-none active:outline-none focus:outline-none" @click="toggleModal = !toggleModal">
          Open Modal
        </button>
        <div class="fixed overflow-x-hidden overflow-y-auto inset-0 flex justify-center items-center z-50"
        v-if="toggleModal"
        >
        <div class="relative mx-auto w-full max-w-2xl">
        
      
    <!-- Auth Card Container -->
    <div class="grid place-items-center w-full mx-2 my-20 sm:my-auto">
        <!-- Auth Card -->
        <div class="w-full p-12 sm:w-8/12 md:w-6/12 lg:w-12/12 2xl:w-4/12 
            px-6 py-10 sm:px-10 sm:py-6 
            bg-white rounded-lg shadow-md lg:shadow-lg">

            <!-- Card Title -->
            <h2 class="text-center font-semibold text-3xl lg:text-4xl text-gray-800">
                Login
            </h2>

            <form class="mt-10" method="POST">
                <!-- Email Input -->
                <label for="email" class="block text-xs font-semibold text-gray-600 uppercase">E-mail</label>
                <input id="email" type="email" name="email" placeholder="e-mail address" autocomplete="email"
                    class="block w-full py-3 px-1 mt-2 
                    text-gray-800 appearance-none 
                    border-b-2 border-gray-100
                    focus:text-gray-500 focus:outline-none focus:border-gray-200"
                    required />

                <!-- Password Input -->
                <label for="password" class="block mt-2 text-xs font-semibold text-gray-600 uppercase">Password</label>
                <input id="password" type="password" name="password" placeholder="password" autocomplete="current-password"
                    class="block w-full py-3 px-1 mt-2 mb-4
                    text-gray-800 appearance-none 
                    border-b-2 border-gray-100
                    focus:text-gray-500 focus:outline-none focus:border-gray-200"
                    required />

                <!-- Auth Buttton -->
                <button type="submit"
                    class="w-full py-3 mt-10 bg-gray-800 rounded-sm
                    font-medium text-white uppercase
                    focus:outline-none hover:bg-gray-700 hover:shadow-none">
                    Login
                </button>

                <!-- Another Auth Routes -->
                <div class="sm:flex sm:flex-wrap mt-8 sm:mb-4 text-sm text-center">
                    <a href="forgot-password" class="flex-2 underline">
                        Forgot password?
                    </a>

                    <p class="flex-1 text-gray-500 text-md mx-4 my-1 sm:my-auto">
                        or
                    </p>
        
                    <a href="register" class="flex-2 underline">
                        Create an Account
                    </a>
                </div>
            </form>
        </div>
    </div>
   
<button class="rounded bg-red-500 text-white px-6 mt-1 py-2"
               @click="toggleModal=false">close
            </button>
          
        </div>
        </div>
      <!---login modal---->
        <a href="#" class="mr-5 hover:text-gray-900">Cart<sup class="mx-2 text-yellow-500">0</sup></a>
      </div>
     </div>
   </header>
  </div>
</template>

<script>
export default {
  data() {
    return {
     toggleModal: false
    }

  }
}
</script>
