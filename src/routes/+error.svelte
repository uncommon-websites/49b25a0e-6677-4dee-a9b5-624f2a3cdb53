<script lang="ts">
	import { page } from "$app/state";
</script>

<main class="min-h-screen flex items-center justify-center bg-white px-6">
	<div class="text-center">
		<h1 class="text-6xl font-light text-gray-900 mb-4">Error {page.status}</h1>
		<p class="text-gray-500 text-lg mb-8">{page.error?.message ?? "Something went wrong."}</p>
		<a href="/" class="bg-primary-600 hover:bg-primary-700 text-white px-6 py-3 rounded-full text-sm font-medium transition-colors inline-block">
			Return to Home
		</a>
	</div>
</main>
