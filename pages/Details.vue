<template>
  <div>
    <div class="py-6">
    <!-- Breadcrumbs -->
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="flex items-center space-x-2 text-gray-400 text-sm">
        <a href="#" class="hover:underline hover:text-gray-600">Home</a>
        <span>
            <svg class="h-5 w-5 leading-none text-gray-300" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" />
            </svg>
        </span>
        <a href="#" class="hover:underline hover:text-gray-600">Electronics</a>
        <span>
            <svg class="h-5 w-5 leading-none text-gray-300" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" />
            </svg>
        </span>
        <span>Headphones</span>
        </div>
    </div>
    <!-- ./ Breadcrumbs -->

    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 mt-6">
        <div class="flex flex-col md:flex-row -mx-4">
        <div class="md:flex-1 px-4">
            <div x-data="{ image: 1 }" x-cloak>
            <div class="h-64 md:h-80 rounded-lg bg-gray-100 mb-4">
                <div x-show="image === 1" class="h-64 md:h-80 rounded-lg bg-gray-100 mb-4 flex items-center justify-center">
                <span class="text-5xl">1</span>
                </div>

                <div x-show="image === 2" class="h-64 md:h-80 rounded-lg bg-gray-100 mb-4 flex items-center justify-center">
                <span class="text-5xl">2</span>
                </div>

                <div x-show="image === 3" class="h-64 md:h-80 rounded-lg bg-gray-100 mb-4 flex items-center justify-center">
                <span class="text-5xl">3</span>
                </div>

                <div x-show="image === 4" class="h-64 md:h-80 rounded-lg bg-gray-100 mb-4 flex items-center justify-center">
                <span class="text-5xl">4</span>
                </div>
            </div>

            <div class="flex -mx-2 mb-4">
                <template x-for="i in 4">
                <div class="flex-1 px-2">
                    <button x-on:click="image = i" :class="{ 'ring-2 ring-indigo-300 ring-inset': image === i }" class="focus:outline-none w-full rounded-lg h-24 md:h-32 bg-gray-100 flex items-center justify-center">
                    <span x-text="i" class="text-2xl"></span>
                    </button>
                </div>
                </template>
            </div>
            </div>
        </div>
        <div class="md:flex-1 px-4">
            <h2 class="mb-2 leading-tight tracking-tight font-bold text-gray-800 text-2xl md:text-3xl">Lorem ipsum dolor, sit amet consectetur, adipisicing elit.</h2>
            <p class="text-gray-500 text-sm">By <a href="#" class="text-indigo-600 hover:underline">ABC Company</a></p>

            <div class="flex items-center space-x-4 my-4">
            <div>
                <div class="rounded-lg bg-gray-100 flex py-2 px-3">
                <span class="text-indigo-400 mr-1 mt-1">$</span>
                <span class="font-bold text-indigo-600 text-3xl">25</span>
                </div>
            </div>
            <div class="flex-1">
                <p class="text-green-500 text-xl font-semibold">Save 12%</p>
                <p class="text-gray-400 text-sm">Inclusive of all Taxes.</p>
            </div>
            </div>

            <p class="text-gray-500">Lorem ipsum, dolor sit, amet consectetur adipisicing elit. Vitae exercitationem porro saepe ea harum corrupti vero id laudantium enim, libero blanditiis expedita cupiditate a est.</p>

            <div class="flex py-4 space-x-4">
            <div class="relative">
                <div class="text-center left-0 pt-2 right-0 absolute block text-xs uppercase text-gray-400 tracking-wide font-semibold">Qty</div>
                <select class="cursor-pointer appearance-none rounded-xl border border-gray-200 pl-4 pr-8 h-14 flex items-end pb-1">
                <option>1</option>
                <option>2</option>
                <option>3</option>
                <option>4</option>
                <option>5</option>
                </select>

                <svg class="w-5 h-5 text-gray-400 absolute right-0 bottom-0 mb-2 mr-2" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 9l4-4 4 4m0 6l-4 4-4-4" />
                </svg>
            </div>

            <button type="button" class="h-14 px-6 py-2 font-semibold rounded-xl bg-indigo-600 hover:bg-indigo-500 text-white">
                Add to Cart
            </button>
            </div>
        </div>
        </div>
    </div>
    </div>






