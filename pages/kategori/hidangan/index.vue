<template>
  <NuxtLayout>
    <HeroHidangan></HeroHidangan>
    <InfoCard></InfoCard>
    <section id="content1" class="relative py-14 lg:py-20">
      <div class="w-96 h-96 -left-48 top-56 blob"></div>
      <div
        class="flex flex-col-reverse md:flex-row md:gap-x-4 lg:gap-0 items-center justify-between w-full"
      >
        <p
          class="md:w-1/2 lg:px-0 pl-4 pr-3 lg:py-0 py-5 mx-auto text-sm md:text-left text-right lg:text-xl font-medium"
        >
          Apa yang dimakan orang Indonesia? Seberapa penting makanan dalam
          tradisi Indonesia? Dari barat ke timur Indonesia, kita akan menemukan
          banyak kebiasaan makan yang unik. Ada 5000 resep tradisional yang
          tersebar di seluruh kepulauan Indonesia. Di dalam belahan bumi yang
          kaya akan keindahan alam dan keberagaman budaya, Indonesia
          menghadirkan pengalaman kuliner yang menggugah selera. Setiap daerah,
          suku, dan pulau menyajikan beragam hidangan tradisional, menciptakan
          perpaduan unik cita rasa yang memanjakan lidah Anda. Dari pesisir
          hingga pegunungan, nikmati sentuhan lezat dari masakan lokal yang kaya
          akan rempah-rempah alami. Setiap gigitan adalah perjalanan melintasi
          keanekaragaman bumbu dan teknik memasak yang telah diwariskan dari
          generasi ke generasi.
        </p>
        <img
          src="~/assets/images/categoriespage/hidangan/image1.png"
          alt=""
          class="w-[70%] md:w-[50%] self-end lg:self-auto lg:w-auto hover:scale-105 transition-all duration-500 hover:shadow-2xl"
        />
      </div>
    </section>
    <section id="content2" class="relative py-10 lg:py-20 overflow-hidden">
      <div class="w-96 h-96 -right-36 top-56 blob"></div>
      <div
        class="flex flex-col md:flex-row items-center justify-between w-full"
      >
        <img
          src="~/assets/images/categoriespage/hidangan/image2.png"
          alt=""
          class="w-[70%] md:w-[50%] self-start lg:self-auto lg:w-auto hover:scale-105 transition-all duration-500 hover:shadow-2xl"
        />
        <p
          class="md:w-1/2 lg:px-0 pr-4 pl-3 lg:py-0 py-5 mx-auto text-sm md:text-left text-left lg:text-xl font-medium"
        >
          Cerita-cerita dalam Indonesia Food Culture dibuat dari keragaman
          budaya, warisan, upacara ritual, dan hasil lokal di setiap wilayah.
          Indonesia memiliki makanan umum yang dapat ditemukan di sebagian besar
          wilayah, seperti Sambal (pasta cabai) dan Soto (Sup Indonesia). Ada
          lebih dari 100 jenis Sambal dan 70 jenis Soto di Indonesia. Proses
          memasak adalah cerita lain yang mungkin menarik untuk dijelajahi.
          Temukan kelezatan soto dari berbagai penjuru negeri, memadukan daging
          dengan bumbu khas setiap daerah. Kesenangan makan bersama sate
          menciptakan momen kebersamaan yang tak terlupakan di setiap sudut
          Indonesia.
        </p>
      </div>
    </section>
    <section id="carousel-category" class="relative mt-10 mb-20">
      <div class="w-96 h-96 -left-36 top-36 blob"></div>
      <CarouselCategories now="hidangan"></CarouselCategories>
    </section>
    <section id="game-card" class="mb-20 px-5 lg:px-0">
      <GameCard></GameCard>
    </section>
  </NuxtLayout>
</template>

<script>
import HeroHidangan from "~/components/categories/hidangan/Hero.vue"
import InfoCard from "~/components/categories/hidangan/InfoCard.vue"
import CarouselCategories from "~/components/categories/hidangan/CarouselCategories.vue"

export default {
  components: { HeroHidangan, InfoCard, CarouselCategories },
}
</script>

<style></style>
