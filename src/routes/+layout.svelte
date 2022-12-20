<script>
	import { page } from '$app/stores';
	import '../app.css';
</script>

<div class="absolute z-[100] left-0 w-full flex justify-center space-x-6 text-white top-8">
	<a href="/" class={`font-bold ${$page.route.id === '/' ? 'underline' : ''}`}>Home</a>
	<a href="/projects" class={`font-bold ${$page.route.id === '/projects' ? 'underline' : ''}`}
		>Projects</a
	>
</div>

<slot />

<div class="mx-auto max-w-2xl my-12">
	<hr>
	<div class="mt-6 flex justify-center space-x-6">
		<a href="https://github.com/almostapps" rel="noreferrer" class="hover:underline">GitHub</a>
		<a href="https://discord.gg/ubqeRSakvG" rel="noreferrer" class="hover:underline">Discord</a>
	</div>

</div>
