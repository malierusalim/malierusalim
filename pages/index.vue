<template>
  <div>
    <header class="bg-gray-800 selection:bg-red-400">
      <div class="lg:flex">
        <div
          class="flex items-center justify-center bg-gray-800 w-full px-6 py-8 lg:h-128 lg:min-h-[65vh] lg:w-1/2"
        >
          <div class="max-w-xl xl:max-w-2xl">
            <h2
              class="text-4xl font-bold leading-10 md:leading-none text-white sm:text-5xl lg:text-6xl xl:text-7xl"
            >
              <span class="text-red-600">Красная Нить</span><br />
              из&nbsp;Израиля,
            </h2>

            <p
              class="mt-2 text-3xl text-white leading-9 md:leading-9 lg:leading-none sm:mt-1 lg:mt-2 lg:text-4xl"
            >
              освящённая<br />
              на гробнице <span class="font-semibold">Рахели</span>
            </p>

            <div class="flex flex-col mt-8 space-y-3 lg:space-y-0 lg:flex-row">
              <a
                href="#map-wrap"
                class="inline-flex items-center justify-center px-6 py-3 border border-transparent text-base lg:text-lg font-semibold tracking-wider rounded-md text-white bg-red-700 hover:bg-red-500 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-red-700"
                >Где купить?</a
              >
            </div>
          </div>
        </div>

        <div class="w-full h-144 lg:w-1/2 lg:h-auto">
          <div
            class="w-full h-full bg-cover"
            style="background-image: url('/6.jpg')"
          >
            <div class="w-full h-full"></div>
          </div>
        </div>
      </div>
    </header>
    <div
      class="selection:bg-red-200 md:max-w-2xl lg:max-w-3xl xl:max-w-4xl mx-auto px-4 py-10 sm:px-6 lg:px-8 lg:py-20 prose lg:prose-xl"
    >
      <h2>
        Подлинная
        <span class="text-red-600">Красная Нить</span> из&nbsp;Израиля,
        освященная на&nbsp;гробнице Рахели
      </h2>
      <p>
        Та&nbsp;самая красная нить, которую носят звезды и&nbsp;политики.
        Сильнейший оберег, защищающий от&nbsp;сглаза и&nbsp;зависти, ненависти
        и&nbsp;негативной энергии. Нить повязывают маленьким детям во&nbsp;время
        болезни и&nbsp;чтобы защитить от&nbsp;&laquo;дурного глаза&raquo;. Также
        считается, что нить притягивает богатство и&nbsp;успех.
      </p>
      <p>
        Но&nbsp;не&nbsp;каждая Красная Нить обладает этими свойствами, даже если
        она привезена из&nbsp;Иерусалима и&nbsp;была взята у&nbsp;Стены Плача.
      </p>
      <p>
        Подлинную нить не&nbsp;купишь у&nbsp;торговцев сувенирами в&nbsp;старом
        городе и&nbsp;у&nbsp;Стены Плача. Там продают обычные
        сувениры&nbsp;&mdash; красные веревочки для туристов на&nbsp;память.
        Настоящие Красные Нити освящают согласно тысячелетней традиции, севернее
        Вифлеема, на&nbsp;гробнице Рахели, жены Яакова, праматери всего
        человечества. Это место с&nbsp;необычайно сильной энергетикой, святое
        для христиан, мусульман и&nbsp;иудеев.
      </p>
      <p>
        Для освящения шерстяную нить оборачивают вокруг гробницы Рахели.
        В&nbsp;процессе освящения читаются тегилим (псалтирь), а&nbsp;после нить
        делят на&nbsp;небольшие отрезки.
      </p>
      <h3>
        Как правильно повязать <span class="text-red-600">Красную нить</span>
      </h3>
      <p>
        Каждый год мы&nbsp;едем на&nbsp;святую землю и&nbsp;освящаем нити
        самостоятельно на&nbsp;гробнице Рахели. Поэтому мы&nbsp;гарантируем
        их&nbsp;подлинность.
      </p>
      <p>
        Красную нить носят на&nbsp;левой руке. Ее&nbsp;завязывают на&nbsp;семь
        узлов, сделать это должен близкий человек. В&nbsp;момент завязывания
        нужно читать молитву Бен Порат семь раз подряд, по&nbsp;одному разу
        на&nbsp;каждый узел.
      </p>
      <p>
        Тот, кому эта нить завязывается, должен направить свои мысли
        к&nbsp;добру и&nbsp;на&nbsp;то, от&nbsp;чего его сердце наполняется
        счастьем.
      </p>
      <p>
        Нить носят не&nbsp;снимая. С&nbsp;ней купаются и&nbsp;спят до&nbsp;тех
        пор, пока она сама не&nbsp;разорвется. Кто-то носит месяц, кто-то год.
        Все это время нить принимает на&nbsp;себя негатив.
      </p>
      <p>
        Если нить рвется, это считается благоприятным знаком, и&nbsp;означает,
        что она уже наполнилась негативом или приняла на&nbsp;себя сильный удар.
        Использованную нить можно сжечь или выкинуть. Красная нить&nbsp;&mdash;
        это достойный подарок для друзей и&nbsp;близких. Если вы&nbsp;дарите
        ее&nbsp;своим друзьям, взамен попросите символическую плату. Членам
        своей семьи повяжите сами, плату брать не&nbsp;надо.
      </p>
      <p>
        Чтобы заказать доставку нитей, задать вопрос или посмотреть видео
        освящения, зайдите в&nbsp;наш&nbsp;<a href="http://vk.com/malierusalim"
          >ВК</a
        >
        или <a href="http://instagram.com/malierusalim_sng">Инстаграмм</a>.
      </p>
    </div>
    <div id="map-wrap" class="h-144">
      <client-only>
        <l-map
          :zoom="17"
          :center="[45.19851841664501, 33.376339915874055]"
          :options="{ scrollWheelZoom: false, dragging: false }"
        >
          <l-tile-layer
            url="http://{s}.tile.osm.org/{z}/{x}/{y}.png"
          ></l-tile-layer>
          <l-marker :lat-lng="[45.19851841664501, 33.376339915874055]">
            <l-popup class="text-base"
              >г. Евпатория, ул. Просмушкиных, д. 34</l-popup
            >
          </l-marker>
        </l-map>
      </client-only>
    </div>
    <div class="h-24 flex items-center justify-center">
      <p class="text-base md:text-xl text-gray-500 font-medium">&copy;{{ getDate }}</p>
    </div>
  </div>
</template>

<script>
export default {
  computed: {
    getDate() {
      return new Date().getFullYear();
    },
  },
};
</script>

<style scoped>
.prose p {
  @apply text-gray-500 font-medium;
}

.prose a {
  @apply text-red-500 font-medium no-underline hover:text-red-700 border-b border-red-300 hover:border-red-500;
}

.prose h2,
.prose h3 {
  @apply text-gray-700 font-bold;
}
</style>