<section class="container">
  <h1>Pure CSS Mega Menu Navigation</h1>
  <h2>Not a single line of jQuery in sight!</h2>
</section><!-- .container -->

<nav>
  <ul class="container ul-reset">
   
    <li class='droppable'>
      <a href='#'>Category Two</a>
      <div class='mega-menu'>
        <div class="container cf">
          <ul class="ul-reset">
            <h3>Heading 1</h3>
             <li><img src="http://placehold.it/205x172"></li>
            
          </ul><!-- .ul-reset -->
          <ul class="ul-reset">
            <h3>Heading 2</h3>
             <li><img src="http://placehold.it/205x172"></li>
          </ul><!-- .ul-reset -->
          <ul class="ul-reset">
            <h3>Heading 3</h3>
             <li><img src="http://placehold.it/205x172"></li>
          </ul><!-- .ul-reset -->
          <ul class="ul-reset">
            <h3>Heading 4</h3>
            <li><img src="http://placehold.it/205x172"></li>
          </ul><!-- .ul-reset -->
        </div><!-- .container -->
      </div><!-- .mega-menu-->
    </li><!-- .droppable -->
   
  </ul><!-- .container .ul-reset -->
</nav>








  </div>
</template>

<script>
export default {

}
</script>
<style>
/* #Resets
–––––––––––––––––––––––––––––––––––––––––––––––––– */
html {box-sizing: border-box;}
*, *:before, *:after {box-sizing: inherit;  }



/* #Universal and Default Styles
–––––––––––––––––––––––––––––––––––––––––––––––––– */
body {
  	background: url(https://s3-us-west-2.amazonaws.com/s.cdpn.io/323039/black-wood-small.jpg);
  	color: #ddd;
  	font-family: "Open Sans", sans-serif;
  	font-size: 14px;
	line-height: 1;
	margin: 0;
	padding: 0;
	text-align: center;
}
a {text-decoration: none;}
h1 {
	font-size: 40px;
  	font-weight: 700;
	margin-bottom: 20px;
  	margin-top: 20px;
}
h2 {
	font-size: 15px;
  	font-weight: 600;
	margin-bottom: 30px;
  	margin-top: 10px;
}
.container {
	margin: auto;
	width: 940px;
}
.ul-reset {
	padding-left: 0;
   margin-top: 0;
   margin-bottom: 0;
	list-style: none;
}



/* #Navigation Styles
–––––––––––––––––––––––––––––––––––––––––––––––––– */
nav {
	background: #424242;
	font-size: 0;
	position: relative;
}
nav > ul > li {
	display: inline-block;
  	font-size: 14px;
  	padding: 0 15px;
  	position: relative;
}
nav > ul > li:first-child {padding-left: 0;}
nav > ul > li:last-child {padding-right: 0;}
nav > ul > li > a {
	color: #fff;
  	display: block;
  	position: relative;
  	padding: 20px 0;
  	border-bottom: 3px solid transparent;
}
nav > ul > li:hover > a {
	color: #69aae0; 
  	border-bottom: 3px solid #69aae0;
}



/* #Mega Menu Styles
–––––––––––––––––––––––––––––––––––––––––––––––––– */
.mega-menu {
	background: #f0f0f0;
  	display: none;
  	left: 0;
  	position: absolute;
  	text-align: left;
  	width: 100%;
}
.mega-menu h3 {color: #444;}
.mega-menu ul {
	float: left;
  	margin-bottom: 20px;
  	margin-right: 40px;
  	width: 205px;
}
.mega-menu ul:last-child {margin-right: 0;}
.mega-menu a {
	border-bottom: 1px solid #ddd;
  	color: #4ea3d8;
  	display: block;
  	padding: 10px 0;
}
.mega-menu a:hover {color: #2d6a91;}



/* #Droppable Class Styles
–––––––––––––––––––––––––––––––––––––––––––––––––– */
.droppable {position: static;}
.droppable > a:after {
	content: "\f107";
  	font-family: FontAwesome;
  	font-size: 12px;
  	padding-left: 6px;
  	position: relative;
  	top: -1px;
}
.droppable:hover .mega-menu {display: block;}



/* #Browser Clearfix
–––––––––––––––––––––––––––––––––––––––––––––––––– */
.cf:before,
.cf:after {
	content: " "; /* 1 */
   display: table; /* 2 */
}
.cf:after {clear: both;}
</style>