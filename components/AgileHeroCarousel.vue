<template>
  <div>
    <client-only placeholder="Loading...">
      <agile :autoplay="true" :autoplaySpeed="5000">
        <section class="slide bg-slide1 relative  animation-style-01">
          <div
            class="container mx-auto px-24 py-0 flex md:flex-row flex-col items-center HeroAnimation"
          >
            <div
              class="lg:flex-grow md:w-1/2 lg:pr-24 md:pr-16 flex flex-col md:items-start md:text-left mb-16 md:mb-0 items-center text-center LeftDivAnimation"
            >
              <h1
                class="text-white font-bold uppercase TitelAnimation"
              >
                SEO оптимизация
              </h1>
              <h2 class="text-white font-normal lowercase SubtitleAnimation">на этапе разработки</h2>
              <p class="text-white text-animation">
                Полный спектр работ по SEO оптимизации веб-сайтов, интернет-магазинов, корпоративных порталов и ресурсов интернет СМИ. Оптимизация заголовков, текстов, мета тегов, изображений и мультимедиа объектов, коррекция и исправление ссылочного ранжирования веб-ресурса.
              </p>
              <div class="flex justify-center">
                <button
                  class="btn"
                >
                  заказать услугу
                </button>
                <button
                  class="btn-secondary"
                >
                  задать вопрос
                </button>
              </div>
            </div>
            <div class="lg:max-w-lg lg:w-full md:w-1/2 w-5/6 RightsDivAnimation">
              <img
                class="object-cover object-center rounded"
                alt="hero"
                src="~/assets/images/Picture1.png"
              />
            </div>
            </div>
        </section>

        <!-- Slade 2 -->
        <section class="slide bg-slide2 relative  animation-style-01">
          <div
            class="container mx-auto px-24 py-0 flex md:flex-row flex-col items-center HeroAnimation"
          >
            <div
              class="lg:flex-grow md:w-1/2 lg:pr-24 md:pr-16 flex flex-col md:items-start md:text-left mb-16 md:mb-0 items-center text-center LeftDivAnimation"
            >
              <h1
                class="color-basic font-bold uppercase TitelAnimation"
              >
                SEO оптимизация
              </h1>
              <h2 class="color-basic font-normal lowercase SubtitleAnimation">на этапе разработки</h2>
              <p class="text-color-basic text-animation">
                Полный спектр работ по SEO оптимизации веб-сайтов, интернет-магазинов, корпоративных порталов и ресурсов интернет СМИ. Оптимизация заголовков, текстов, мета тегов, изображений и мультимедиа объектов, коррекция и исправление ссылочного ранжирования веб-ресурса.
              </p>
              <div class="flex justify-center">
                <button
                  class="btn"
                >
                  <span class="color-basic">заказать услугу</span>
                </button>
                <button
                  class="btn-secondary-2"
                >
                  задать вопрос
                </button>
              </div>
            </div>
            <div class="lg:max-w-lg lg:w-full md:w-1/2 w-5/6 RightsDivAnimation">
              <img
                class="object-cover object-center rounded"
                alt="hero"
                src="~/assets/images/Picture2.png"
              />
            </div>
            </div>
        </section>

        <!-- Slade 3 -->
        <section class="slide bg-slide3 relative   animation-style-01">
          <div
            class="container mx-auto px-24 py-0  flex  items-center HeroAnimation"
          >
            <div
              class="lg:flex-grow md:w-1/2 lg:pr-24 md:pr-16 flex flex-col md:items-start md:text-left mb-16 md:mb-0 items-center text-center LeftDivAnimation"
            >
              <h1
                class="text-white font-bold uppercase TitelAnimation"
              >
                SEO продвижение
              </h1>
              <h2 class="text-white font-normal lowercase SubtitleAnimation">лидирование вашего сайта</h2>
              <p class="text-white text-animation">
                Полный спектр работ по SEO оптимизации веб-сайтов, интернет-магазинов, корпоративных порталов и ресурсов интернет СМИ. Оптимизация заголовков, текстов, мета тегов, изображений и мультимедиа объектов, коррекция и исправление ссылочного ранжирования веб-ресурса.
              </p>
              <div class="flex justify-center">
                <button
                  class="btn"
                >
                  заказать услугу
                </button>
                <button
                  class="btn-secondary"
                >
                  задать вопрос
                </button>
              </div>
            </div>
            <div class="lg:max-w-lg lg:w-full md:w-1/2 w-5/6 RightsDivAnimation">
              <img
                class="object-cover object-center rounded"
                alt="hero"
                src="~/assets/images/Picture3.png"
              />
            </div>
          </div>
        </section>
         <!-- Button PREV and NEXT -->
            <template slot="prevButton">
              <button class="prev">&#10094;</button>
            </template>
            <template slot="nextButton">
              <button class="next">&#10095;</button>
            </template>
      </agile>
    </client-only>
  </div>
</template>

<script>
export default {};
</script>

