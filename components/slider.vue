<!-- components/NewsCarousel.vue -->
<template>
  <div class="relative mt-3 py-2">
    <!-- Slider Container -->
    <div
      ref="slider"
      class="flex overflow-x-auto space-x-4"
      @scroll.passive="updateScrollPosition"
    >
      <!-- Loop through news items -->
      <div
        v-for="(news, index) in newsItems"
        :key="index"
        class="min-w-[320px] bg-white shadow-lg rounded-lg overflow-hidden"
      >
        <div>
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
            <a :href="news.link" class="hover:text-blue-800">
              {{ news.title }}
            </a>
          </h4>
        </div>
      </div>
    </div>

    <!-- Prev/Next Buttons -->
    <button
      v-if="canScrollLeft"
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
      v-if="canScrollRight"
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
import { ref, computed } from "vue";

const slider = ref(null);
const scrollPosition = ref(0);

const newsItems = [
  {
    title:
      "উলিপুরে বাংলাদেশ জাতীয় হিন্দু মহাজোটের সহযোগীতা, শারোদীয় দূর্গা উৎসব সম্পন্ন",
    link: "#",
    image:
      "https://royelnews.com/wp-content/uploads/2023/10/395711786_719079943577963_376892770646993724_n-1-600x337.jpg",
  },
  {
    title: "রাশিয়া ছেড়ে পালিয়েছেন সাবেক ওয়াগনার কমান্ডার",
    link: "#",
    image:
      "https://royelnews.com/wp-content/uploads/2023/01/3-Copy-639-700x390-1.jpg",
  },
  {
    title: "৬ দশকের মধ্যে সবচেয়ে কম জন্মহার চীনে!",
    link: "#",
    image:
      "https://royelnews.com/wp-content/uploads/2023/01/3-Copy-638-700x390-1.jpg",
  },
  {
    title: "দ্বিতীয় বিয়ে করেছেন দাউদ ইব্রাহিম, স্ত্রী পাকিস্তানি",
    link: "#",
    image:
      "https://royelnews.com/wp-content/uploads/2023/01/3-Copy-637-700x390-1.jpg",
  },
  {
    title: "রৌমারীতে আই,এফ,আই, সি, ব্যাংক উদ্বোধন",
    link: "#",
    image:
      "https://royelnews.com/wp-content/uploads/2022/12/322625132_719526586261443_2986189997021982751_n-600x337.jpg",
  },
  {
    title:
      "নাটোরের ভোক্তা-অধিকারের অভিযানে ২ হাজার কেজি গুড় জব্দ ও ২ লক্ষ টাকা জরিমানা",
    link: "#",
    image:
      "https://royelnews.com/wp-content/uploads/2022/12/received_478339027784806-600x337.jpeg",
  },
  {
    title: "শার্শার লাউতাড়ায় তথ্য আপার উঠান বৈঠক",
    link: "#",
    image:
      "https://royelnews.com/wp-content/uploads/2022/12/received_568067688499501-600x337.jpeg",
  },
  {
    title: "স্ত্রীর পরকীয়ার কারণে বিষ পানে বাবা ও দুই বছরের শিশুর মৃত্যু",
    link: "#",
    image:
      "https://royelnews.com/wp-content/uploads/2022/12/321949874_614676263797003_3781314040877330611_n.jpg",
  },
  {
    title: "নিয়ন্ত্রণ হারিয়ে গাছের সঙ্গে ধাক্কা, শালা-দুলাভাই নিহত",
    link: "#",
    image:
      "https://royelnews.com/wp-content/uploads/2022/12/322569738_561347029173132_1925919187688930683_n.jpg",
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

const updateScrollPosition = () => {
  scrollPosition.value = slider.value?.scrollLeft || 0;
};

const canScrollLeft = computed(() => scrollPosition.value > 0);
const canScrollRight = computed(() => {
  if (slider.value) {
    return (
      slider.value.scrollWidth > slider.value.clientWidth + scrollPosition.value
    );
  }
  return false;
});
</script>
