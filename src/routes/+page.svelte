<script>
	import * as m from '$lib/paraglide/messages';
	import { i18n } from '$lib/i18n';
	import { page } from '$app/state';
	import { goto } from '$app/navigation';

	function switchToLanguage(newLanguage) {
		const canonicalPath = i18n.route(page.url.pathname);
		const localisedPath = i18n.resolveRoute(canonicalPath, newLanguage);

		goto(localisedPath);
	}
</script>

<svelte:head>
	<title>LibreFest...</title>
</svelte:head>

<div class="container mx-auto flex-grow">
	<div class="mx-5 lg:mx-0">
		<div
			class="mx-auto grid max-w-screen-xl px-4 py-8 lg:grid-cols-12 lg:gap-8 lg:pt-12 lg:pb-16 xl:gap-0"
		>
			<div class="mr-auto place-self-center lg:col-span-7">
				<h1
					class="mb-6 max-w-2xl text-4xl leading-none font-extrabold tracking-tight md:text-5xl xl:text-6xl"
				>
					{m.header_website()}
				</h1>
				<p class="mb-6 max-w-2xl font-light text-gray-500 md:text-lg lg:mb-10 lg:text-xl">
					{m.coming_info()}
				</p>
				<button
					class="mr-2 mb-2 inline-flex items-center rounded-lg bg-[#050708] px-5 py-2.5 text-center text-sm font-medium text-white hover:bg-[#050708]/80 focus:ring-4 focus:ring-[#050708]/50 dark:hover:bg-[#050708]/40 dark:focus:ring-gray-600"
					onclick={() => switchToLanguage('bg')}>БГ</button
				>
				<button
					class="mr-2 mb-2 inline-flex items-center rounded-lg bg-[#050708] px-5 py-2.5 text-center text-sm font-medium text-white hover:bg-[#050708]/80 focus:ring-4 focus:ring-[#050708]/50 dark:hover:bg-[#050708]/40 dark:focus:ring-gray-600"
					onclick={() => switchToLanguage('en')}>EN</button
				>
			</div>
		</div>
	</div>
</div>
