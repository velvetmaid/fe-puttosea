<script>
	import '../app.css';
	import Footer from '../components/Footer.svelte';
	import Navbar from '../components/Navbar.svelte';
</script>

<div class="w-full min-h-screen">
	<div
		class="h-screen bg-center bg-cover lg:h-[32rem] bg-[url('/images/header-bg.jpg')] lg:bg-cover lg:bg-center"
	>
		<Navbar />
	</div>
	<slot />
	<Footer />
</div>
