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
      "https://royelnews.com/wp-content/uploads/2024/05/IMG-20240503-WA0011-600x337.jpg",
    title: "রাজশাহীতে বিশ্ব মুক্ত গণমাধ্যম দিবস পালন",
  },
  {
    link: "https://royelnews.com/link2",
    image:
      "https://royelnews.com/wp-content/uploads/2024/05/IMG-20240501-WA0038-600x337.jpg",
    title:
      "রাজশাহীতে জাতীয় দৈনিক মানবিক বাংলাদেশ পত্রিকার প্রতিষ্ঠা বার্ষিকী পালন",
  },
  {
    link: "https://royelnews.com/link2",
    image:
      "https://royelnews.com/wp-content/uploads/2023/10/395711786_719079943577963_376892770646993724_n-1-600x337.jpg",
    title:
      "উলিপুরে বাংলাদেশ জাতীয় হিন্দু মহাজোটের সহযোগীতা, শারোদীয় দূর্গা উৎসব সম্পন্ন।",
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
    image:
      "https://royelnews.com/wp-content/uploads/2023/01/8d46acaac5d4ea49698575b138b101ed-1-600x337.jpg",
    title: "পরীমনির মামলার কার্যক্রম ৬ মাস স্থগিত",
  },
  {
    link: "https://royelnews.com/link2",
    image:
      "https://royelnews.com/wp-content/uploads/2023/01/3-Copy-216-700x390-1-600x337.jpg",
    title: "হঠাৎ কেন বৃন্দাবনে বিরাট-আনুশকা? ভিডিও ভাইরাল",
  },
  {
    link: "https://royelnews.com/link2",
    image:
      "https://royelnews.com/wp-content/uploads/2023/01/resize-350x230x0x0-image-206026-1672902664.jpg",
    title: "তবে কি একসঙ্গেই থাকছেন রাজ-পরী!",
  },
  // Add more news items here...
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
