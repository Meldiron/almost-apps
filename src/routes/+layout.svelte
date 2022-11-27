<script>
	import '../app.css';
</script>

<header class="p-6 mt-2 text-slate-800 flex flex-col md:flex-row space-y-4 md:space-y-0 items-center justify-between">
	<h1 class="title text-2xl">Almost Apps</h1>

	<div class="flex items-center justify-center space-x-3">
		<a href="/" class="rounded-full bg-[#f6f6f6] text-slate-800 px-4 py-2">Home</a>
		<a href="/projects" class="rounded-full bg-white text-slate-800 px-4 py-2">Projects</a>
        <a href="/about-us" class="rounded-full bg-white text-slate-800 px-4 py-2">About Us</a>
		<a href="/contact" class="rounded-full bg-white text-slate-800 px-4 py-2">Contact</a>
	</div>

	<button on:click={() => alert("Please contact us at contact@almostapps.eu")} class="rounded-full bg-slate-800 text-white px-6 py-2">Become Sponsor</button>
</header>

<div class="container mx-auto grid grid-cols-12 gap-6 py-6 px-3">
	<div class="col-span-12 lg:col-span-6 bg-[#f6f6f6] rounded-[40px] w-full p-8">
		<h1 class="text-5xl mb-4">👋</h1>
		<p class="text-xl text-slate-800 mb-3">
			<b class="font-bolder">Almost Apps</b> is a set of projects replicating iconic functionalities
			of existing applications.
		</p>
		<p class="text-slate-600 mb-3">
			Projects do not focus on design itself, only the integration. We don't claim authorship of any
			design.
		</p>
		<p class="text-slate-600">All Almost Projects are free and made for education purposes.</p>
	</div>

    <a class="col-span-12 sm:col-span-6 lg:col-span-3" href="https://github.com/almostapps">

	<button
		class="w-full relative bg-[#181717] text-white rounded-[40px] flex items-center justify-center aspect-square h-full"
	>
		<svg role="img" class="w-24 h-24" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"
			><title>GitHub</title><path
				fill="currentColor"
				d="M12 .297c-6.63 0-12 5.373-12 12 0 5.303 3.438 9.8 8.205 11.385.6.113.82-.258.82-.577 0-.285-.01-1.04-.015-2.04-3.338.724-4.042-1.61-4.042-1.61C4.422 18.07 3.633 17.7 3.633 17.7c-1.087-.744.084-.729.084-.729 1.205.084 1.838 1.236 1.838 1.236 1.07 1.835 2.809 1.305 3.495.998.108-.776.417-1.305.76-1.605-2.665-.3-5.466-1.332-5.466-5.93 0-1.31.465-2.38 1.235-3.22-.135-.303-.54-1.523.105-3.176 0 0 1.005-.322 3.3 1.23.96-.267 1.98-.399 3-.405 1.02.006 2.04.138 3 .405 2.28-1.552 3.285-1.23 3.285-1.23.645 1.653.24 2.873.12 3.176.765.84 1.23 1.91 1.23 3.22 0 4.61-2.805 5.625-5.475 5.92.42.36.81 1.096.81 2.22 0 1.606-.015 2.896-.015 3.286 0 .315.21.69.825.57C20.565 22.092 24 17.592 24 12.297c0-6.627-5.373-12-12-12"
			/></svg
		>

		<div class="absolute top-4 w-full">
			<h2 class="text-center text-lg text-white opacity-50 font-medium my-4 shrink-0">
				GitHub Organization
			</h2>
		</div>

		<div class="absolute bottom-4 left-4">
				<div class="p-3 rounded-full bg-white text-black">
					<svg
						xmlns="http://www.w3.org/2000/svg"
						fill="none"
						viewBox="0 0 24 24"
						stroke-width="2"
						stroke="currentColor"
						class="w-5 h-5"
					>
						<path
							stroke-linecap="round"
							stroke-linejoin="round"
							d="M13.19 8.688a4.5 4.5 0 011.242 7.244l-4.5 4.5a4.5 4.5 0 01-6.364-6.364l1.757-1.757m13.35-.622l1.757-1.757a4.5 4.5 0 00-6.364-6.364l-4.5 4.5a4.5 4.5 0 001.242 7.244"
						/>
					</svg>
				</div>
		</div>
	</button>
</a>

