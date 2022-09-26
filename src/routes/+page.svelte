<script>
	import Cat from "../lib/header/bg-curataro.png";
	import Cash from "../lib/header/cash.png";
	import Swipe from "../lib/header/swipe.png";
	import Wallet from "../lib/header/wallet.png";
	import Lucian from "../lib/header/Lucian.png";
	import Naomi from "../lib/header/Naomi.png";
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<section class="bg-color p-20 pb-1 px-28">
	<div class="flex flex-row"> 
      <div class="w-5/12 m-auto"> 
		<h1 class="text-left mb-5 text-7xl pr-1">The future of NFT curation<br/> 
			<span>is NEAR</span></h1>
		<p class="mb-5 text-2xl font-normal">Support the NFT ecosystem, curate, and earn rewards.</p>
		<div class="flex flex-row gap-x-7"> 
			<button type="button" class="text-black font-bold btn-color transition-colors rounded-lg text-md px-10 py-2.5 ">Start Curating</button>
			<button type="button" class="text-black font-bold btn-color1 transition-colors rounded-lg text-md px-10 py-2.5 ">Explore NFTs</button>
		</div>	
	  </div>

	  <div class="w-6/12 m-auto"> 
		<img class="w-full shadow-2xl rounded-lg drop-shadow-2xl" alt="" src="https://cdn.technadu.com/wp-content/uploads/2022/04/Kocho_Shinobu_Demon_Slayer.png" />
	  </div>

	</div>
	
	<img class="m-auto mt-40" alt="" src={Cat} />

</section>

<section class="bg-color pb-10"> 
	<div> 
		<h1>How it works</h1>
		<div class="flex flex-row justify-center gap-x-40 mt-20"> 
		  <div> 
			<div class="bg-white w-36 h-36 rounded-full p-5">
			<img class="m-auto" alt="" src={Wallet} />
			</div>
			<h3 class="font-bold text-xl text-center mt-5">Connect Wallet</h3>
		  </div>
		  
		  <div> 
			<div class="bg-white w-36 h-36 rounded-full p-5">
			<img class="m-auto mt-2" alt="" src={Swipe} />
			</div>
			<h3 class="font-bold text-xl text-center mt-5">Start Curating</h3>
		  </div>
	
		  <div> 
			<div class="bg-white w-36 h-36 rounded-full p-5">
			<img class="m-auto" alt="" src={Cash} />
			</div>
			<h3 class="font-bold text-xl text-center mt-5">Earn Tokens</h3>
		  </div>
		  
		</div>
	  </div>

</section>

<section class="bg-color pb-20"> 
	<div class="pt-20"> 
		<h1>Who built this?</h1>
		<div class="flex flex-row justify-center gap-x-40 mt-20"> 
		  
		  <div> 
			
			<img class="m-auto rounded-full" alt="" src={Lucian} />
			
			<a href="https://devpost.com/DJkal11"><h3 class="font-bold text-xl text-center mt-5">@DJKal11</h3></a>
		  </div>
	
		  <div> 
			
			<img class="m-auto  rounded-full" alt="" src={Naomi} />
			
			<a href="https://devpost.com/Na0xmi"><h3 class="font-bold text-xl text-center mt-5">@Na0xmi</h3></a>
		  </div>
		  
		</div>
	  </div>

</section>

<style>
@import url('https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@400;500;600;700&display=swap');

section {
	font-family: 'Cormorant Garamond', serif;
	
}

.btn-color {
	background-color: #FFAAA6;
  }

  .btn-color:hover {
	background-color: #ff908a;
  }

	 .bg-color {
    background-color: #DCEDC2;
  }

  .btn-color1 {
	border: 2px solid #FFAAA6;
	background-color: transparent;
	color: #FFAAA6;
  }

  .btn-color1:hover {
	border: 2px solid #FFAAA6;
	background-color: #FFAAA6;
	color: black;
  }

  span {
	color: #FFAAA6;
  }

  a {
	color: black;
  }
	
</style>
