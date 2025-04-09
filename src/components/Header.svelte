<script>
	import deerLogo from '../img/LibreFest_Avatar_3.svg';
</script>

<header class="sticky top-0 bg-white shadow">
	<menu class="container mx-auto flex flex-col items-center justify-between px-8 py-4 lg:flex-row">
		<div class="font-freeman flex items-center text-3xl">
			<div class="mr-4 w-12">
				<img src={deerLogo} alt="LibreFest Logo" />
			</div>
			LibreFest
		</div>
		<nav class="mt-4 flex p-4 sm:mt-0">
			<a
				class="relative mx-4 cursor-pointer pb-0.5 after:absolute after:bottom-0 after:left-0 after:h-0.5 after:w-0 after:bg-black after:transition-all after:duration-500 hover:after:w-full"
				href="https://librefest.org/"
				>Начало
			</a>
			<a
				class="relative mx-4 cursor-pointer pb-0.5 after:absolute after:bottom-0 after:left-0 after:h-0.5 after:w-0 after:bg-black after:transition-all after:duration-500 hover:after:w-full"
				href="#event"
				>За събитието
			</a>
			<a
				class="relative mx-4 cursor-pointer pb-0.5 after:absolute after:bottom-0 after:left-0 after:h-0.5 after:w-0 after:bg-black after:transition-all after:duration-500 hover:after:w-full"
				href="#agenda"
				>Програма
			</a>
			<a
				class="relative mx-4 cursor-pointer pb-0.5 after:absolute after:bottom-0 after:left-0 after:h-0.5 after:w-0 after:bg-black after:transition-all after:duration-500 hover:after:w-full"
				href="#map"
				>Карта
			</a>
			<a
				class="relative mx-4 cursor-pointer pb-0.5 after:absolute after:bottom-0 after:left-0 after:h-0.5 after:w-0 after:bg-black after:transition-all after:duration-500 hover:after:w-full"
				href="#contact"
				>Контакти
			</a>
		</nav>
	</menu>
</header>
