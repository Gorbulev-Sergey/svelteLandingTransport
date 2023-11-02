<script lang="ts">
	import ImageListBlock from '$lib/components/ImageListBlock.svelte';
</script>

<nav class="fixed-top bg-white bg-opacity-75 text-dark w-100" style="backdrop-filter: blur(1em)">
	<div
		class="d-flex justify-content-between align-items-center flex-wrap px-5 py-3"
		style="font-size:1.2em">
		<div class="flex-grow-1">+7 (985) 388-74-47</div>
		<div class="display-6 fw-bold">ООО "КЛЭВЭР ЛОГИСТИКС"</div>
		<div class="flex-grow-1 text-end">Время работы: Пн-Пт <br /> с 9:00 до 18:00</div>
	</div>
</nav>
<div class="my-main-block d-flex align-items-center">
	<div class="my-inside-block bg-white bg-opacity-10 text-light w-75">
		<div class="d-flex flex-column align-items-start justify-content-center">
			<h1 class="display-4 fw-bold">МЫ - КЛЭВЭР ЛОГИСТИКС</h1>
			<h3 class="text-light text-opacity-75 py-3">
				Логистическая компания, осуществляющая полный комплекс транспортно-экспедиторских услуг по
				международной доставке грузов.
			</h3>
			<div class="d-flex gap-3">
				<a
					href="#about"
					class="btn btn-light bg-light bg-opacity-25 text-light border-0 mt-3 rounded-1"
					>Кто мы?</a>
				<a
					href="#work"
					class="btn btn-light bg-light bg-opacity-25 text-light border-0 mt-3 rounded-1"
					>Чем мы занимаемся?</a>
				<a
					href="#map"
					class="btn btn-light bg-light bg-opacity-25 text-light border-0 mt-3 rounded-1"
					>Где мы находимся?</a>
			</div>
		</div>
	</div>
</div>

<div id="about" class="my-main-block d-flex">
	<div class="my-inside-block bg-white bg-opacity-50 text-dark w-100">
		<h2 class="mb-4">Кто мы?</h2>
		<div>
			<b>Г</b>оловной офис нашей компании располагается в городе Дубна.
		</div>
		<hr />
		<div>
			<b>Г</b>еография услуг компании охватывает страны Западной и Центральной Европы, Российскую
			Федерацию, Беларусь, Украину, Молдову, Казахстан, Узбекистан и другие страны СНГ.
		</div>
		<hr />
		<div>
			<b>Н</b>аш коллектив – хорошо организованная команда высококвалифицированных специалистов в
			области транспорта и логистики. Клиенты КЛЭВЭР ЛОГИСТИКС – это крупные международные концерны,
			средние и малые предприятия России и стран Европейского Союза.
		</div>
		<hr />
		<div>
			<b>М</b>ы гарантируем своим клиентам четкое выполнение условий договоров, стабильность,
			уважение и в обязательном порядке высокое качество.
		</div>
		<hr />
		<div>
			<b>К</b>омпания КЛЭВЭР ЛОГИСТИКС осуществляет международные автоперевозки с использованием
			наиболее оптимальных логистических схем.
		</div>
	</div>
</div>

<div id="work" class="my-main-block d-flex">
	<div class="my-inside-block gap-4 bg-white bg-opacity-50 text-dark w-100">
		<h2 class="mb-4">Чем мы звнимаемся?</h2>
		<ImageListBlock
			title="ПЕРЕВОЗКИ КОМПЛЕКТНЫХ ГРУЗОВ"
			image="https://cleverlogistics.ru/images/good_block_1.jpg" />
		<ImageListBlock
			title="ПЕРЕВОЗКИ СБОРНЫХ ГРУЗОВ"
			image="https://cleverlogistics.ru/images/good_block_2.jpg" />
		<ImageListBlock
			title="ПЕРЕВАЛКА И СКЛАДСКОЕ ХРАНЕНИЕ, КОНСОЛИДАЦИЯ ГРУЗОВ"
			image="https://cleverlogistics.ru/images/good_block_3.jpg" />
		<ImageListBlock
			title="CТРАХОВАНИЕ ГРУЗОВ"
			image="https://cleverlogistics.ru/images/good_block_4.jpg" />
		<ImageListBlock
			title="КОНТРОЛЬ КАЧЕСТВА, СЮРВЕЙЕРСКИЕ ОТЧЕТЫ"
			image="https://cleverlogistics.ru/images/good_block_5.jpg" />
		<ImageListBlock
			title="УСЛУГИ ПЕРЕОФОРМЛЕНИЯ И НЕЙТРАЛИЗАЦИИ"
			image="https://cleverlogistics.ru/images/good_block_6.jpg" />
		<ImageListBlock
			title="СЕРТИФИКАЦИЯ ФИТОСАНИТАРИИ И ВЕТЕРИНАРИИ"
			image="https://cleverlogistics.ru/images/good_block_7.jpg" />
		<ImageListBlock
			title="ЮРИДИЧЕСКАЯ ПОДДЕРЖКА И УРЕГУЛИРОВАНИЕ КОНФЛИКТНЫХ СИТУАЦИЙ ПРИ ПЕРЕВОЗКЕ ГРУЗОВ	В МЕЖДУНАРОДНОМ СООБЩЕНИИ"
			image="https://cleverlogistics.ru/images/good_block_8.jpg" />
		<ImageListBlock
			title="КОНСУЛЬТАЦИИ ПО ВОПРОСАМ	ЭКСПОРТНО-ИМПОРТНЫХ	ОПЕРАЦИЙ И ТАМОЖЕННЫХ ПРОЦЕДУР"
			image="https://cleverlogistics.ru/images/good_block_9.jpg" />
		<ImageListBlock
			title="КОМПЛЕКСНАЯ ЛОГИСТИКА ТРЕТЬЕЙ СТОРОНЫ (3PL)"
			image="https://cleverlogistics.ru/images/good_block_10.jpg" />
		<ImageListBlock
			title="СЕРТИФИКАЦИЯ/ДЕКЛАРАЦИЯ СООТВЕТСТВИЯ"
			image="https://cleverlogistics.ru/images/good_block_11.jpg" />
	</div>
</div>

<style>
	.my-main-block {
		min-height: 100vh;
		background: transparent;
		padding: 8em 4em 4em 4em;
	}

	.my-main-block > .my-inside-block {
		display: flex;
		flex-direction: column;
		justify-content: center;
		padding: 3em;
		backdrop-filter: blur(2em);
		border-radius: 0.35em;
	}
</style>
