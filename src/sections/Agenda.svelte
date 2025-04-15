<script>
	import velikoTurnovoCat from '../img/veliko-turnovo-cat.svg';
	import unconferencePresent from '../img/unconference-present.svg';
</script>

<section id="event" class="py-20">
	<div class="container mx-auto flex flex-col items-center px-16 lg:flex-row">
		<div class="lg:w-1/2">
			<div class="lg:pr-32 xl:pr-32">
				<h3 class="text-3xl leading-tight font-semibold">🎤 15-минутни представяния</h3>
				<p class="mt-8 text-xl leading-relaxed font-light">
					Точно толкова, колкото да споделиш идея, да запалиш интерес и да не изгубиш публиката по
					пътя. Без скука, без излишни слайдове – само смисъл, енергия и малко време за въпроси.
				</p>
			</div>
		</div>
		<div class="undefined mt-10 w-full lg:mt-0 lg:w-1/2">
			<img src={unconferencePresent} alt="Презентация на unconference" />
		</div>
	</div>
</section>

<section class="py-20">
	<div class="container mx-auto flex flex-col items-center px-16 lg:flex-row">
		<div class="lg:w-1/2">
			<div class="lg:pl-32 xl:pl-32">
				<h3 class="text-3xl leading-tight font-semibold">
					🌳 Локация: парк Ксилифор, Велико Търново
				</h3>
				<p class="mt-8 text-xl leading-relaxed font-light">
					В непосредствена близост до старопрестолната столица Велико Търново. На чист въздух и
					далеч от шумния град в парк Ксилифор. Едно приказно място с възможност за разходки и
					интересни дискусии.
				</p>
			</div>
		</div>
		<div class="order-last mt-10 w-full lg:order-first lg:mt-0 lg:w-1/2">
			<img src={velikoTurnovoCat} alt="Велико Търново" />
		</div>
	</div>
</section>