<style>
.slide {
  font-family: Roboto;
}
.bg-slide1 {
  width: 100%;
  background: #2c97dd;
}
.bg-slide2 {
  background: #5fb6ee;
}
.bg-slide3 {
  background: #0e5d90;
}
.slide h1,
.slide h2 {
  font-size: 48px;
  font-style: normal;
  line-height: 56px;
  letter-spacing: 2px;
}
.slide p {
  font-size: 15px;
  line-height: 25px;
  letter-spacing: 2px;
  padding-top: 38px;
  padding-bottom: 30px;
}

.btn {
  font-family: Montserrat;
  font-style: normal;
  font-weight: 500;
  font-size: 18px;
  line-height: 22px;
  /* identical to box height */
  text-transform: uppercase;
  color: #2c97dd;
  padding: 10px 20px;
  background: #ffffff;
  margin-right: 25px;
}
.btn-secondary {
  border: 1px solid #ffffff;
  box-sizing: border-box;
  font-family: Montserrat;
  font-style: normal;
  font-weight: 500;
  font-size: 18px;
  line-height: 22px;
  /* identical to box height */
  text-transform: uppercase;
  color: #ffffff;
  padding: 10px 20px;
}

.btn-secondary-2 {
  border: 1px solid #0e5d90;
  box-sizing: border-box;
  font-family: Montserrat;
  font-style: normal;
  font-weight: 500;
  font-size: 18px;
  line-height: 22px;
  /* identical to box height */
  text-transform: uppercase;
  color: #0e5d90;
  padding: 10px 20px;
}

/* Next & previous buttons */
.prev,
.next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  width: auto;
  margin-top: -22px;
  padding: 16px;
  color: #ffffff;
  font-weight: bold;
  font-size: 24px;
  transition: 0.6s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;
  z-index: 15;
  opacity: 0;
}
.agile:hover .agile__actions .agile__nav-button .prev,
.agile:hover .agile__actions .agile__nav-button .next {
  opacity: 1;
}
/* Position the "next button" to the right */
.next {
  right: 0;
  border-radius: 3px 0 0 3px;
}
/* On hover, add a black background color with a little bit see-through */
.prev:hover,
.next:hover {
  background-color: #0e5c90ca;
}
/*  */

/* Animation */
.swiper-slide-active .HeroAnimation .LeftDivAnimation > :nth-child(4) {
  animation-delay: 1.8s;
}
.animation-style-01.agile__slide--active
  .HeroAnimation
  .LeftDivAnimation
  .TitelAnimation {
  animation-name: fadeInUp;
  animation-delay: 0.5s;
  animation-duration: 1s;
  animation-fill-mode: both;
}
.animation-style-01.agile__slide--active
  .HeroAnimation
  .LeftDivAnimation
  .SubtitleAnimation {
  animation-name: fadeInUp;
  animation-delay: 1s;
  animation-duration: 1s;
  animation-fill-mode: both;
}
.animation-style-01.agile__slide--active .HeroAnimation .LeftDivAnimation .btn {
  animation-name: fadeInUp;
  animation-delay: 2s;
  animation-duration: 1s;
  animation-fill-mode: both;
}
.animation-style-01.agile__slide--active
  .HeroAnimation
  .LeftDivAnimation
  .btn-secondary {
  animation-name: fadeInUp;
  animation-delay: 2.5s;
  animation-duration: 1s;
  animation-fill-mode: both;
}
.animation-style-01.agile__slide--active
  .HeroAnimation
  .LeftDivAnimation
  .btn-secondary-2 {
  animation-name: fadeInUp;
  animation-delay: 2.5s;
  animation-duration: 1s;
  animation-fill-mode: both;
}
.animation-style-01.agile__slide--active .text-animation {
  animation-name: fadeInUp;
  animation-delay: 1.5s;
  animation-duration: 1s;
  animation-fill-mode: both;
}
.animation-style-01.agile__slide--active
  .HeroAnimation
  .RightsDivAnimation
  img {
  animation-name: zoomIn;
  animation-delay: 1s;
  animation-duration: 1s;
  animation-fill-mode: both;
}
.agile__slide .HeroAnimation .LeftDivAnimation,
.agile__slide .text-animation {
  opacity: 0;
}
.agile__slide.agile__slide--active .HeroAnimation .LeftDivAnimation,
.agile__slide.agile__slide--active .text-animation {
  opacity: 1;
}
.agile__slide .HeroAnimation .LeftDivAnimation .subtitle-animation {
  opacity: 0;
}
.agile__slide.agile__slide--active
  .HeroAnimation
  .LeftDivAnimation
  .subtitle-animation {
  opacity: 1;
}
.agile__slide--active .HeroAnimation > :nth-child(4) {
  animation-delay: 1.8s;
}
.agile__slide .HeroAnimation .RightsDivAnimation img {
  opacity: 0;
}
.agile__slide.agile__slide--active .HeroAnimation .RightsDivAnimation img {
  opacity: 1;
}
/* //Animation */
</style>
