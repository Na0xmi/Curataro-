<script>
	import { page } from '$app/stores';
	import Logo from "../header/curataro.png";
</script>

<header>
	<nav class="bg-color border-gray-200 px-2 sm:px-4 py-2.5 rounded dark:bg-gray-900">
		<div class="container flex flex-wrap justify-between items-center mx-auto">
		<a href="/" class="flex items-center">
			<img src={Logo} class="w-40 " alt="Flowbite Logo">
		</a>
		<div class="flex justify-between gap-x-12 h-12">
		<div class="flex md:order-2">
			<button type="button" class="text-black font-bold btn-color transition-colors rounded-lg text-md px-10 py-2.5 ">Connect Wallet</button>
			<button data-collapse-toggle="navbar-cta" type="button" class="inline-flex items-center p-2 text-sm text-gray-500 rounded-lg md:hidden hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200 dark:text-gray-400 dark:hover:bg-gray-700 dark:focus:ring-gray-600" aria-controls="navbar-cta" aria-expanded="false">
			  <span class="sr-only">Open main menu</span>
			  <svg class="w-6 h-6" aria-hidden="true" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z" clip-rule="evenodd"></path></svg>
		  </button>
		</div>
		<div class="hidden justify-between items-center w-full md:flex md:w-auto md:order-1" id="navbar-cta">
		  <ul class="flex gap-7 flex-col p-4 mt-4 bg-color rounded-lg border border-gray-100 md:flex-row md:space-x-8 md:mt-0 md:text-sm md:font-medium md:border-0 md:bg-white dark:bg-gray-800 md:dark:bg-gray-900 dark:border-gray-700">
		   
			<li>
			  <a href="#" class="block text-lg py-2 pr-4 pl-3 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:hover:text-blue-700 md:p-0 md:dark:hover:text-white dark:text-gray-400 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700">About</a>
			</li>
			<li>
			  <a href="#" class="block text-lg py-2 pr-4 pl-3 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:hover:text-blue-700 md:p-0 md:dark:hover:text-white dark:text-gray-400 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700">NFT Gallery</a>
			</li>
			
		  </ul>
		</div>
	  </div>
		</div>
	  </nav>
</header>

<style>
@import url('https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@400;500;600;700&display=swap');

header {
	font-family: 'Cormorant Garamond', serif;
	
}

	 .bg-color {
    background-color: #DCEDC2;
  }

  .btn-color {
	background-color: #FFAAA6;
  }

  .btn-color:hover {
	background-color: #ff908a;
  }

	a:hover {
		color: var(--accent-color);
	}
</style>