<a class="col-span-12 sm:col-span-6 lg:col-span-3" href="https://discord.gg/ubqeRSakvG">

	<div
		class="relative bg-[#5865F2] w-full text-white rounded-[40px] flex items-center justify-center aspect-square h-full"
	>
		<svg class="w-24 h-24" role="img" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"
			><title>Discord</title><path
				fill="currentColor"
				d="M20.317 4.3698a19.7913 19.7913 0 00-4.8851-1.5152.0741.0741 0 00-.0785.0371c-.211.3753-.4447.8648-.6083 1.2495-1.8447-.2762-3.68-.2762-5.4868 0-.1636-.3933-.4058-.8742-.6177-1.2495a.077.077 0 00-.0785-.037 19.7363 19.7363 0 00-4.8852 1.515.0699.0699 0 00-.0321.0277C.5334 9.0458-.319 13.5799.0992 18.0578a.0824.0824 0 00.0312.0561c2.0528 1.5076 4.0413 2.4228 5.9929 3.0294a.0777.0777 0 00.0842-.0276c.4616-.6304.8731-1.2952 1.226-1.9942a.076.076 0 00-.0416-.1057c-.6528-.2476-1.2743-.5495-1.8722-.8923a.077.077 0 01-.0076-.1277c.1258-.0943.2517-.1923.3718-.2914a.0743.0743 0 01.0776-.0105c3.9278 1.7933 8.18 1.7933 12.0614 0a.0739.0739 0 01.0785.0095c.1202.099.246.1981.3728.2924a.077.077 0 01-.0066.1276 12.2986 12.2986 0 01-1.873.8914.0766.0766 0 00-.0407.1067c.3604.698.7719 1.3628 1.225 1.9932a.076.076 0 00.0842.0286c1.961-.6067 3.9495-1.5219 6.0023-3.0294a.077.077 0 00.0313-.0552c.5004-5.177-.8382-9.6739-3.5485-13.6604a.061.061 0 00-.0312-.0286zM8.02 15.3312c-1.1825 0-2.1569-1.0857-2.1569-2.419 0-1.3332.9555-2.4189 2.157-2.4189 1.2108 0 2.1757 1.0952 2.1568 2.419 0 1.3332-.9555 2.4189-2.1569 2.4189zm7.9748 0c-1.1825 0-2.1569-1.0857-2.1569-2.419 0-1.3332.9554-2.4189 2.1569-2.4189 1.2108 0 2.1757 1.0952 2.1568 2.419 0 1.3332-.946 2.4189-2.1568 2.4189Z"
			/></svg
		>

		<div class="absolute top-4 w-full">
			<h2 class="text-center text-lg text-white opacity-50 font-medium my-4 shrink-0">
				Discord Server
			</h2>
		</div>

		<div class="absolute bottom-4 left-4">
				<div class="p-3 rounded-full bg-white text-black">
					<svg
						xmlns="http://www.w3.org/2000/svg"
						fill="none"
						viewBox="0 0 24 24"
						stroke-width="2"
						stroke="currentColor"
						class="w-5 h-5"
					>
						<path
							stroke-linecap="round"
							stroke-linejoin="round"
							d="M13.19 8.688a4.5 4.5 0 011.242 7.244l-4.5 4.5a4.5 4.5 0 01-6.364-6.364l1.757-1.757m13.35-.622l1.757-1.757a4.5 4.5 0 00-6.364-6.364l-4.5 4.5a4.5 4.5 0 001.242 7.244"
						/>
					</svg>
				</div>
		</div>
	</div>
    </a>

    <div class="col-span-12 md:col-span-6 bg-gradient-to-br from-lime-400 to-green-500 rounded-[40px] w-full p-8 flex items-center justify-center">
		<h1 class="text-5xl text-white text-center p-12">Open Source</h1>
	</div>

    <div class="col-span-12 md:col-span-6 bg-gradient-to-br from-[#dd4367] to-[#f02e65] rounded-[40px] w-full p-8 flex items-center justify-center">
		<h1 class="text-5xl text-white text-center p-12">Appwrite Backend</h1>
	</div>

    <div class="col-span-12 rounded-[40px] w-full p-8 flex justify-center items-center">
        <h1 class="text-5xl mb-4 text-slate-300">(project list coming soon)</h1>
	</div>

    <div class="col-span-12 bg-slate-900 rounded-[40px] w-full p-8">
        <h1 class="text-5xl mb-4">💬</h1>
        <h1 class="text-5xl mb-4 text-white">Get in Touch</h1>
		<p class="leading-relaxed text-xl text-slate-400 mb-3">
			Wanna Chat? Provide feedback? Talk about sponsorship? Reach us at <a href="mailto:contact@almostapps.eu" class="bg-white rounded-xl px-2 py-1 text-slate-800">contact@almostapps.eu</a>.
		</p>
	</div>
</div>


<slot />