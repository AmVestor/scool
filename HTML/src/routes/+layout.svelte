<script lang="ts">
	import '../app.postcss';
</script>

<div class="flex h-screen w-screen flex-col justify-between items-center">
	<header>
		<d	iv class="flex justify-between items-center w-full bg-gray-900">
			<div class="flex items-center">
				<a href="/" class="text-2xl font-bold  text-blue-500"
					>Boot<span class="text-red-500">Camp</span></a
				>
				<nav class="flex ml-4">
					<a href="/about" class="ml-4">About</a>
						</nav>
					</div>
			<div class="flex items-center">
				<a href="" class="ml-4">Login</a>
				<a href="" class="ml-4">Register</a>
			</div>
		</div>
	</header>
	<main>

		
		<slot />
			</main>
			<footer class="bg-gray-800 text-white text-center text-xs p-3 w-full">&copy; 2020</footer>
</div>
