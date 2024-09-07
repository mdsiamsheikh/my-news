<!-- components/NewsCarousel.vue -->
<template>
  <div class="relative mt-3 py-2">
    <!-- Slider Container -->
    <div
      ref="slider"
      class="slider_container flex overflow-x-auto space-x-4 scroll-smooth"
    >
      <!-- Loop through news items -->
      <div
        v-for="(news, index) in newsItems"
        :key="index"
        class="news_card bg-white shadow-lg rounded-lg overflow-hidden w-80"
      >
        <div class="news_image">
          <a :href="news.link" target="_blank">
            <img
              :src="news.image"
              :alt="news.title"
              class="w-full h-auto object-cover"
            />
          </a>
        </div>
        <div class="p-4">
          <h4 class="text-[16px] font-semibold text-gray-600">
            <a :href="news.link" class="hover:text-blue-800">{{
              news.title
            }}</a>
          </h4>
        </div>
      </div>
    </div>

    <!-- Prev/Next Buttons -->
    <button
      @click="scroll(-300)"
      class="absolute top-1/2 left-0 transform -translate-y-1/2 bg-gray-800 text-white p-2 rounded-full hover:bg-gray-600"
    >
      <svg
        class="w-6 h-6"
        fill="none"
        stroke="currentColor"
        viewBox="0 0 24 24"
      >
        <path
          stroke-linecap="round"
          stroke-linejoin="round"
          stroke-width="2"
          d="M15 19l-7-7 7-7"
        />
      </svg>
    </button>
    <button
      @click="scroll(300)"
      class="absolute top-1/2 right-0 transform -translate-y-1/2 bg-gray-800 text-white p-2 rounded-full hover:bg-gray-600"
    >
      <svg
        class="w-6 h-6"
        fill="none"
        stroke="currentColor"
        viewBox="0 0 24 24"
      >
        <path
          stroke-linecap="round"
          stroke-linejoin="round"
          stroke-width="2"
          d="M9 5l7 7-7 7"
        />
      </svg>
    </button>
  </div>
</template>

<script setup>
import { ref } from "vue";

const slider = ref(null);

const newsItems = [
  {
    link: "https://royelnews.com/link1",
    image:
      "https://royelnews.com/wp-content/uploads/2023/10/395711786_719079943577963_376892770646993724_n-1-600x337.jpg",
    title:
      "উলিপুরে বাংলাদেশ জাতীয় হিন্দু মহাজোটের সহযোগীতা, শারোদীয় দূর্গা উৎসব সম্পন্ন।",
  },
  {
    link: "https://royelnews.com/link2",
    image:
      "https://royelnews.com/wp-content/uploads/2023/09/prothomalo-bangla_2021-11_8f79a823-5cec-48db-a67b-ef98317af490_P_1-600x337.webp",
    title: "ফ্রান্সের প্রেসিডেন্ট আসছেন আজ, যা নিয়ে আলোচনা হতে পারে",
  },
  {
    link: "https://royelnews.com/link2",
    image:
      "https://royelnews.com/wp-content/uploads/2023/01/5-4-700x390-1.jpeg",
    title: "জাপানে দুই সপ্তাহে ৫ হাজার করোনা রোগীর মৃত্যু",
  },
  {
    link: "https://royelnews.com/link2",
    image:
      "https://royelnews.com/wp-content/uploads/2023/01/3-Copy-640-700x390-1.jpg",
    title: "ইতালির কিংবদন্তি অভিনেত্রী জিনা লল্লব্রিজিদা আর নেই",
  },
  {
    link: "https://royelnews.com/link2",
    image:
      "https://royelnews.com/wp-content/uploads/2023/01/3-Copy-639-700x390-1.jpg",
    title: "৬ দশকের মধ্যে সবচেয়ে কম জন্মহার চীনে!",
  },
  {
    link: "https://royelnews.com/link2",
    image:
      "https://royelnews.com/wp-content/uploads/2023/01/3-Copy-637-700x390-1.jpg",
    title: "দ্বিতীয় বিয়ে করেছেন দাউদ ইব্রাহিম, স্ত্রী পাকিস্তানি’",
  },
  {
    link: "https://royelnews.com/link2",
    image: "https://royelnews.com/wp-content/uploads/2023/01/64-600x337.png",
    title: "ছুটিতে থাকা সহকর্মীকে বিরক্ত করলেই জরিমানা ১ লাখ রুপি",
  },
  {
    link: "https://royelnews.com/link2",
    image:
      "https://royelnews.com/wp-content/uploads/2023/01/3-Copy-479-700x390-1-600x337.jpg",
    title: "ন্যাটোর অনুচরে পরিণত হচ্ছে ইউরোপীয় ইউনিয়ন: রাশিয়া",
  },
  {
    link: "https://royelnews.com/link2",
    image:
      "https://royelnews.com/wp-content/uploads/2023/01/3-Copy-330-700x390-1-600x337.jpg",
    title: "রাত ৮টায় দোকান বন্ধ নিয়ে পাকিস্তানের মন্ত্রীর অদ্ভুত মন্তব্য",
  },
];

const scroll = (amount) => {
  if (slider.value) {
    slider.value.scrollBy({
      left: amount,
      behavior: "smooth",
    });
  }
};
</script>

<style scoped>
.slider_container {
  scroll-snap-type: x mandatory;
}

.news_card {
  scroll-snap-align: start;
  min-width: 320px;
}

button {
  cursor: pointer;
}
</style>
