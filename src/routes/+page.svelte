<script>
	// your script goes here
	import { Github, Twitter } from 'lucide-svelte';
</script>

<div class=" h-screen px-10 pt-40 sm:max-w-lg mx-auto">
	<header class="flex justify-between flex-1 items-center mb-10">
		<figure class="flex items-center gap-3">
			<img src="mili.jpeg" alt="Avatar" class="w-12 h-12 rounded-full" />
			<figcaption class="flex flex-col">
				<span>mili is my name</span>
				<span>fullstack dev</span>
			</figcaption>
		</figure>
		<nav>
			<ul class="flex gap-3 justify-between">
				<li>
					<a href="https://twitter.com/milimyname"><Twitter /></a>
				</li>
				<li>
					<a href="https://github.com/milimyname"> <Github /></a>
				</li>
			</ul>
		</nav>
	</header>
	<main>
		<h1 class="font-medium text-xl mb-10">projects</h1>
		<ul class="flex flex-col gap-5">
			<li>
				<a href="https://taijobi.com" target="_blank">
					<figure class="flex items-center gap-2">
						<img src="taijobi.png" alt="Avatar" class="w-10 h-10" />
						<figcaption class="flex flex-col">
							<span class="underline">Taijobi</span>
							<span>a japanese learning platform for now or maybe</span>
						</figcaption>
					</figure>
				</a>
			</li>
			<li>
				<a href="https://app.mili-my.name" target="_blank">
					<figure class="flex items-center gap-2">
						<img src="bookself.png" alt="Avatar" class="w-10 h-10 invert" />
						<figcaption class="flex flex-col">
							<span class="underline">Bookself</span>
							<span>an auto booking platform</span>
						</figcaption>
					</figure>
				</a>
			</li>
		</ul>
	</main>
</div>

<style>
	:global(html) {
		background-color: theme('colors.gray.800');
		color: theme('colors.white');
	}
</style>
