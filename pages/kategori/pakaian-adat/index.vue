<template>
  <NuxtLayout>
    <HeroTarian></HeroTarian>
    <InfoCard></InfoCard>
    <section id="content1" class="relative py-14 lg:py-20">
      <div class="w-96 h-96 -left-48 top-56 blob"></div>
      <div
        class="flex flex-col-reverse md:flex-row md:gap-x-4 lg:gap-0 items-center justify-between w-full"
      >
        <p
          class="md:w-1/2 lg:px-0 pl-4 pr-3 lg:py-0 py-5 mx-auto text-sm md:text-left text-right lg:text-xl font-medium"
        >
          Selamat datang di dunia penuh warna dan keindahan, di mana setiap
          serat kain adalah kisah yang bercerita. Selamat datang di Indonesia,
          tempat di mana pakaian adat bukan hanya pakaian, tetapi karya seni
          yang mencerminkan keanekaragaman budaya dan keindahan tradisional yang
          tak terlupakan.Dari ujung Aceh hingga ke tanah Papua, setiap daerah di
          Indonesia memiliki pakaian adat yang memikat hati. Kain yang dihiasi
          dengan motif tradisional yang khas, warna yang mencolok, dan desain
          yang elegan, menjadikan setiap pakaian adat sebagai manifestasi
          kekayaan warisan budaya.
        </p>
        <img
          src="~/assets/images/categoriespage/pakaian-adat/image1.png"
          alt=""
          class="w-[70%] md:w-[50%] self-end lg:self-auto lg:w-auto hover:scale-105 transition-all duration-500 hover:shadow-2xl"
        />
      </div>
    </section>
    <section id="content2" class="relative py-10 lg:py-20 overflow-hidden">
      <div class="w-96 h-96 -right-36 top-56 blob"></div>
      <div
        class="flex flex-col md:flex-row md:gap-x-4 lg:gap-0 items-center justify-between w-full"
      >
        <img
          src="~/assets/images/categoriespage/pakaian-adat/image2.png"
          alt=""
          class="w-[70%] md:w-[50%] self-start lg:self-auto lg:w-auto hover:scale-105 transition-all duration-500 hover:shadow-2xl"
        />
        <p
          class="md:w-1/2 lg:px-0 pr-4 pl-3 lg:py-0 py-5 mx-auto text-sm md:text-left text-left lg:text-xl font-medium"
        >
          Keunikan pakaian adat Indonesia terletak pada setiap detailnya. Batik
          Jawa yang sarat makna filosofis, Songket dari Sumatera yang berkilau,
          Ulos Batak yang menghiasi dan merangkul, dan masih banyak lagi. Setiap
          motif, warna, dan material menceritakan sejarah panjang suku bangsa di
          Indonesia. Pakaian adat bukan hanya busana; mereka adalah pewaris
          budaya dan penjaga tradisi. Dari upacara pernikahan hingga upacara
          adat, pakaian adat menjadi simbol kesatuan, kehormatan, dan identitas
          suku bangsa.
        </p>
      </div>
    </section>
    <section id="carousel-category" class="relative mt-10 mb-20">
      <div class="w-96 h-96 -left-36 top-36 blob"></div>
      <CarouselCategories now="Pakaian Adat"></CarouselCategories>
    </section>
    <section id="game-card" class="mb-20 px-5 lg:px-0">
      <GameCard></GameCard>
    </section>
  </NuxtLayout>
</template>

<script>
import HeroTarian from "~/components/categories/pakaian-adat/Hero.vue"
import InfoCard from "~/components/categories/pakaian-adat/InfoCard.vue"
import CarouselCategories from "~/components/categories/pakaian-adat/CarouselCategories.vue"

export default {
  components: { HeroTarian, InfoCard, CarouselCategories },
}
</script>

<style></style>
