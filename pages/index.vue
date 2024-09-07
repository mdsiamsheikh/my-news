<template>
  <div>
    <div class="flex items-center justify-between p-4">
      <div class="w-1/4">
        <a href="">
          <img
            src="https://royelnews.com/wp-content/uploads/2022/12/277830472_318193127061596_4636589903513880359_n-1.png"
            alt="Logo"
            class="w-full"
          />
        </a>
      </div>
      <div class="w-3/4 flex justify-end">
        <a href="" target="_blank">
          <img
            src="https://royelnews.com/wp-content/uploads/2024/04/UntiegfuayugJDSgauri84yhtiewtr7wuk950-265rwaifioet7r8.jpg"
            alt="Banner"
            class="w-full"
          />
        </a>
      </div>
    </div>

    <!-------menu option stsrt-------->

    <div class="flex flex-col mx-w-[1099px] m-auto">
      <nav class="bg-[#d60909] shadow">
        <div class="max-w-7xl mx-auto px-2 sm:px-6 lg:px-6">
          <div class="flex justify-between h-[50px]">
            <div class="flex items-center">
              <button
                class="text-gray-500 hover:text-gray-700 focus:outline-none focus:text-gray-700 sm:hidden"
                aria-label="Toggle navigation"
              >
                <svg
                  class="h-6 w-6"
                  stroke="currentColor"
                  fill="none"
                  viewBox="0 0 24 24"
                >
                  <path
                    class="inline-flex"
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M4 6h16M4 12h16M4 18h16"
                  />
                </svg>
              </button>
              <div class="hidden sm:flex space-x-3 text-[14px]">
                <a
                  href="https://royelnews.com/"
                  class="text-white hover:text-white bg-[#73337D] inline-flex items-center px-1 pt-1 border-b-2 text-sm font-medium"
                  title="প্রচ্ছদ"
                  >প্রচ্ছদ</a
                >
                <div id="menu-item-82" class="relative group">
                  <a
                    title="সারাদেশ"
                    href="#"
                    class="flex py-2 px-3 text-white hover:text-white hover:bg-[#9A1515]"
                  >
                    সারাদেশ
                    <svg
                      class="ml-2 h-5 w-5"
                      xmlns="http://www.w3.org/2000/svg"
                      viewBox="0 0 20 20"
                      fill="currentColor"
                      aria-hidden="true"
                    >
                      <path
                        fill-rule="evenodd"
                        d="M5.23 7.21a.75.75 0 011.06.02L10 10.77l3.71-3.54a.75.75 0 111.04 1.08l-4.25 4a.75.75 0 01-1.04 0l-4.25-4a.75.75 0 01-.02-1.06z"
                        clip-rule="evenodd"
                      /></svg
                    ><span class="caret"></span>
                  </a>

                  <!-- Dropdown Menu -->
                  <div
                    class="absolute left-0 hidden bg-[#9A1515] w-[190px] group-hover:block"
                  >
                    <div class="menu-item">
                      <a
                        title="ঢাকা"
                        href=""
                        class="block py-2 px-4 text-white hover:text-gray-800 hover:bg-[#DCDCDC]"
                      >
                        ঢাকা
                      </a>
                    </div>
                    <div class="menu-item">
                      <a
                        title="রংপুর"
                        href=""
                        class="block py-2 px-4 text-white hover:text-gray-800 hover:bg-[#DCDCDC]"
                      >
                        রংপুর
                      </a>
                    </div>
                    <div class="menu-item">
                      <a
                        title="চট্রগ্রাম"
                        href=""
                        class="block py-2 px-4 text-white hover:text-gray-800 hover:bg-[#DCDCDC]"
                      >
                        চট্রগ্রাম
                      </a>
                    </div>
                    <div class="menu-item">
                      <a
                        title="রাজশাহী"
                        href=""
                        class="block py-2 px-4 text-white hover:text-gray-800 hover:bg-[#DCDCDC]"
                      >
                        রাজশাহী
                      </a>
                    </div>
                    <div class="menu-item">
                      <a
                        title="সিলেট"
                        href=""
                        class="block py-2 px-4 text-white hover:text-gray-800 hover:bg-[#DCDCDC]"
                      >
                        সিলেট
                      </a>
                    </div>
                    <div class="menu-item">
                      <a
                        title="ময়মনসিংহ"
                        href=""
                        class="block py-2 px-4 text-white hover:text-gray-800 hover:bg-[#DCDCDC]"
                      >
                        ময়মনসিংহ
                      </a>
                    </div>
                    <div class="menu-item">
                      <a
                        title="বরিশাল"
                        href=""
                        class="block py-2 px-4 text-white hover:text-gray-800 hover:bg-[#DCDCDC]"
                      >
                        বরিশাল
                      </a>
                    </div>
                    <div class="menu-item">
                      <a
                        title="খুলনা"
                        href=""
                        class="block py-2 px-4 text-white hover:text-gray-800 hover:bg-[#DCDCDC]"
                      >
                        খুলনা
                      </a>
                    </div>
                  </div>
                </div>
                <a
                  href=""
                  class="text-white hover:text-white hover:bg-[#9A1515] inline-flex items-center px-1 pt-1 text-sm font-medium"
                  title="জাতীয়"
                  >জাতীয়</a
                >
                <a
                  href=""
                  class="text-white hover:text-white hover:bg-[#9A1515] inline-flex items-center px-1 pt-1 text-sm font-medium"
                  title="রাজনীতি"
                  >রাজনীতি</a
                >
                <a
                  href=""
                  class="text-white hover:text-white hover:bg-[#9A1515] inline-flex items-center px-1 pt-1 text-sm font-medium"
                  title="অর্থ ও বাণিজ্য"
                  >অর্থ ও বাণিজ্য</a
                >
                <a
                  href=""
                  class="text-white hover:text-white hover:bg-[#9A1515] inline-flex items-center px-1 pt-1 text-sm font-medium"
                  title="অর্থনীতি"
                  >আর্ন্তজাতিক</a
                >
                <a
                  href=""
                  class="text-white hover:text-white hover:bg-[#9A1515] inline-flex items-center px-1 pt-1 text-sm font-medium"
                  title="চাকরি"
                  >চাকরি</a
                >
                <a
                  href=""
                  class="text-white hover:text-white hover:bg-[#9A1515] inline-flex items-center px-1 pt-1 text-sm font-medium"
                  title="বিনোদন"
                  >বিনোদন</a
                >
                <a
                  href=""
                  class="text-white hover:text-white hover:bg-[#9A1515] inline-flex items-center px-1 pt-1 text-sm font-medium"
                  title="শিক্ষা"
                  >শিক্ষা</a
                >
                <a
                  href=""
                  class="inline-flex items-center px-1 pt-1 text-sm font-medium text-white hover:text-white hover:bg-[#9A1515]"
                  title="শিল্প ও সাহিত্য"
                  >শিল্প ও সাহিত্য</a
                >

                <!-- Parent Menu Item -->
                <div id="menu-item-82" class="relative group">
                  <a
                    title="অন্যান্য"
                    href="#"
                    class="flex py-2 px-4 text-white hover:text-white hover:bg-[#9A1515]"
                  >
                    অন্যান্য
                    <svg
                      class="ml-2 h-5 w-5"
                      xmlns="http://www.w3.org/2000/svg"
                      viewBox="0 0 20 20"
                      fill="currentColor"
                      aria-hidden="true"
                    >
                      <path
                        fill-rule="evenodd"
                        d="M5.23 7.21a.75.75 0 011.06.02L10 10.77l3.71-3.54a.75.75 0 111.04 1.08l-4.25 4a.75.75 0 01-1.04 0l-4.25-4a.75.75 0 01-.02-1.06z"
                        clip-rule="evenodd"
                      /></svg
                    ><span class="caret"></span>
                  </a>

                  <!-- Dropdown Menu -->
                  <div
                    class="absolute left-0 hidden bg-[#9A1515] w-[170px] group-hover:block"
                  >
                    <div class="menu-item">
                      <a
                        title="কৃষি"
                        href=""
                        class="block py-2 px-4 text-white hover:text-gray-800 hover:bg-[#DCDCDC]"
                      >
                        কৃষি
                      </a>
                    </div>
                    <div class="menu-item">
                      <a
                        title="ধর্ম"
                        href=""
                        class="block py-2 px-4 text-white hover:text-gray-800 hover:bg-[#DCDCDC]"
                      >
                        ধর্ম
                      </a>
                    </div>
                    <div class="menu-item">
                      <a
                        title="ভ্রমণ"
                        href=""
                        class="block py-2 px-4 text-white hover:text-gray-800 hover:bg-[#DCDCDC]"
                      >
                        ভ্রমণ
                      </a>
                    </div>
                    <div class="menu-item">
                      <a
                        title="লাইফস্টাইল"
                        href=""
                        class="block py-2 px-4 text-white hover:text-gray-800 hover:bg-[#DCDCDC]"
                      >
                        লাইফস্টাইল
                      </a>
                    </div>
                    <div class="menu-item">
                      <a
                        title="সম্পাদকীয়"
                        href=""
                        class="block py-2 px-4 text-white hover:text-gray-800 hover:bg-[#DCDCDC]"
                      >
                        সম্পাদকীয়
                      </a>
                    </div>
                    <div class="menu-item">
                      <a
                        title="স্বাস্থ্য ও চিকিৎসা"
                        href=""
                        class="block py-2 px-4 text-white hover:text-gray-800 hover:bg-[#DCDCDC]"
                      >
                        স্বাস্থ্য ও চিকিৎসা
                      </a>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </nav>
    </div>
    <div class="flex flex-col w-full mt-3">
      <div class="w-full">
        <div class="flex flex-row">
          <div class="w-1/6 md:w-1/7 px-2 py-2 bg-[#3A3698] text-white">
            <span class="font-[400]">শিরোনাম:</span>
          </div>
          <div class="w-5/6 md:w-11/12 px-2 py-2 bg-[#F1F7FB]">
            <marquee
              direction="left"
              scrollamount="4"
              onmouseover="this.stop()"
              onmouseout="this.start()"
              class="flex items-center"
            >
              <!-- <div aria-hidden="true" class="flex text-center mx-3">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 448 512"
                  class="w-5"
                >
                  <path
                    fill="#d30d0d"
                    d="M0 96C0 60.7 28.7 32 64 32H384c35.3 0 64 28.7 64 64V416c0 35.3-28.7 64-64 64H64c-35.3 0-64-28.7-64-64V96z"
                  />
                </svg>
              </div> -->
              <a href="" class="text-black text-[16px]"
                >কুড়িগ্রামে বৈষম্য বিরোধী ছাত্র আন্দোলনে আহত আশিক চিকিৎসাধীন
                অবস্থায় ঢাকায় মারা গেছে</a
              >

              <a href="" class="text-black text-[16px]"
                >নগরীতে প্রতারণার জেরে কথিত সাংবাদিক চপলকে চড়-থাপ্পড়, ছড়াচ্ছে
                অপপ্রচার</a
              >

              <a href="" class="text-black text-[16px]"
                >নাগরিক সনদ অনুযায়ী সেবা প্রদান, প্রোপাগাণ্ডা ছড়ানোর অভিযোগ</a
              >

              <a href="" class="text-black text-[16px]"
                >প্রতিশোধ নয় দেশকে নতুন ভাবে গড়তে চাই জামায়াতে ইসলামী</a
              >

              <a href="" class="text-black text-[16px]"
                >রৌমারীতে যুব অধিকার পরিষদের ৪র্থ প্রতিষ্ঠা বার্ষিকী পালিত</a
              >

              <a href="" class="text-black text-[16px]"
                >পশ্চিমাঞ্চল রেলওয়ে শ্রমিকলীগের শতাধিক নেতাকর্মী কর্মস্থলে
                অনুপস্থিত</a
              >

              <a href="" class="text-black text-[16px]"
                >রৌমারীতে জামায়াতের কর্মী সম্মেলন অনুষ্ঠিত</a
              >

              <a href="" class="text-black text-[16px]"
                >রৌমারীতে সাংবাদিকের সাথে অসৌজন্য আচরণে বিজিবি ক্লোজ</a
              >

              <a href="" class="text-black text-[16px]"
                >রৌমারীর সীমান্তে বিজিবি ও ছাত্র-জনতা রাস্তা সংস্কার সর্ব মহলে
                প্রশংসা</a
              >

              <a href="" class="text-black text-[16px]"
                >রৌমারীতে স্বাধীন প্রশাসন উদ্বোধন দিবস পালিত</a
              >
            </marquee>
          </div>
        </div>
      </div>
    </div>
    <!--  -->
    <div>
      <div class="mt-6">
        <div
          class="container mx-auto flex justify-between items-center bg-[#EDE9E9]"
        >
          <div
            class="siam w-1/6 md:w-1/7 px-2 py-2 inline-block bg-[#cc0000] text-white"
          >
            <a href="" class="flex items-center text-white">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 448 512"
                class="w-5 h-5 mr-2"
                fill="currentColor"
              >
                <path
                  d="M0 96C0 78.3 14.3 64 32 64h384c17.7 0 32 14.3 32 32s-14.3 32-32 32H32C14.3 128 0 113.7 0 96zM0 256c0-17.7 14.3-32 32-32h384c17.7 0 32 14.3 32 32s-14.3 32-32 32H32c-17.7 0-32-14.3-32-32zM448 416c0 17.7-14.3 32-32 32H32c-17.7 0-32-14.3-32-32s14.3-32 32-32h384c17.7 0 32 14.3 32 32z"
                />
              </svg>
              সারাদেশ
            </a>
          </div>
        </div>
      </div>

      <div class="container mx-auto p-1 mt-2">
        <div class="flex flex-wrap justify-center gap-6">
          <div
            class="min-w-[200px] max-w-[300px] flex-1 bg-white shadow-md rounded-lg overflow-hidden"
          >
            <div
              class="h-48 bg-cover bg-center"
              style="
                background-image: url('https://royelnews.com/wp-content/uploads/2024/09/inbound3425044609959334860-600x337.jpg');
              "
            ></div>
            <div class="p-4">
              <h4
                class="text-[15px] font-semibold text-gray-500 hover:text-[#3636a1] m-[15px]"
              >
                <a href="#"
                  >কুড়িগ্রামে বৈষম্য বিরোধী ছাত্র আন্দোলনে আহত আশিক চিকিৎসাধীন
                  অবস্থায় ঢাকায় মারা গেছে</a
                >
              </h4>
            </div>
          </div>

          <div
            class="min-w-[200px] max-w-[300px] flex-1 bg-white shadow-md rounded-lg overflow-hidden"
          >
            <div
              class="h-48 bg-cover bg-center"
              style="
                background-image: url('https://royelnews.com/wp-content/uploads/2024/09/IMG-20240901-WA0279-600x337.jpg');
              "
            ></div>
            <div class="p-4">
              <h4
                class="text-[15px] font-semibold text-gray-500 hover:text-[#191957] m-[15px]"
              >
                নগরীতে প্রতারণার জেরে কথিত সাংবাদিক চপলকে চড়-থাপ্পড়, ছড়াচ্ছে
                অপপ্রচার
              </h4>
            </div>
          </div>

          <div
            class="min-w-[200px] max-w-[300px] flex-1 bg-white shadow-md rounded-lg overflow-hidden"
          >
            <div
              class="h-48 bg-cover bg-center"
              style="
                background-image: url('https://royelnews.com/wp-content/uploads/2024/09/received_1954492561735802-600x337.jpeg');
              "
            ></div>
            <div class="p-4">
              <h4
                class="text-[15px] font-semibold text-gray-500 hover:text-[#3636a1] m-[15px]"
              >
                নাগরিক সনদ অনুযায়ী সেবা প্রদান, প্রোপাগাণ্ডা ছড়ানোর অভিযোগ
              </h4>
            </div>
          </div>

          <div
            class="min-w-[200px] max-w-[300px] flex-1 bg-white shadow-md rounded-lg overflow-hidden"
          >
            <div
              class="h-48 bg-cover bg-center"
              style="
                background-image: url('https://royelnews.com/wp-content/uploads/2024/08/IMG-725101963-600x337.jpg');
              "
            ></div>
            <div class="p-4">
              <h4
                class="text-[15px] font-semibold text-gray-500 hover:text-[#3636a1] m-[15px]"
              >
                প্রতিশোধ নয় দেশকে নতুন ভাবে গড়তে চাই জামায়াতে ইসলামী
              </h4>
            </div>
          </div>

          <div
            class="min-w-[200px] max-w-[300px] flex-1 bg-white shadow-md rounded-lg overflow-hidden"
          >
            <div
              class="h-48 bg-cover bg-center"
              style="
                background-image: url('https://royelnews.com/wp-content/uploads/2024/08/Messenger_creation_E99E5FA5-0265-4295-9E75-A6A7F7189730-600x324.jpeg');
              "
            ></div>
            <div class="p-4">
              <h4
                class="text-[15px] font-semibold text-gray-500 hover:text-[#3636a1] m-[15px]"
              >
                পশ্চিমাঞ্চল রেলওয়ে শ্রমিকলীগের শতাধিক নেতাকর্মী কর্মস্থলে
                অনুপস্থিত
              </h4>
            </div>
          </div>

          <div
            class="min-w-[200px] max-w-[300px] flex-1 bg-white shadow-md rounded-lg overflow-hidden"
          >
            <div
              class="h-48 bg-cover bg-center"
              style="
                background-image: url('https://royelnews.com/wp-content/uploads/2024/08/download-600x337.jpeg');
              "
            ></div>
            <div class="p-4">
              <h4
                class="text-[15px] font-semibold text-gray-500 hover:text-[#3636a1] m-[15px]"
              >
                রৌমারীতে স্বাধীন প্রশাসন উদ্বোধন দিবস পালিত
              </h4>
            </div>
          </div>

          <div
            class="min-w-[200px] max-w-[300px] flex-1 bg-white shadow-md rounded-lg overflow-hidden"
          >
            <div
              class="h-48 bg-cover bg-center"
              style="
                background-image: url('https://royelnews.com/wp-content/uploads/2024/08/IMG-20240827-WA0067-600x337.jpg');
              "
            ></div>
            <div class="p-4">
              <h4
                class="text-[15px] font-semibold text-gray-500 hover:text-[#3636a1] m-[15px]"
              >
                রাজশাহীতে জনস্বাস্থ্য কর্মকর্তার বদলি বাণিজ্য
              </h4>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!--------------add option start-------------->

    <div class="flex flex-wrap justify-between mt-2">
      <div class="w-full sm:w-1/2 p-2">
        <div class="bg-white">
          <img
            class="w-full h-auto"
            src="https://royelnews.com/wp-content/uploads/2023/10/biggapon-1.gif"
            alt=""
          />
        </div>
      </div>
      <div class="w-full sm:w-1/2 p-2">
        <div class="bg-white">
          <img
            class="w-full h-auto"
            src="https://royelnews.com/wp-content/uploads/2023/10/biggapon-1.gif"
            alt=""
          />
        </div>
      </div>
    </div>

    <!-- Wrapper for slides -->

    <!--  -->
    <div class="section_two mx-auto px-4 py-8">
      <div class="max-w-7xl mx-auto">
        <div class="photo_gallery relative">
          <div class="carousel relative overflow-hidden">
            <!-- Slides -->
            <div class="carousel-inner relative w-full">
              <div
                v-for="(slide, index) in slides"
                :key="index"
                :class="['carousel-item', { hidden: index !== currentIndex }]"
              >
                <div class="Name">
                  <a :href="slide.link">
                    <img
                      :src="slide.image"
                      :alt="'Slide ' + (index + 1)"
                      class="w-full h-auto rounded-lg shadow-lg"
                    />
                  </a>
                  <h4 class="photo_caption text-lg font-medium mt-4">
                    <a
                      :href="slide.link"
                      class="text-gray-600 hover:text-blue-800"
                      >{{ slide.caption }}</a
                    >
                  </h4>
                </div>
              </div>
            </div>

            <!-- Controls -->
            <button
              @click="prevSlide"
              class="absolute top-1/2 left-4 transform -translate-y-1/2 text-white rounded-full p-2"
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
              @click="nextSlide"
              class="absolute top-1/2 right-4 transform -translate-y-1/2 text-white rounded-full p-2"
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
        </div>
      </div>
    </div>

    <!-- catagory three -->
    <div class="flex flex-wrap -mx-2">
      <div class="w-full md:w-1/3 px-2">
        <div class="bg-white shadow-lg rounded-lg overflow-hidden">
          <div class="relative">
            <a href="">
              <img
                src="https://royelnews.com/wp-content/uploads/2024/09/received_2866279110191873-600x337.jpeg"
                alt=""
                class="w-full h-auto"
              />
            </a>
          </div>
          <div class="p-4">
            <h4 class="text-[16px] font-semibold mb-2">
              <a href="" class="text-gray-500 hover:text-blue-600">
                বৈষম্যহীন, নিরাপদ, মানবিক বাংলাদেশ গড়ার প্রত্যয়ে জাতীয়তাবাদী
                যুবদলের মতবিনিময় সভা অনুষ্ঠিত
              </a>
            </h4>
          </div>
        </div>
      </div>

      <div class="w-full md:w-1/3 px-2">
        <div class="bg-white shadow-lg rounded-lg overflow-hidden">
          <div class="relative">
            <a href="">
              <img
                src="https://royelnews.com/wp-content/uploads/2024/08/IMG-725101963-600x337.jpg"
                alt=""
                class="w-full h-auto"
              />
            </a>
          </div>
          <div class="p-4">
            <h4 class="text-[16px] font-semibold mb-2">
              <a href="/" class="text-gray-500 hover:text-blue-600">
                প্রতিশোধ নয় দেশকে নতুন ভাবে গড়তে চাই জামায়াতে ইসলামী
              </a>
            </h4>
          </div>
        </div>
      </div>

      <div class="w-full md:w-1/3 px-2">
        <div class="bg-white shadow-lg rounded-lg overflow-hidden">
          <div class="relative">
            <a href="">
              <img
                src="https://royelnews.com/wp-content/uploads/2024/08/IMG-20240827-WA0067-600x337.jpg"
                alt=""
                class="w-full h-auto"
              />
            </a>
          </div>
          <div class="p-4">
            <h4 class="text-[16px] font-semibold mb-2">
              <a href="" class="text-gray-500 hover:text-blue-600">
                রাজশাহীতে জনস্বাস্থ্য কর্মকর্তার বদলি বাণিজ্য
              </a>
            </h4>
          </div>
        </div>
      </div>
    </div>
    <!--  -->
    <div class="flex flex-wrap">
      <div class="w-full sm:w-1/2 md:w-1/3 p-2">
        <div class="bg-white rounded-lg shadow">
          <div>
            <a
              href="https://royelnews.com/%e0%a7%a7%e0%a7%ae-%e0%a6%ac%e0%a6%9b%e0%a6%b0-%e0%a6%aa%e0%a6%b0-%e0%a6%b0%e0%a6%be%e0%a6%9c%e0%a6%b6%e0%a6%be%e0%a6%b9%e0%a7%80-%e0%a6%aa%e0%a7%8d%e0%a6%b0%e0%a7%87%e0%a6%b8%e0%a6%95%e0%a7%8d/"
            >
              <img
                class="w-full h-auto rounded-t-lg"
                src="https://royelnews.com/wp-content/uploads/2024/08/images-6-549x337.jpeg"
                alt=""
              />
            </a>
          </div>
          <div class="p-4">
            <h4 class="text-[16px] font-bold">
              <a class="text-gray-500 hover:text-blue-800" href=""
                >১৮ বছর পর রাজশাহী প্রেসক্লাবের আহ্বায়ক কমিটি গঠন
              </a>
            </h4>
          </div>
        </div>
      </div>

      <div class="w-full sm:w-1/2 md:w-1/3 p-2">
        <div class="bg-white rounded-lg shadow">
          <div>
            <a href="">
              <img
                class="w-full h-auto rounded-t-lg"
                src="https://royelnews.com/wp-content/uploads/2024/08/received_8038653189582922-600x337.jpeg"
                alt=""
              />
            </a>
          </div>
          <div class="p-4">
            <h4 class="text-[16px] font-bold">
              <a class="text-gray-500 hover:text-blue-800" href=""
                >রাজশাহী শাহ্ মখদুম বিমান বন্দরের ম্যানেজারকে আইনগত নোটিশ</a
              >
            </h4>
          </div>
        </div>
      </div>

      <div class="w-full sm:w-1/2 md:w-1/3 p-2">
        <div class="bg-white rounded-lg shadow">
          <div>
            <a href="">
              <img
                class="w-full h-auto rounded-t-lg"
                src="https://royelnews.com/wp-content/uploads/2024/08/InShot_20240814_193646461-600x337.jpg"
                alt=""
              />
            </a>
          </div>
          <div class="p-4">
            <h4 class="text-[16px] font-bold">
              <a class="text-gray-500 hover:text-blue-800" href=""
                >ছাত্রদের গুম &#8211; খুন ও খুনি হাসিনার বিচারের দাবিতে রাজশাহী
                যুবদলের বিক্ষোভ মিছিল ও অবস্থান কর্মসূচি</a
              >
            </h4>
          </div>
        </div>
      </div>

      <!-- main div -->

      <div class="flex gap-4">
        <!-- step one -->
        <div class="flex flex-col md:w-1/3">
          <!-- Category Title -->
          <div class="mt-6">
            <div
              class="container mx-auto flex justify-between items-center bg-[#EDE9E9]"
            >
              <div
                class="siam w-1/6 md:w-1/3 px-2 py-2 inline-block bg-[#cc0000] text-white"
              >
                <a href="" class="flex items-center text-white">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 448 512"
                    class="w-5 h-5 mr-2"
                    fill="currentColor"
                  >
                    <path
                      d="M0 96C0 78.3 14.3 64 32 64h384c17.7 0 32 14.3 32 32s-14.3 32-32 32H32C14.3 128 0 113.7 0 96zM0 256c0-17.7 14.3-32 32-32h384c17.7 0 32 14.3 32 32s-14.3 32-32 32H32c-17.7 0-32-14.3-32-32zM448 416c0 17.7-14.3 32-32 32H32c-17.7 0-32-14.3-32-32s14.3-32 32-32h384c17.7 0 32 14.3 32 32z"
                    />
                  </svg>
                  চাকরি
                </a>
              </div>
            </div>
          </div>

          <!-- Article Box -->
          <div class="shadow-lg mt-3">
            <!-- Image -->
            <div class="overflow-hidden">
              <a href="">
                <img
                  class="w-full h-auto"
                  src="https://royelnews.com/wp-content/uploads/2023/10/395711786_719079943577963_376892770646993724_n-1-600x337.jpg"
                  alt=""
                />
              </a>
            </div>

            <!-- Article Content -->
            <div class="p-4 shadow-lg bg-white rounded-b-lg">
              <h4 class="text-[16px] font-bold mb-2 border-b pb-2">
                <a href="" class="text-gray-500 hover:text-blue-800"
                  >উলিপুরে বাংলাদেশ জাতীয় হিন্দু মহাজোটের সহযোগীতা, শারোদীয়
                  দূর্গা উৎসব সম্পন্ন।</a
                >
              </h4>

              <!-- Small Image and Title -->
              <div class="flex items-center mt-4 border-t pt-4">
                <a href="" class="flex items-center space-x-2">
                  <img
                    class="w-1/3 h-auto"
                    src="https://royelnews.com/wp-content/uploads/2023/01/3-Copy-639-700x390-1.jpg"
                    alt=""
                  />
                  <h4 class="text-sm font-medium text-black hover:text-red-600">
                    রাশিয়া ছেড়ে পালিয়েছেন সাবেক ওয়াগনার কমান্ডার
                  </h4>
                </a>
              </div>
              <div class="flex items-center mt-4 border-t pt-4">
                <a href="" class="flex items-center space-x-2">
                  <img
                    class="w-1/3 h-auto"
                    src="https://royelnews.com/wp-content/uploads/2023/01/3-Copy-638-700x390-1.jpg"
                    alt=""
                    decoding="async"
                    srcset="
                      https://royelnews.com/wp-content/uploads/2023/01/3-Copy-638-700x390-1.jpg         700w,
                      https://royelnews.com/wp-content/uploads/2023/01/3-Copy-638-700x390-1-300x167.jpg 300w
                    "
                    sizes="(max-width: 600px) 100vw, 600px"
                  />
                  <h4 class="text-sm font-medium text-black hover:text-red-600">
                    ৬ দশকের মধ্যে সবচেয়ে কম জন্মহার চীনে!
                  </h4>
                </a>
              </div>

              <div class="flex items-center mt-4 border-t pt-4">
                <a href="" class="flex items-center space-x-2">
                  <img
                    class="w-1/3 h-auto"
                    src="https://royelnews.com/wp-content/uploads/2023/01/3-Copy-637-700x390-1.jpg"
                    alt=""
                    decoding="async"
                    srcset="
                      https://royelnews.com/wp-content/uploads/2023/01/3-Copy-637-700x390-1.jpg         700w,
                      https://royelnews.com/wp-content/uploads/2023/01/3-Copy-637-700x390-1-300x167.jpg 300w
                    "
                    sizes="(max-width: 600px) 100vw, 600px"
                  />
                  <h4 class="text-sm font-medium text-black hover:text-red-600">
                    দ্বিতীয় বিয়ে করেছেন দাউদ ইব্রাহিম, স্ত্রী পাকিস্তানি’
                  </h4>
                </a>
              </div>

              <div class="flex items-center mt-4 border-t pt-4">
                <a href="" class="flex items-center space-x-2">
                  <img
                    class="w-1/3 h-auto"
                    src="https://royelnews.com/wp-content/uploads/2022/12/322625132_719526586261443_2986189997021982751_n-600x337.jpg"
                    alt=""
                    decoding="async"
                  />
                  <h4 class="text-sm font-medium text-black hover:text-red-600">
                    রৌমারীতে আই,এফ,আই, সি, ব্যাংক উদ্বোধন
                  </h4>
                </a>
              </div>
            </div>
            <div class="bg-gray-100 p-4">
              <h4
                class="text-right text-[14px] text-gray-600 hover:text-green-600 flex justify-end items-center"
              >
                <a href="" class="flex items-center space-x-1">
                  <span>আরো সংবাদ..</span>
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 512 512"
                    class="w-3"
                  >
                    <path
                      fill="currentColor"
                      d="M470.6 278.6c12.5-12.5 12.5-32.8 0-45.3l-160-160c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3L402.7 256 265.4 393.4c-12.5 12.5-12.5 32.8 0 45.3s32.8 12.5 45.3 0l160-160zm-352 160l160-160c12.5-12.5 12.5-32.8 0-45.3l-160-160c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3L210.7 256 73.4 393.4c-12.5 12.5-12.5 32.8 0 45.3s32.8 12.5 45.3 0z"
                    />
                  </svg>
                </a>
              </h4>
            </div>
          </div>
        </div>

        <!-- step two -->
        <div class="md:w-1/3 sm:w-1/3">
          <div class="mt-6">
            <div
              class="container mx-auto flex justify-between items-center bg-[#EDE9E9]"
            >
              <div
                class="siam w-1/6 md:w-1/2 px-2 py-2 inline-block bg-[#cc0000] text-white"
              >
                <a href="" class="flex items-center text-white">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 448 512"
                    class="w-5 h-5 mr-2"
                    fill="currentColor"
                  >
                    <path
                      d="M0 96C0 78.3 14.3 64 32 64h384c17.7 0 32 14.3 32 32s-14.3 32-32 32H32C14.3 128 0 113.7 0 96zM0 256c0-17.7 14.3-32 32-32h384c17.7 0 32 14.3 32 32s-14.3 32-32 32H32c-17.7 0-32-14.3-32-32zM448 416c0 17.7-14.3 32-32 32H32c-17.7 0-32-14.3-32-32s14.3-32 32-32h384c17.7 0 32 14.3 32 32z"
                    />
                  </svg>
                  আর্ন্তজাতিক
                </a>
              </div>
            </div>
          </div>

          <!-- Article Section -->
          <div class="shadow-lg bg-white rounded-b-lg">
            <div class="mb-4 mt-3">
              <a href="">
                <img
                  src="https://royelnews.com/wp-content/uploads/2023/10/395711786_719079943577963_376892770646993724_n-1-600x337.jpg"
                  alt="Main Article Image"
                  class="w-full h-auto"
                />
              </a>
              <div class="p-4">
                <h4 class="text-[16px] font-bold mb-2 border-b pb-2">
                  <a href="" class="text-gray-500 hover:text-blue-800">
                    উলিপুরে বাংলাদেশ জাতীয় হিন্দু মহাজোটের সহযোগীতা, শারোদীয়
                    দূর্গা উৎসব সম্পন্ন।
                  </a>
                </h4>

                <!-- Small Images Section -->

                <div class="flex items-center mt-4 border-t pt-4">
                  <a href="" class="flex items-center space-x-2">
                    <img
                      class="w-1/3 h-auto"
                      src="https://royelnews.com/wp-content/uploads/2023/09/prothomalo-bangla_2021-11_8f79a823-5cec-48db-a67b-ef98317af490_P_1-600x337.webp"
                      alt=""
                      decoding="async"
                    />
                    <h4
                      class="text-sm font-medium text-black hover:text-red-600"
                    >
                      ফ্রান্সের প্রেসিডেন্ট আসছেন আজ, যা নিয়ে আলোচনা হতে পারে
                    </h4>
                  </a>
                </div>

                <div class="flex items-center mt-4 border-t pt-4">
                  <a href="" class="flex items-center space-x-2">
                    <img
                      class="w-1/3 h-auto"
                      src="https://royelnews.com/wp-content/uploads/2023/01/5-4-700x390-1.jpeg"
                      alt=""
                      decoding="async"
                    />
                    <h4
                      class="text-sm font-medium text-black hover:text-red-600"
                    >
                      জাপানে দুই সপ্তাহে ৫ হাজার করোনা রোগীর মৃত্যু
                    </h4>
                  </a>
                </div>

                <div class="flex items-center mt-4 border-t pt-4">
                  <a href="" class="flex items-center space-x-2">
                    <img
                      class="w-1/3 h-auto"
                      src="https://royelnews.com/wp-content/uploads/2023/01/3-Copy-641-700x390-1.jpg"
                      alt=""
                      decoding="async"
                    />
                    <h4
                      class="text-sm font-medium text-black hover:text-red-600"
                    >
                      সেদিন ওশিনকে কাজে যেতে নিষেধ করেছিলেন বাবা
                    </h4>
                  </a>
                </div>

                <div class="flex items-center mt-4 border-t pt-4">
                  <a href="" class="flex items-center space-x-2">
                    <img
                      class="w-1/3 h-auto"
                      src="https://royelnews.com/wp-content/uploads/2023/01/3-Copy-639-700x390-1.jpg"
                      alt=""
                      decoding="async"
                    />
                    <h4
                      class="text-sm font-medium text-black hover:text-red-600"
                    >
                      রাশিয়া ছেড়ে পালিয়েছেন সাবেক ওয়াগনার কমান্ডার
                    </h4>
                  </a>
                </div>
              </div>
              <div class="bg-gray-100 p-4">
                <h4
                  class="text-right text-[14px] text-gray-600 hover:text-green-600 flex justify-end items-center"
                >
                  <a href="" class="flex items-center space-x-1">
                    <span>আরো সংবাদ..</span>
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      viewBox="0 0 512 512"
                      class="w-3"
                    >
                      <path
                        fill="currentColor"
                        d="M470.6 278.6c12.5-12.5 12.5-32.8 0-45.3l-160-160c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3L402.7 256 265.4 393.4c-12.5 12.5-12.5 32.8 0 45.3s32.8 12.5 45.3 0l160-160zm-352 160l160-160c12.5-12.5 12.5-32.8 0-45.3l-160-160c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3L210.7 256 73.4 393.4c-12.5 12.5-12.5 32.8 0 45.3s32.8 12.5 45.3 0z"
                      />
                    </svg>
                  </a>
                </h4>
              </div>
            </div>
          </div>
        </div>
        <!-- step three -->
        <div class="md:w-1/3 sm:w-1/3">
          <!-- Category Title -->
          <div class="mt-6">
            <div
              class="container mx-auto flex justify-between items-center bg-[#EDE9E9]"
            >
              <div
                class="siam w-1/6 md:w-1/3 px-2 py-2 inline-block bg-[#cc0000] text-white"
              >
                <a href="" class="flex items-center text-white">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 448 512"
                    class="w-5 h-5 mr-2"
                    fill="currentColor"
                  >
                    <path
                      d="M0 96C0 78.3 14.3 64 32 64h384c17.7 0 32 14.3 32 32s-14.3 32-32 32H32C14.3 128 0 113.7 0 96zM0 256c0-17.7 14.3-32 32-32h384c17.7 0 32 14.3 32 32s-14.3 32-32 32H32c-17.7 0-32-14.3-32-32zM448 416c0 17.7-14.3 32-32 32H32c-17.7 0-32-14.3-32-32s14.3-32 32-32h384c17.7 0 32 14.3 32 32z"
                    />
                  </svg>
                  ধর্ম
                </a>
              </div>
            </div>
          </div>

          <!-- Article Section -->
          <div class="shadow-lg bg-white rounded-b-lg">
            <div class="mb-4 mt-3">
              <a href="">
                <img
                  src="https://royelnews.com/wp-content/uploads/2023/10/395711786_719079943577963_376892770646993724_n-1-600x337.jpg"
                  alt="Main Article Image"
                  class="w-full h-auto"
                />
              </a>
              <div class="p-4">
                <h4 class="text-[16px] font-bold mb-2 border-b pb-2">
                  <a href="" class="text-gray-500 hover:text-blue-800">
                    উলিপুরে বাংলাদেশ জাতীয় হিন্দু মহাজোটের সহযোগীতা, শারোদীয়
                    দূর্গা উৎসব সম্পন্ন।
                  </a>
                </h4>

                <!-- Small Images Section -->

                <div class="flex items-center mt-4 border-t pt-4">
                  <a href="" class="flex items-center space-x-2">
                    <img
                      class="w-1/3 h-auto"
                      src="https://royelnews.com/wp-content/uploads/2023/10/inbound8594950081661160676.jpg"
                      alt=""
                      decoding="async"
                    />
                    <h4
                      class="text-sm font-medium text-black hover:text-red-600"
                    >
                      উলিপুরে হিন্দু মহাজোটের বিভিন্ন কর্মসূচি ও সহযোগীতায়
                      শারদীয় দূর্গা উৎসব পালিত।
                    </h4>
                  </a>
                </div>
                <div class="flex items-center mt-4 border-t pt-4">
                  <a href="" class="flex items-center space-x-2">
                    <img
                      class="w-1/3 h-auto"
                      src="https://royelnews.com/wp-content/uploads/2023/01/3-Copy-639-700x390-1.jpg"
                      alt=""
                      decoding="async"
                    />
                    <h4
                      class="text-sm font-medium text-black hover:text-red-600"
                    >
                      রাশিয়া ছেড়ে পালিয়েছেন সাবেক ওয়াগনার কমান্ডার
                    </h4>
                  </a>
                </div>
                <div class="flex items-center mt-4 border-t pt-4">
                  <a href="" class="flex items-center space-x-2">
                    <img
                      class="w-1/3 h-auto"
                      src="https://royelnews.com/wp-content/uploads/2023/01/3-Copy-638-700x390-1.jpg"
                      alt=""
                      decoding="async"
                    />
                    <h4
                      class="text-sm font-medium text-black hover:text-red-600"
                    >
                      ৬ দশকের মধ্যে সবচেয়ে কম জন্মহার চীনে!
                    </h4>
                  </a>
                </div>
                <div class="flex items-center mt-4 border-t pt-4">
                  <a href="" class="flex items-center space-x-2">
                    <img
                      class="w-1/3 h-auto"
                      src="https://royelnews.com/wp-content/uploads/2023/01/3-Copy-637-700x390-1.jpg"
                      alt=""
                      decoding="async"
                    />
                    <h4
                      class="text-sm font-medium text-black hover:text-red-600"
                    >
                      দ্বিতীয় বিয়ে করেছেন দাউদ ইব্রাহিম, স্ত্রী পাকিস্তানি’
                    </h4>
                  </a>
                </div>
              </div>
              <div class="bg-gray-100 p-4">
                <h4
                  class="text-right text-[14px] text-gray-600 hover:text-green-600 flex justify-end items-center"
                >
                  <a href="" class="flex items-center space-x-1">
                    <span>আরো সংবাদ..</span>
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      viewBox="0 0 512 512"
                      class="w-3"
                    >
                      <path
                        fill="currentColor"
                        d="M470.6 278.6c12.5-12.5 12.5-32.8 0-45.3l-160-160c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3L402.7 256 265.4 393.4c-12.5 12.5-12.5 32.8 0 45.3s32.8 12.5 45.3 0l160-160zm-352 160l160-160c12.5-12.5 12.5-32.8 0-45.3l-160-160c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3L210.7 256 73.4 393.4c-12.5 12.5-12.5 32.8 0 45.3s32.8 12.5 45.3 0z"
                      />
                    </svg>
                  </a>
                </h4>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Tailwind  with Banner Ads -->
    <div class="flex flex-wrap mt-3">
      <div class="w-full md:w-1/2 p-2">
        <div class="bg-gray-100">
          <div class="widget_area">
            <div class="textwidget">
              <p>
                <img
                  class="w-full h-auto"
                  src="https://royelnews.com/wp-content/uploads/2022/12/banner-ads-hostitbd.jpg"
                  alt="Banner Ad"
                  srcset="
                    https://royelnews.com/wp-content/uploads/2022/12/banner-ads-hostitbd.jpg          2330w,
                    https://royelnews.com/wp-content/uploads/2022/12/banner-ads-hostitbd-300x50.jpg    300w,
                    https://royelnews.com/wp-content/uploads/2022/12/banner-ads-hostitbd-1024x169.jpg 1024w,
                    https://royelnews.com/wp-content/uploads/2022/12/banner-ads-hostitbd-768x127.jpg   768w,
                    https://royelnews.com/wp-content/uploads/2022/12/banner-ads-hostitbd-1536x254.jpg 1536w,
                    https://royelnews.com/wp-content/uploads/2022/12/banner-ads-hostitbd-2048x338.jpg 2048w
                  "
                  sizes="(max-width: 2330px) 100vw, 2330px"
                />
              </p>
            </div>
          </div>
        </div>
      </div>

      <div class="w-full md:w-1/2 p-2">
        <div class="bg-gray-100">
          <div class="widget_area">
            <div class="textwidget">
              <p>
                <img
                  class="w-full h-auto"
                  src="https://royelnews.com/wp-content/uploads/2022/12/banner-ads-hostitbd.jpg"
                  alt="Banner Ad"
                  srcset="
                    https://royelnews.com/wp-content/uploads/2022/12/banner-ads-hostitbd.jpg          2330w,
                    https://royelnews.com/wp-content/uploads/2022/12/banner-ads-hostitbd-300x50.jpg    300w,
                    https://royelnews.com/wp-content/uploads/2022/12/banner-ads-hostitbd-1024x169.jpg 1024w,
                    https://royelnews.com/wp-content/uploads/2022/12/banner-ads-hostitbd-768x127.jpg   768w,
                    https://royelnews.com/wp-content/uploads/2022/12/banner-ads-hostitbd-1536x254.jpg 1536w,
                    https://royelnews.com/wp-content/uploads/2022/12/banner-ads-hostitbd-2048x338.jpg 2048w
                  "
                  sizes="(max-width: 2330px) 100vw, 2330px"
                />
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- বিনোদন -->
    <div class="mt-3">
      <div
        class="container mx-auto flex justify-between items-center bg-[#EDE9E9]"
      >
        <div
          class="siam w-1/6 md:w-1/7 px-2 py-2 inline-block bg-[#cc0000] text-white"
        >
          <a href="" class="flex items-center text-white">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 448 512"
              class="w-5 h-5 mr-2"
              fill="currentColor"
            >
              <path
                d="M0 96C0 78.3 14.3 64 32 64h384c17.7 0 32 14.3 32 32s-14.3 32-32 32H32C14.3 128 0 113.7 0 96zM0 256c0-17.7 14.3-32 32-32h384c17.7 0 32 14.3 32 32s-14.3 32-32 32H32c-17.7 0-32-14.3-32-32zM448 416c0 17.7-14.3 32-32 32H32c-17.7 0-32-14.3-32-32s14.3-32 32-32h384c17.7 0 32 14.3 32 32z"
              />
            </svg>
            বিনোদন
          </a>
        </div>
      </div>
    </div>
    <!--বিনোদন  -->
    <NewsSlider />

    <!-- Tailwind CSS  with Ads -->
    <div class="flex flex-wrap justify-between mt-2">
      <div class="w-full sm:w-1/2 p-2">
        <div class="bg-white">
          <img
            class="w-full h-auto"
            src="https://royelnews.com/wp-content/uploads/2023/10/biggapon-1.gif"
            alt=""
          />
        </div>
      </div>
      <div class="w-full sm:w-1/2 p-2">
        <div class="bg-white">
          <img
            class="w-full h-auto"
            src="https://royelnews.com/wp-content/uploads/2023/10/biggapon-1.gif"
            alt=""
          />
        </div>
      </div>
    </div>
    <!-- রাজনীতি  -->
    <div class="flex gap-4">
      <!-- step one -->
      <div class="flex flex-col md:w-1/3">
        <!-- Category Title -->
        <div class="mt-3">
          <div
            class="container mx-auto flex justify-between items-center bg-[#EDE9E9]"
          >
            <div
              class="siam w-1/6 md:w-1/2 px-2 py-2 inline-block bg-[#cc0000] text-white"
            >
              <a href="" class="flex items-center text-white">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 448 512"
                  class="w-5 h-5 mr-2"
                  fill="currentColor"
                >
                  <path
                    d="M0 96C0 78.3 14.3 64 32 64h384c17.7 0 32 14.3 32 32s-14.3 32-32 32H32C14.3 128 0 113.7 0 96zM0 256c0-17.7 14.3-32 32-32h384c17.7 0 32 14.3 32 32s-14.3 32-32 32H32c-17.7 0-32-14.3-32-32zM448 416c0 17.7-14.3 32-32 32H32c-17.7 0-32-14.3-32-32s14.3-32 32-32h384c17.7 0 32 14.3 32 32z"
                  />
                </svg>
                রাজনীতি
              </a>
            </div>
          </div>
        </div>

        <!-- Article Box -->
        <div class="shadow-lg mt-3">
          <!-- Image -->
          <div class="overflow-hidden">
            <a href="">
              <img
                class="w-full h-auto"
                src="https://royelnews.com/wp-content/uploads/2024/09/received_2866279110191873-600x337.jpeg"
                alt=""
              />
            </a>
          </div>

          <!-- Article Content -->
          <div class="p-4 shadow-lg bg-white rounded-b-lg">
            <h4 class="text-[16px] font-bold mb-2 border-b pb-2">
              <a href="" class="text-gray-500 hover:text-blue-800"
                >বৈষম্যহীন, নিরাপদ, মানবিক বাংলাদেশ গড়ার প্রত্যয়ে জাতীয়তাবাদী
                যুবদলের মতবিনিময় সভা অনুষ্ঠিত</a
              >
            </h4>

            <!-- Small Image and Title -->
            <div class="flex items-center mt-4 border-t pt-4">
              <a href="" class="flex items-center space-x-2">
                <img
                  class="w-1/3 h-auto"
                  src="https://royelnews.com/wp-content/uploads/2024/08/IMG-725101963-600x337.jpg"
                  alt=""
                />
                <h4 class="text-sm font-medium text-black hover:text-red-600">
                  প্রতিশোধ নয় দেশকে নতুন ভাবে গড়তে চাই জামায়াতে ইসলামী
                </h4>
              </a>
            </div>
            <div class="flex items-center mt-4 border-t pt-4">
              <a href="" class="flex items-center space-x-2">
                <img
                  class="w-1/3 h-auto"
                  src="https://royelnews.com/wp-content/uploads/2024/08/IMG-20240819-WA0070-600x337.jpg"
                  alt=""
                  decoding="async"
                  srcset="
                    https://royelnews.com/wp-content/uploads/2023/01/3-Copy-638-700x390-1.jpg         700w,
                    https://royelnews.com/wp-content/uploads/2023/01/3-Copy-638-700x390-1-300x167.jpg 300w
                  "
                  sizes="(max-width: 600px) 100vw, 600px"
                />
                <h4 class="text-sm font-medium text-black hover:text-red-600">
                  রাজশাহীতে জাঁকজমক ভাবে স্বেচ্ছাসেবক দলের ৪৪তম প্রতিষ্ঠা
                  বার্ষিকী পালন
                </h4>
              </a>
            </div>

            <div class="flex items-center mt-4 border-t pt-4">
              <a href="" class="flex items-center space-x-2">
                <img
                  class="w-1/3 h-auto"
                  src="https://royelnews.com/wp-content/uploads/2024/08/IMG-20240817-WA0071-600x337.jpg"
                  alt=""
                  decoding="async"
                  srcset="
                    https://royelnews.com/wp-content/uploads/2023/01/3-Copy-637-700x390-1.jpg         700w,
                    https://royelnews.com/wp-content/uploads/2023/01/3-Copy-637-700x390-1-300x167.jpg 300w
                  "
                  sizes="(max-width: 600px) 100vw, 600px"
                />
                <h4 class="text-sm font-medium text-black hover:text-red-600">
                  রাজশাহীতে ভূমি দখল-চাঁদাবাজিতে জড়িত হলে আইনে সোপর্দ করুন- মিনু
                </h4>
              </a>
            </div>

            <div class="flex items-center mt-4 border-t pt-4">
              <a href="" class="flex items-center space-x-2">
                <img
                  class="w-1/3 h-auto"
                  src="https://royelnews.com/wp-content/uploads/2024/08/InShot_20240814_193646461-600x337.jpg"
                  alt=""
                  decoding="async"
                />
                <h4 class="text-sm font-medium text-black hover:text-red-600">
                  ছাত্রদের গুম &#8211; খুন ও খুনি হাসিনার বিচারের দাবিতে রাজশাহী
                  যুবদলের বিক্ষোভ মিছিল ও অবস্থান কর্মসূচি
                </h4>
              </a>
            </div>
            <div class="bg-gray-100 p-4 mt-5">
              <h4
                class="text-right text-[14px] text-gray-600 hover:text-green-600 flex justify-end items-center"
              >
                <a href="" class="flex items-center space-x-1">
                  <span>আরো সংবাদ..</span>
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 512 512"
                    class="w-3"
                  >
                    <path
                      fill="currentColor"
                      d="M470.6 278.6c12.5-12.5 12.5-32.8 0-45.3l-160-160c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3L402.7 256 265.4 393.4c-12.5 12.5-12.5 32.8 0 45.3s32.8 12.5 45.3 0l160-160zm-352 160l160-160c12.5-12.5 12.5-32.8 0-45.3l-160-160c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3L210.7 256 73.4 393.4c-12.5 12.5-12.5 32.8 0 45.3s32.8 12.5 45.3 0z"
                    />
                  </svg>
                </a>
              </h4>
            </div>
          </div>
        </div>
      </div>
      <!-- step two -->
      <div class="md:w-1/3 sm:w-1/3">
        <div class="mt-3">
          <div
            class="container mx-auto flex justify-between items-center bg-[#EDE9E9]"
          >
            <div
              class="siam w-1/6 md:w-1/2 px-2 py-2 inline-block bg-[#cc0000] text-white"
            >
              <a
                href="https://royelnews.com/category/%e0%a6%b8%e0%a6%be%e0%a6%b0%e0%a6%be%e0%a6%a6%e0%a7%87%e0%a6%b6/"
                class="flex items-center text-white"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 448 512"
                  class="w-5 h-5 mr-2"
                  fill="currentColor"
                >
                  <path
                    d="M0 96C0 78.3 14.3 64 32 64h384c17.7 0 32 14.3 32 32s-14.3 32-32 32H32C14.3 128 0 113.7 0 96zM0 256c0-17.7 14.3-32 32-32h384c17.7 0 32 14.3 32 32s-14.3 32-32 32H32c-17.7 0-32-14.3-32-32zM448 416c0 17.7-14.3 32-32 32H32c-17.7 0-32-14.3-32-32s14.3-32 32-32h384c17.7 0 32 14.3 32 32z"
                  />
                </svg>
                লাইফস্টাইল
              </a>
            </div>
          </div>
        </div>

        <!-- Article Section -->
        <div class="shadow-lg bg-white rounded-b-lg">
          <div class="mb-4 mt-3">
            <a href="">
              <img
                src="https://royelnews.com/wp-content/uploads/2023/10/395711786_719079943577963_376892770646993724_n-1-600x337.jpg"
                alt="Main Article Image"
                class="w-full h-auto"
              />
            </a>
            <div class="p-4">
              <h4 class="text-[16px] font-bold mb-2 border-b pb-2">
                <a href="" class="text-gray-500 hover:text-blue-800">
                  উলিপুরে বাংলাদেশ জাতীয় হিন্দু মহাজোটের সহযোগীতা, শারোদীয়
                  দূর্গা উৎসব সম্পন্ন।
                </a>
              </h4>

              <!-- Small Images Section -->

              <div class="flex items-center mt-4 border-t pt-4">
                <a href="" class="flex items-center space-x-2">
                  <img
                    class="w-1/3 h-auto"
                    src="https://royelnews.com/wp-content/uploads/2023/01/3-Copy-639-700x390-1.jpg"
                    alt=""
                    decoding="async"
                  />
                  <h4 class="text-sm font-medium text-black hover:text-red-600">
                    রাশিয়া ছেড়ে পালিয়েছেন সাবেক ওয়াগনার কমান্ডার
                  </h4>
                </a>
              </div>

              <div class="flex items-center mt-4 border-t pt-4">
                <a href="" class="flex items-center space-x-2">
                  <img
                    class="w-1/3 h-auto"
                    src="https://royelnews.com/wp-content/uploads/2023/01/3-Copy-638-700x390-1.jpg"
                    alt=""
                    decoding="async"
                  />
                  <h4 class="text-sm font-medium text-black hover:text-red-600">
                    ৬ দশকের মধ্যে সবচেয়ে কম জন্মহার চীনে!
                  </h4>
                </a>
              </div>

              <div class="flex items-center mt-4 border-t pt-4">
                <a href="" class="flex items-center space-x-2">
                  <img
                    class="w-1/3 h-auto"
                    src="https://royelnews.com/wp-content/uploads/2023/01/3-Copy-637-700x390-1.jpg"
                    alt=""
                    decoding="async"
                  />
                  <h4 class="text-sm font-medium text-black hover:text-red-600">
                    দ্বিতীয় বিয়ে করেছেন দাউদ ইব্রাহিম, স্ত্রী পাকিস্তানি’
                  </h4>
                </a>
              </div>

              <div class="flex items-center mt-4 border-t pt-4">
                <a href="" class="flex items-center space-x-2">
                  <img
                    class="w-1/3 h-auto"
                    src="https://royelnews.com/wp-content/uploads/2022/12/322625132_719526586261443_2986189997021982751_n-600x337.jpg"
                    alt=""
                    decoding="async"
                  />
                  <h4 class="text-sm font-medium text-black hover:text-red-600">
                    রৌমারীতে আই,এফ,আই, সি, ব্যাংক উদ্বোধন
                  </h4>
                </a>
              </div>
            </div>
            <div class="bg-gray-100 p-4">
              <h4
                class="text-right text-[14px] text-gray-600 hover:text-green-600 flex justify-end items-center"
              >
                <a href="" class="flex items-center space-x-1">
                  <span>আরো সংবাদ..</span>
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 512 512"
                    class="w-3"
                  >
                    <path
                      fill="currentColor"
                      d="M470.6 278.6c12.5-12.5 12.5-32.8 0-45.3l-160-160c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3L402.7 256 265.4 393.4c-12.5 12.5-12.5 32.8 0 45.3s32.8 12.5 45.3 0l160-160zm-352 160l160-160c12.5-12.5 12.5-32.8 0-45.3l-160-160c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3L210.7 256 73.4 393.4c-12.5 12.5-12.5 32.8 0 45.3s32.8 12.5 45.3 0z"
                    />
                  </svg>
                </a>
              </h4>
            </div>
          </div>
        </div>
      </div>
      <!-- step three -->
      <div class="md:w-1/3 sm:w-1/3">
        <!-- Category Title -->
        <div class="mt-3">
          <div
            class="container mx-auto flex justify-between items-center bg-[#EDE9E9]"
          >
            <div
              class="siam w-1/6 md:w-1/3 px-2 py-2 inline-block bg-[#cc0000] text-white"
            >
              <a href="" class="flex items-center text-white">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 448 512"
                  class="w-5 h-5 mr-2"
                  fill="currentColor"
                >
                  <path
                    d="M0 96C0 78.3 14.3 64 32 64h384c17.7 0 32 14.3 32 32s-14.3 32-32 32H32C14.3 128 0 113.7 0 96zM0 256c0-17.7 14.3-32 32-32h384c17.7 0 32 14.3 32 32s-14.3 32-32 32H32c-17.7 0-32-14.3-32-32zM448 416c0 17.7-14.3 32-32 32H32c-17.7 0-32-14.3-32-32s14.3-32 32-32h384c17.7 0 32 14.3 32 32z"
                  />
                </svg>
                চাকরি
              </a>
            </div>
          </div>
        </div>

        <!-- Article Section -->
        <div class="shadow-lg bg-white rounded-b-lg">
          <div class="mb-4 mt-3">
            <a href="">
              <img
                src="https://royelnews.com/wp-content/uploads/2023/10/395711786_719079943577963_376892770646993724_n-1-600x337.jpg"
                alt="Main Article Image"
                class="w-full h-auto"
              />
            </a>
            <div class="p-4">
              <h4 class="text-[16px] font-bold mb-2 border-b pb-2">
                <a href="" class="text-gray-500 hover:text-blue-800">
                  উলিপুরে বাংলাদেশ জাতীয় হিন্দু মহাজোটের সহযোগীতা, শারোদীয়
                  দূর্গা উৎসব সম্পন্ন।
                </a>
              </h4>

              <!-- Small Images Section -->

              <div class="flex items-center mt-4 border-t pt-4">
                <a href="" class="flex items-center space-x-2">
                  <img
                    class="w-1/3 h-auto"
                    src="https://royelnews.com/wp-content/uploads/2023/10/inbound8594950081661160676.jpg"
                    alt=""
                    decoding="async"
                  />
                  <h4 class="text-sm font-medium text-black hover:text-red-600">
                    উলিপুরে হিন্দু মহাজোটের বিভিন্ন কর্মসূচি ও সহযোগীতায় শারদীয়
                    দূর্গা উৎসব পালিত।
                  </h4>
                </a>
              </div>
              <div class="flex items-center mt-4 border-t pt-4">
                <a href="" class="flex items-center space-x-2">
                  <img
                    class="w-1/3 h-auto"
                    src="https://royelnews.com/wp-content/uploads/2023/01/3-Copy-639-700x390-1.jpg"
                    alt=""
                    decoding="async"
                  />
                  <h4 class="text-sm font-medium text-black hover:text-red-600">
                    রাশিয়া ছেড়ে পালিয়েছেন সাবেক ওয়াগনার কমান্ডার
                  </h4>
                </a>
              </div>
              <div class="flex items-center mt-4 border-t pt-4">
                <a href="" class="flex items-center space-x-2">
                  <img
                    class="w-1/3 h-auto"
                    src="https://royelnews.com/wp-content/uploads/2023/01/3-Copy-638-700x390-1.jpg"
                    alt=""
                    decoding="async"
                  />
                  <h4 class="text-sm font-medium text-black hover:text-red-600">
                    ৬ দশকের মধ্যে সবচেয়ে কম জন্মহার চীনে!
                  </h4>
                </a>
              </div>
              <div class="flex items-center mt-4 border-t pt-4">
                <a href="" class="flex items-center space-x-2">
                  <img
                    class="w-1/3 h-auto"
                    src="https://royelnews.com/wp-content/uploads/2023/01/3-Copy-637-700x390-1.jpg"
                    alt=""
                    decoding="async"
                  />
                  <h4 class="text-sm font-medium text-black hover:text-red-600">
                    দ্বিতীয় বিয়ে করেছেন দাউদ ইব্রাহিম, স্ত্রী পাকিস্তানি’
                  </h4>
                </a>
              </div>
            </div>
            <div class="bg-gray-100 p-4">
              <h4
                class="text-right text-[14px] text-gray-600 hover:text-green-600 flex justify-end items-center"
              >
                <a href="" class="flex items-center space-x-1">
                  <span>আরো সংবাদ..</span>
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 512 512"
                    class="w-3"
                  >
                    <path
                      fill="currentColor"
                      d="M470.6 278.6c12.5-12.5 12.5-32.8 0-45.3l-160-160c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3L402.7 256 265.4 393.4c-12.5 12.5-12.5 32.8 0 45.3s32.8 12.5 45.3 0l160-160zm-352 160l160-160c12.5-12.5 12.5-32.8 0-45.3l-160-160c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3L210.7 256 73.4 393.4c-12.5 12.5-12.5 32.8 0 45.3s32.8 12.5 45.3 0z"
                    />
                  </svg>
                </a>
              </h4>
            </div>
          </div>
        </div>
      </div>

      <!-- step four -->
      <div class="md:w-1/3 sm:w-1/3">
        <!-- Category Title -->
        <div class="mt-3">
          <div
            class="container mx-auto flex justify-between items-center bg-[#EDE9E9]"
          >
            <div
              class="siam w-1/6 md:w-[150px] px-2 py-2 inline-block bg-[#cc0000] text-white"
            >
              <a href="" class="flex items-center text-white">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 448 512"
                  class="w-5 h-5 mr-2"
                  fill="currentColor"
                >
                  <path
                    d="M0 96C0 78.3 14.3 64 32 64h384c17.7 0 32 14.3 32 32s-14.3 32-32 32H32C14.3 128 0 113.7 0 96zM0 256c0-17.7 14.3-32 32-32h384c17.7 0 32 14.3 32 32s-14.3 32-32 32H32c-17.7 0-32-14.3-32-32zM448 416c0 17.7-14.3 32-32 32H32c-17.7 0-32-14.3-32-32s14.3-32 32-32h384c17.7 0 32 14.3 32 32z"
                  />
                </svg>
                শিল্প ও সাহিত্য
              </a>
            </div>
          </div>
        </div>

        <!-- Article Section -->
        <div class="shadow-lg bg-white rounded-b-lg">
          <div class="mb-4 mt-3">
            <a href="">
              <img
                src="https://royelnews.com/wp-content/uploads/2024/07/inbound9009272998494483268-600x337.jpg"
                alt="Main Article Image"
                class="w-full h-auto"
              />
            </a>
            <div class="p-4">
              <h4 class="text-[16px] font-bold mb-2 border-b pb-2">
                <a href="" class="text-gray-500 hover:text-blue-800">
                  কুড়িগ্রামে দৈনিক নতুন সময়ের মত বিনিময়সভা
                </a>
              </h4>

              <!-- Small Images Section -->

              <div class="flex items-center mt-4 border-t pt-4">
                <a href="" class="flex items-center space-x-2">
                  <img
                    class="w-1/3 h-auto"
                    src="https://royelnews.com/wp-content/uploads/2024/05/169403577_2887668758184488_3514495690456674687_n-600x337.jpg"
                    alt=""
                    decoding="async"
                  />
                  <h4 class="text-sm font-medium text-black hover:text-red-600">
                    কুড়িগ্রাম জেলার শ্রেষ্ঠ শ্রেণি শিক্ষক নির্বাচিত হলেন আমিনুল
                    ইসলাম বি.এসসি
                  </h4>
                </a>
              </div>
              <div class="flex items-center mt-4 border-t pt-4">
                <a href="" class="flex items-center space-x-2">
                  <img
                    class="w-1/3 h-auto"
                    src="https://royelnews.com/wp-content/uploads/2024/02/received_7083083735137742-600x337.jpeg"
                    alt=""
                    decoding="async"
                  />
                  <h4 class="text-sm font-medium text-black hover:text-red-600">
                    দৈনিক নাগরিক ভাবনা পত্রিকার ৪র্থ প্রতিষ্ঠা বার্ষিকী উদযাপন
                  </h4>
                </a>
              </div>
              <div class="flex items-center mt-4 border-t pt-4">
                <a href="" class="flex items-center space-x-2">
                  <img
                    class="w-1/3 h-auto"
                    src="https://royelnews.com/wp-content/uploads/2023/11/received_1007607633830713-600x337.jpeg"
                    alt=""
                    decoding="async"
                  />
                  <h4 class="text-sm font-medium text-black hover:text-red-600">
                    ঢাকা আহ্ছানিয়া মিশনের উদ্যোগে বেনাপোলে বিশ্ব টয়লেট দিবস ২০২৩
                    উদযাপন
                  </h4>
                </a>
              </div>
              <div class="flex items-center mt-4 border-t pt-4">
                <a href="" class="flex items-center space-x-2">
                  <img
                    class="w-1/3 h-auto"
                    src="https://royelnews.com/wp-content/uploads/2023/10/395711786_719079943577963_376892770646993724_n-1-600x337.jpg"
                    alt=""
                    decoding="async"
                  />
                  <h4 class="text-sm font-medium text-black hover:text-red-600">
                    উলিপুরে বাংলাদেশ জাতীয় হিন্দু মহাজোটের সহযোগীতা, শারোদীয়
                    দূর্গা উৎসব সম্পন্ন।
                  </h4>
                </a>
              </div>
            </div>
            <div class="bg-gray-100 p-4">
              <h4
                class="text-right text-[14px] text-gray-600 hover:text-green-600 flex justify-end items-center"
              >
                <a href="" class="flex items-center space-x-1">
                  <span>আরো সংবাদ..</span>
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 512 512"
                    class="w-3"
                  >
                    <path
                      fill="currentColor"
                      d="M470.6 278.6c12.5-12.5 12.5-32.8 0-45.3l-160-160c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3L402.7 256 265.4 393.4c-12.5 12.5-12.5 32.8 0 45.3s32.8 12.5 45.3 0l160-160zm-352 160l160-160c12.5-12.5 12.5-32.8 0-45.3l-160-160c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3L210.7 256 73.4 393.4c-12.5 12.5-12.5 32.8 0 45.3s32.8 12.5 45.3 0z"
                    />
                  </svg>
                </a>
              </h4>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!--  -->
    <!-- Tailwind CSS Navbar with Ads -->
    <div class="grid grid-cols-1 md:grid-cols-2 gap-4 mt-3">
      <!-- First ad -->
      <div class="flex justify-center md:justify-start">
        <img
          class="w-full max-w-md object-contain"
          src="https://royelnews.com/wp-content/uploads/2023/10/biggapon-1.gif"
          alt="Ad Image"
        />
      </div>

      <!-- Second ad -->
      <div class="flex justify-center md:justify-end">
        <img
          class="w-full max-w-md object-contain"
          src="https://royelnews.com/wp-content/uploads/2023/10/biggapon-1.gif"
          alt="Ad Image"
        />
      </div>
    </div>

    <!-- ধর্ম  -->
    <div class="flex gap-8">
      <!-- step one -->
      <div class="flex flex-col md:w-[633px]">
        <!-- Category Title -->
        <div class="mt-6">
          <div
            class="container mx-auto flex justify-between items-center bg-[#EDE9E9]"
          >
            <div
              class="siam w-1/6 md:w-1/3 px-2 py-2 inline-block bg-[#cc0000] text-white"
            >
              <a href="" class="flex items-center text-white">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 448 512"
                  class="w-5 h-5 mr-2"
                  fill="currentColor"
                >
                  <path
                    d="M0 96C0 78.3 14.3 64 32 64h384c17.7 0 32 14.3 32 32s-14.3 32-32 32H32C14.3 128 0 113.7 0 96zM0 256c0-17.7 14.3-32 32-32h384c17.7 0 32 14.3 32 32s-14.3 32-32 32H32c-17.7 0-32-14.3-32-32zM448 416c0 17.7-14.3 32-32 32H32c-17.7 0-32-14.3-32-32s14.3-32 32-32h384c17.7 0 32 14.3 32 32z"
                  />
                </svg>
                ধর্ম
              </a>
            </div>
          </div>
        </div>

        <!-- Article Box -->
        <div class="flex flex-wrap mt-3 gap-">
          <div class="w-full sm:w-1/2 md:w-1/2">
            <div class="mb-6">
              <div class="relative">
                <a href="">
                  <img
                    src="https://royelnews.com/wp-content/uploads/2023/10/395711786_719079943577963_376892770646993724_n-1-600x337.jpg"
                    alt="Main Article Image"
                    class="w-full h-auto"
                  />
                </a>
              </div>
              <div class="p-4">
                <h4 class="text-[16px] font-bold mb-2 border-b pb-2">
                  <a href="" class="text-gray-500 hover:text-blue-800">
                    উলিপুরে বাংলাদেশ জাতীয় হিন্দু মহাজোটের সহযোগীতা, শারোদীয়
                    দূর্গা উৎসব সম্পন্ন।
                  </a>
                </h4>
                <div class="mt-2">
                  ২০ অক্টো উলিপুরে বাংলাদেশ জাতীয় হিন্দু মহাজোটের সহযোগীতা,
                  শারোদীয় দূর্গা উৎসব
                  <span class="text-right">
                    <a href="https://royelnews.com/" class="text-blue-500"
                      >......বিস্তারিত</a
                    >
                  </span>
                </div>
              </div>
            </div>

            <div class="flex flex-wrap gap-3">
              <div class="w-full sm:w-[97px]">
                <div class="mb-6">
                  <a href="">
                    <img
                      class="w-full h-auto"
                      src="https://royelnews.com/wp-content/uploads/2023/10/inbound8594950081661160676.jpg"
                      alt="News image"
                    />
                  </a>
                  <div class="p-4">
                    <h4 class="text-lg font-bold">
                      <a
                        href=""
                        class="text-sm font-medium text-black hover:text-red-600"
                        >উলিপুরে হিন্দু মহাজোটের বিভিন্ন কর্মসূচি ও সহযোগীতায়
                        শারদীয় দূর্গা উৎসব পালিত।</a
                      >
                    </h4>
                  </div>
                </div>
              </div>

              <div class="w-full sm:w-[97px]">
                <div class="mb-">
                  <a href="">
                    <img
                      class="w-full h-auto"
                      src="https://royelnews.com/wp-content/uploads/2023/01/3-Copy-639-700x390-1.jpg"
                      alt="News image"
                    />
                  </a>
                  <div class="p-4">
                    <h4 class="text-lg font-bold">
                      <a
                        href=""
                        class="text-sm font-medium text-black hover:text-red-600"
                        >রাশিয়া ছেড়ে পালিয়েছেন সাবেক ওয়াগনার কমান্ডার</a
                      >
                    </h4>
                  </div>
                </div>
              </div>
            </div>
          </div>

          <div class="w-full sm:w-1/2 md:w-1/2">
            <div class="shadow-md p-4">
              <div class="flex items-center mt-4 pt-4">
                <a href="" class="flex items-center space-x-2">
                  <img
                    class="w-12 h-auto"
                    src="https://royelnews.com/wp-content/uploads/2023/01/3-Copy-638-700x390-1.jpg"
                    alt=""
                    decoding="async"
                  />
                  <h4 class="text-sm font-medium text-black hover:text-red-600">
                    ৬ দশকের মধ্যে সবচেয়ে কম জন্মহার চীনে!
                  </h4>
                </a>
              </div>

              <div class="flex items-center mt-4 border-t pt-4">
                <a href="" class="flex items-center space-x-2">
                  <img
                    class="w-12 h-auto"
                    src="https://royelnews.com/wp-content/uploads/2023/01/3-Copy-637-700x390-1.jpg"
                    alt=""
                    decoding="async"
                  />
                  <h4 class="text-sm font-medium text-black hover:text-red-600">
                    দ্বিতীয় বিয়ে করেছেন দাউদ ইব্রাহিম, স্ত্রী পাকিস্তানি’
                  </h4>
                </a>
              </div>

              <div class="flex items-center mt-4 border-t pt-4">
                <a href="" class="flex items-center space-x-2">
                  <img
                    class="w-12 h-auto"
                    src="https://royelnews.com/wp-content/uploads/2023/01/received_1503234363494888-581x337.jpeg"
                    alt=""
                    decoding="async"
                  />
                  <h4 class="text-sm font-medium text-black hover:text-red-600">
                    রৌমারীতে বীর মুক্তিযোদ্ধার মৃত্য রাষ্ট্রীয় মর্জাদায় দাফন
                  </h4>
                </a>
              </div>
              <div class="flex items-center mt-4 border-t pt-4">
                <a href="" class="flex items-center space-x-2">
                  <img
                    class="w-12 h-auto"
                    src="https://royelnews.com/wp-content/uploads/2022/12/received_3369899119930546-600x337.jpeg"
                    alt=""
                    decoding="async"
                  />
                  <h4 class="text-sm font-medium text-black hover:text-red-600">
                    থার্টি ফার্স্ট নাইট উদযাপন, ইসলাম কি বলে? |মুফতী সাইফ উদ্দীন
                    আল-আজাদ|
                  </h4>
                </a>
              </div>
              <div class="flex items-center mt-4 border-t pt-4">
                <a href="" class="flex items-center space-x-2">
                  <img
                    class="w-12 h-auto"
                    src="https://royelnews.com/wp-content/uploads/2022/12/received_478339027784806-600x337.jpeg"
                    alt=""
                    decoding="async"
                  />
                  <h4 class="text-sm font-medium text-black hover:text-red-600">
                    নাটোরের ভোক্তা-অধিকারের অভিযানে ২ হাজার কেজি গুড় জব্দ ও ২
                    লক্ষ টাকা জরিমানা
                  </h4>
                </a>
              </div>
              <div class="flex items-center mt-4 border-t pt-4">
                <a href="" class="flex items-center space-x-2">
                  <img
                    class="w-12 h-auto"
                    src="https://royelnews.com/wp-content/uploads/2022/12/received_568067688499501-600x337.jpeg"
                    alt=""
                    decoding="async"
                  />
                  <h4 class="text-sm font-medium text-black hover:text-red-600">
                    শার্শার লাউতাড়ায় তথ্য আপার উঠান বৈঠক
                  </h4>
                </a>
              </div>
            </div>
            <div class="bg-gray-100 p-4">
              <h4
                class="text-right text-[14px] text-gray-600 hover:text-green-600 flex justify-end items-center"
              >
                <a href="" class="flex items-center space-x-1">
                  <span>আরো সংবাদ..</span>
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 512 512"
                    class="w-3"
                  >
                    <path
                      fill="currentColor"
                      d="M470.6 278.6c12.5-12.5 12.5-32.8 0-45.3l-160-160c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3L402.7 256 265.4 393.4c-12.5 12.5-12.5 32.8 0 45.3s32.8 12.5 45.3 0l160-160zm-352 160l160-160c12.5-12.5 12.5-32.8 0-45.3l-160-160c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3L210.7 256 73.4 393.4c-12.5 12.5-12.5 32.8 0 45.3s32.8 12.5 45.3 0z"
                    />
                  </svg>
                </a>
              </h4>
            </div>
          </div>
        </div>
      </div>

      <!-- step two -->
      <div class="md:w-[355px] sm:w-12">
        <div class="mt-6">
          <div
            class="container mx-auto flex justify-between items-center bg-[#EDE9E9]"
          >
            <div
              class="siam w-1/6 md:w-1/2 px-2 py-2 inline-block bg-[#cc0000] text-white"
            >
              <a
                href="https://royelnews.com/category/%e0%a6%b8%e0%a6%be%e0%a6%b0%e0%a6%be%e0%a6%a6%e0%a7%87%e0%a6%b6/"
                class="flex items-center text-white"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 448 512"
                  class="w-5 h-5 mr-2"
                  fill="currentColor"
                >
                  <path
                    d="M0 96C0 78.3 14.3 64 32 64h384c17.7 0 32 14.3 32 32s-14.3 32-32 32H32C14.3 128 0 113.7 0 96zM0 256c0-17.7 14.3-32 32-32h384c17.7 0 32 14.3 32 32s-14.3 32-32 32H32c-17.7 0-32-14.3-32-32zM448 416c0 17.7-14.3 32-32 32H32c-17.7 0-32-14.3-32-32s14.3-32 32-32h384c17.7 0 32 14.3 32 32z"
                  />
                </svg>
                আর্ন্তজাতিক
              </a>
            </div>
          </div>
        </div>

        <!-- Article Section -->
        <div class="shadow-lg bg-white rounded-b-lg">
          <div class="mb-4 mt-3">
            <a href="">
              <img
                src="https://royelnews.com/wp-content/uploads/2023/10/395711786_719079943577963_376892770646993724_n-1-600x337.jpg"
                alt="Main Article Image"
                class="w-full h-auto"
              />
            </a>
            <div class="p-4">
              <h4 class="text-[16px] font-bold mb-2 border-b pb-2">
                <a href="" class="text-gray-500 hover:text-blue-800">
                  উলিপুরে বাংলাদেশ জাতীয় হিন্দু মহাজোটের সহযোগীতা, শারোদীয়
                  দূর্গা উৎসব সম্পন্ন।
                </a>
              </h4>

              <!-- Small Images Section -->

              <div class="flex items-center mt-4 border-t pt-4">
                <a href="" class="flex items-center space-x-2">
                  <img
                    class="w-1/3 h-auto"
                    src="https://royelnews.com/wp-content/uploads/2023/09/prothomalo-bangla_2021-11_8f79a823-5cec-48db-a67b-ef98317af490_P_1-600x337.webp"
                    alt=""
                    decoding="async"
                  />
                  <h4 class="text-sm font-medium text-black hover:text-red-600">
                    ফ্রান্সের প্রেসিডেন্ট আসছেন আজ, যা নিয়ে আলোচনা হতে পারে
                  </h4>
                </a>
              </div>

              <div class="flex items-center mt-4 border-t pt-4">
                <a href="" class="flex items-center space-x-2">
                  <img
                    class="w-1/3 h-auto"
                    src="https://royelnews.com/wp-content/uploads/2023/01/5-4-700x390-1.jpeg"
                    alt=""
                    decoding="async"
                  />
                  <h4 class="text-sm font-medium text-black hover:text-red-600">
                    জাপানে দুই সপ্তাহে ৫ হাজার করোনা রোগীর মৃত্যু
                  </h4>
                </a>
              </div>

              <div class="flex items-center mt-4 border-t pt-4">
                <a href="" class="flex items-center space-x-2">
                  <img
                    class="w-1/3 h-auto"
                    src="https://royelnews.com/wp-content/uploads/2023/01/3-Copy-641-700x390-1.jpg"
                    alt=""
                    decoding="async"
                  />
                  <h4 class="text-sm font-medium text-black hover:text-red-600">
                    সেদিন ওশিনকে কাজে যেতে নিষেধ করেছিলেন বাবা
                  </h4>
                </a>
              </div>

              <div class="flex items-center mt-4 border-t pt-4">
                <a href="" class="flex items-center space-x-2">
                  <img
                    class="w-1/3 h-auto"
                    src="https://royelnews.com/wp-content/uploads/2023/01/3-Copy-639-700x390-1.jpg"
                    alt=""
                    decoding="async"
                  />
                  <h4 class="text-sm font-medium text-black hover:text-red-600">
                    রাশিয়া ছেড়ে পালিয়েছেন সাবেক ওয়াগনার কমান্ডার
                  </h4>
                </a>
              </div>
            </div>
            <div class="bg-gray-100 p-4">
              <h4
                class="text-right text-[14px] text-gray-600 hover:text-green-600 flex justify-end items-center"
              >
                <a href="" class="flex items-center space-x-1">
                  <span>আরো সংবাদ..</span>
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 512 512"
                    class="w-3"
                  >
                    <path
                      fill="currentColor"
                      d="M470.6 278.6c12.5-12.5 12.5-32.8 0-45.3l-160-160c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3L402.7 256 265.4 393.4c-12.5 12.5-12.5 32.8 0 45.3s32.8 12.5 45.3 0l160-160zm-352 160l160-160c12.5-12.5 12.5-32.8 0-45.3l-160-160c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3L210.7 256 73.4 393.4c-12.5 12.5-12.5 32.8 0 45.3s32.8 12.5 45.3 0z"
                    />
                  </svg>
                </a>
              </h4>
            </div>
          </div>
        </div>
      </div>
      <!-- step three -->
      <div class="md:w-1/3 sm:w-1/3">
        <!-- Category Title -->
        <div class="mt-6">
          <div
            class="container mx-auto flex justify-between items-center bg-[#EDE9E9]"
          >
            <div
              class="siam w-1/6 md:w-1/3 px-2 py-2 inline-block bg-[#cc0000] text-white"
            >
              <a href="" class="flex items-center text-white">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 448 512"
                  class="w-5 h-5 mr-2"
                  fill="currentColor"
                >
                  <path
                    d="M0 96C0 78.3 14.3 64 32 64h384c17.7 0 32 14.3 32 32s-14.3 32-32 32H32C14.3 128 0 113.7 0 96zM0 256c0-17.7 14.3-32 32-32h384c17.7 0 32 14.3 32 32s-14.3 32-32 32H32c-17.7 0-32-14.3-32-32zM448 416c0 17.7-14.3 32-32 32H32c-17.7 0-32-14.3-32-32s14.3-32 32-32h384c17.7 0 32 14.3 32 32z"
                  />
                </svg>
                ধর্ম
              </a>
            </div>
          </div>
        </div>

        <!-- Article Section -->
        <div class="shadow-lg bg-white rounded-b-lg">
          <div class="mb-4 mt-3">
            <a href="">
              <img
                src="https://royelnews.com/wp-content/uploads/2023/10/395711786_719079943577963_376892770646993724_n-1-600x337.jpg"
                alt="Main Article Image"
                class="w-full h-auto"
              />
            </a>
            <div class="p-4">
              <h4 class="text-[16px] font-bold mb-2 border-b pb-2">
                <a href="" class="text-gray-500 hover:text-blue-800">
                  উলিপুরে বাংলাদেশ জাতীয় হিন্দু মহাজোটের সহযোগীতা, শারোদীয়
                  দূর্গা উৎসব সম্পন্ন।
                </a>
              </h4>

              <!-- Small Images Section -->

              <div class="flex items-center mt-4 border-t pt-4">
                <a href="" class="flex items-center space-x-2">
                  <img
                    class="w-1/3 h-auto"
                    src="https://royelnews.com/wp-content/uploads/2023/10/inbound8594950081661160676.jpg"
                    alt=""
                    decoding="async"
                  />
                  <h4 class="text-sm font-medium text-black hover:text-red-600">
                    উলিপুরে হিন্দু মহাজোটের বিভিন্ন কর্মসূচি ও সহযোগীতায় শারদীয়
                    দূর্গা উৎসব পালিত।
                  </h4>
                </a>
              </div>
              <div class="flex items-center mt-4 border-t pt-4">
                <a href="" class="flex items-center space-x-2">
                  <img
                    class="w-1/3 h-auto"
                    src="https://royelnews.com/wp-content/uploads/2023/01/3-Copy-639-700x390-1.jpg"
                    alt=""
                    decoding="async"
                  />
                  <h4 class="text-sm font-medium text-black hover:text-red-600">
                    রাশিয়া ছেড়ে পালিয়েছেন সাবেক ওয়াগনার কমান্ডার
                  </h4>
                </a>
              </div>
              <div class="flex items-center mt-4 border-t pt-4">
                <a href="" class="flex items-center space-x-2">
                  <img
                    class="w-1/3 h-auto"
                    src="https://royelnews.com/wp-content/uploads/2023/01/3-Copy-638-700x390-1.jpg"
                    alt=""
                    decoding="async"
                  />
                  <h4 class="text-sm font-medium text-black hover:text-red-600">
                    ৬ দশকের মধ্যে সবচেয়ে কম জন্মহার চীনে!
                  </h4>
                </a>
              </div>
              <div class="flex items-center mt-4 border-t pt-4">
                <a href="" class="flex items-center space-x-2">
                  <img
                    class="w-1/3 h-auto"
                    src="https://royelnews.com/wp-content/uploads/2023/01/3-Copy-637-700x390-1.jpg"
                    alt=""
                    decoding="async"
                  />
                  <h4 class="text-sm font-medium text-black hover:text-red-600">
                    দ্বিতীয় বিয়ে করেছেন দাউদ ইব্রাহিম, স্ত্রী পাকিস্তানি’
                  </h4>
                </a>
              </div>
            </div>
            <div class="bg-gray-100 p-4">
              <h4
                class="text-right text-[14px] text-gray-600 hover:text-green-600 flex justify-end items-center"
              >
                <a href="" class="flex items-center space-x-1">
                  <span>আরো সংবাদ..</span>
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 512 512"
                    class="w-3"
                  >
                    <path
                      fill="currentColor"
                      d="M470.6 278.6c12.5-12.5 12.5-32.8 0-45.3l-160-160c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3L402.7 256 265.4 393.4c-12.5 12.5-12.5 32.8 0 45.3s32.8 12.5 45.3 0l160-160zm-352 160l160-160c12.5-12.5 12.5-32.8 0-45.3l-160-160c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3L210.7 256 73.4 393.4c-12.5 12.5-12.5 32.8 0 45.3s32.8 12.5 45.3 0z"
                    />
                  </svg>
                </a>
              </h4>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!--  -->
    <div class="grid grid-cols-1 md:grid-cols-2 gap-4 mt-3">
      <div class="flex justify-center md:justify-start">
        <img
          class="w-full max-w-md object-contain"
          src="https://royelnews.com/wp-content/uploads/2023/10/biggapon-1.gif"
          alt="Ad Image"
        />
      </div>

      <!-- Second ad -->
      <div class="flex justify-center md:justify-end">
        <img
          class="w-full max-w-md object-contain"
          src="https://royelnews.com/wp-content/uploads/2023/10/biggapon-1.gif"
          alt="Ad Image"
        />
      </div>
    </div>
    <div class="mt-6">
      <div
        class="container mx-auto flex justify-between items-center bg-[#EDE9E9]"
      >
        <div
          class="siam w-1/6 md:w-1/7 px-2 py-2 inline-block bg-[#cc0000] text-white"
        >
          <a
            href="https://royelnews.com/category/%e0%a6%b8%e0%a6%be%e0%a6%b0%e0%a6%be%e0%a6%a6%e0%a7%87%e0%a6%b6/"
            class="flex items-center text-white"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 448 512"
              class="w-5 h-5 mr-2"
              fill="currentColor"
            >
              <path
                d="M0 96C0 78.3 14.3 64 32 64h384c17.7 0 32 14.3 32 32s-14.3 32-32 32H32C14.3 128 0 113.7 0 96zM0 256c0-17.7 14.3-32 32-32h384c17.7 0 32 14.3 32 32s-14.3 32-32 32H32c-17.7 0-32-14.3-32-32zM448 416c0 17.7-14.3 32-32 32H32c-17.7 0-32-14.3-32-32s14.3-32 32-32h384c17.7 0 32 14.3 32 32z"
              />
            </svg>
            আর্ন্তজাতিক
          </a>
        </div>
      </div>
    </div>
    <newSlider />
    <!-- banner -->
    <div class="flex flex-wrap">
      <div class="w-full md:w-1/2 p-2">
        <div class="bg-gray-100">
          <div class="widget_area">
            <div class="textwidget">
              <p>
                <img
                  class="w-full h-auto"
                  src="https://royelnews.com/wp-content/uploads/2022/12/banner-ads-hostitbd.jpg"
                  alt="Banner Ad"
                  srcset="
                    https://royelnews.com/wp-content/uploads/2022/12/banner-ads-hostitbd.jpg          2330w,
                    https://royelnews.com/wp-content/uploads/2022/12/banner-ads-hostitbd-300x50.jpg    300w,
                    https://royelnews.com/wp-content/uploads/2022/12/banner-ads-hostitbd-1024x169.jpg 1024w,
                    https://royelnews.com/wp-content/uploads/2022/12/banner-ads-hostitbd-768x127.jpg   768w,
                    https://royelnews.com/wp-content/uploads/2022/12/banner-ads-hostitbd-1536x254.jpg 1536w,
                    https://royelnews.com/wp-content/uploads/2022/12/banner-ads-hostitbd-2048x338.jpg 2048w
                  "
                  sizes="(max-width: 2330px) 100vw, 2330px"
                />
              </p>
            </div>
          </div>
        </div>
      </div>

      <div class="w-full md:w-1/2 p-2">
        <div class="bg-gray-100">
          <div class="widget_area">
            <div class="textwidget">
              <p>
                <img
                  class="w-full h-auto"
                  src="https://royelnews.com/wp-content/uploads/2022/12/banner-ads-hostitbd.jpg"
                  alt="Banner Ad"
                  srcset="
                    https://royelnews.com/wp-content/uploads/2022/12/banner-ads-hostitbd.jpg          2330w,
                    https://royelnews.com/wp-content/uploads/2022/12/banner-ads-hostitbd-300x50.jpg    300w,
                    https://royelnews.com/wp-content/uploads/2022/12/banner-ads-hostitbd-1024x169.jpg 1024w,
                    https://royelnews.com/wp-content/uploads/2022/12/banner-ads-hostitbd-768x127.jpg   768w,
                    https://royelnews.com/wp-content/uploads/2022/12/banner-ads-hostitbd-1536x254.jpg 1536w,
                    https://royelnews.com/wp-content/uploads/2022/12/banner-ads-hostitbd-2048x338.jpg 2048w
                  "
                  sizes="(max-width: 2330px) 100vw, 2330px"
                />
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- chakri -->
    <div class="mt-6">
      <div
        class="container mx-auto flex justify-between items-center bg-[#EDE9E9]"
      >
        <div
          class="siam w-[104px] md:w-1/7 px-2 py-2 inline-block bg-[#cc0000] text-white"
        >
          <a href="" class="flex items-center text-white">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 448 512"
              class="w-5 h-5 mr-2"
              fill="currentColor"
            >
              <path
                d="M0 96C0 78.3 14.3 64 32 64h384c17.7 0 32 14.3 32 32s-14.3 32-32 32H32C14.3 128 0 113.7 0 96zM0 256c0-17.7 14.3-32 32-32h384c17.7 0 32 14.3 32 32s-14.3 32-32 32H32c-17.7 0-32-14.3-32-32zM448 416c0 17.7-14.3 32-32 32H32c-17.7 0-32-14.3-32-32s14.3-32 32-32h384c17.7 0 32 14.3 32 32z"
              />
            </svg>
            চাকরি
          </a>
        </div>
      </div>
    </div>
    <!--  -->
    <div class="flex flex-wrap">
      <!-- First Column -->
      <div class="w-full sm:w-1/4 p-2">
        <!-- First News Item -->
        <div class="bg-white shadow-md">
          <div class="overflow-hidden">
            <a href="">
              <img
                class="w-full h-auto"
                src="https://royelnews.com/wp-content/uploads/2023/01/3-Copy-639-700x390-1.jpg"
                alt="News Image 1"
              />
            </a>
          </div>
          <div class="p-4">
            <h4 class="text-[16px] font-bold mb-2">
              <a href="" class="text-gray-500 hover:text-blue-800"
                >রাশিয়া ছেড়ে পালিয়েছেন সাবেক ওয়াগনার কমান্ডার</a
              >
            </h4>
          </div>
        </div>

        <!-- Second News Item -->
        <div class="bg-white shadow-md mt-4">
          <div class="overflow-hidden">
            <a href="">
              <img
                class="w-full h-auto"
                src="https://royelnews.com/wp-content/uploads/2023/01/3-Copy-638-700x390-1.jpg"
                alt="News Image 2"
              />
            </a>
          </div>
          <div class="p-4">
            <h4 class="text-[16px] font-bold mb-2">
              <a href="" class="text-gray-500 hover:text-blue-800"
                >৬ দশকের মধ্যে সবচেয়ে কম জন্মহার চীনে!</a
              >
            </h4>
          </div>
        </div>
      </div>

      <!-- Second Column -->
      <div class="w-full sm:w-1/2 p-2">
        <div class="bg-white shadow-md">
          <div class="overflow-hidden">
            <a href="">
              <img
                class="w-full h-auto"
                src="https://royelnews.com/wp-content/uploads/2023/10/395711786_719079943577963_376892770646993724_n-1-600x337.jpg"
                alt="News Image 3"
              />
            </a>
          </div>
          <div class="p-4">
            <h4 class="text-[18px] font-bold mb-2">
              <a href="" class="text-gray-500 hover:text-red-800"
                >উলিপুরে বাংলাদেশ জাতীয় হিন্দু মহাজোটের সহযোগীতা, শারোদীয় দূর্গা
                উৎসব সম্পন্ন।</a
              >
            </h4>
            <p class="text-gray-700">
              ২০ অক্টোউলিপুরে বাংলাদেশ জাতীয় হিন্দু মহাজোটের সহযোগীতা, শারোদীয়
              দূর্গা উৎসব সম্পন্ন। ২০ অক্টোবর ২০২৩ইং...
              <a href="https://royelnews.com/your-link-3" class="text-blue-600"
                >বিস্তারিত</a
              >
            </p>
          </div>
        </div>
      </div>

      <!-- Third Column -->
      <div class="w-full sm:w-1/4 p-2">
        <!-- Fourth News Item -->
        <div class="bg-white shadow-md">
          <div class="overflow-hidden">
            <a href="">
              <img
                class="w-full h-auto"
                src="https://royelnews.com/wp-content/uploads/2023/01/3-Copy-637-700x390-1.jpg"
                alt="News Image 4"
              />
            </a>
          </div>
          <div class="p-4">
            <h4 class="text-[16[px]] font-bold mb-2">
              <a href="" class="text-gray-500 hover:text-blue-800"
                >দ্বিতীয় বিয়ে করেছেন দাউদ ইব্রাহিম, স্ত্রী পাকিস্তানি</a
              >
            </h4>
          </div>
        </div>

        <!-- Fifth News Item -->
        <div class="bg-white shadow-md mt-4">
          <div class="overflow-hidden">
            <a href="">
              <img
                class="w-full h-auto"
                src="https://royelnews.com/wp-content/uploads/2022/12/322625132_719526586261443_2986189997021982751_n-600x337.jpg"
                alt="News Image 5"
              />
            </a>
          </div>
          <div class="p-4">
            <h4 class="text-[16px] font-bold mb-2">
              <a href="" class="text-gray-500 hover:text-blue-800"
                >রৌমারীতে আই,এফ,আই, সি, ব্যাংক উদ্বোধন</a
              >
            </h4>
          </div>
        </div>
      </div>
    </div>
    <!-- Second ad -->

    <div class="grid grid-cols-1 md:grid-cols-2 gap-4 mt-3">
      <div class="flex justify-center md:justify-start">
        <img
          class="w-full max-w-md object-contain"
          src="https://royelnews.com/wp-content/uploads/2023/10/biggapon-1.gif"
          alt="Ad Image"
        />
      </div>

      <div class="flex justify-center md:justify-end">
        <img
          class="w-full max-w-md object-contain"
          src="https://royelnews.com/wp-content/uploads/2023/10/biggapon-1.gif"
          alt="Ad Image"
        />
      </div>
    </div>

    <!--  -->
    <div class="mt-6">
      <div
        class="container mx-auto flex justify-between items-center bg-[#EDE9E9]"
      >
        <div
          class="siam w-[104px] md:w-1/7 px-2 py-2 inline-block bg-[#cc0000] text-white"
        >
          <a href="" class="flex items-center text-white">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 448 512"
              class="w-5 h-5 mr-2"
              fill="currentColor"
            >
              <path
                d="M0 96C0 78.3 14.3 64 32 64h384c17.7 0 32 14.3 32 32s-14.3 32-32 32H32C14.3 128 0 113.7 0 96zM0 256c0-17.7 14.3-32 32-32h384c17.7 0 32 14.3 32 32s-14.3 32-32 32H32c-17.7 0-32-14.3-32-32zM448 416c0 17.7-14.3 32-32 32H32c-17.7 0-32-14.3-32-32s14.3-32 32-32h384c17.7 0 32 14.3 32 32z"
              />
            </svg>
            চাকরি
          </a>
        </div>
      </div>
    </div>
    <!--  -->
    <slider />

    <!-- banner -->
    <div class="flex flex-wrap">
      <div class="w-full md:w-1/2 p-2">
        <div class="bg-gray-100">
          <div class="widget_area">
            <div class="textwidget">
              <p>
                <img
                  class="w-full h-auto"
                  src="https://royelnews.com/wp-content/uploads/2022/12/banner-ads-hostitbd.jpg"
                  alt="Banner Ad"
                  srcset="
                    https://royelnews.com/wp-content/uploads/2022/12/banner-ads-hostitbd.jpg          2330w,
                    https://royelnews.com/wp-content/uploads/2022/12/banner-ads-hostitbd-300x50.jpg    300w,
                    https://royelnews.com/wp-content/uploads/2022/12/banner-ads-hostitbd-1024x169.jpg 1024w,
                    https://royelnews.com/wp-content/uploads/2022/12/banner-ads-hostitbd-768x127.jpg   768w,
                    https://royelnews.com/wp-content/uploads/2022/12/banner-ads-hostitbd-1536x254.jpg 1536w,
                    https://royelnews.com/wp-content/uploads/2022/12/banner-ads-hostitbd-2048x338.jpg 2048w
                  "
                  sizes="(max-width: 2330px) 100vw, 2330px"
                />
              </p>
            </div>
          </div>
        </div>
      </div>

      <div class="w-full md:w-1/2 p-2">
        <div class="bg-gray-100">
          <div class="widget_area">
            <div class="textwidget">
              <p>
                <img
                  class="w-full h-auto"
                  src="https://royelnews.com/wp-content/uploads/2022/12/banner-ads-hostitbd.jpg"
                  alt="Banner Ad"
                  srcset="
                    https://royelnews.com/wp-content/uploads/2022/12/banner-ads-hostitbd.jpg          2330w,
                    https://royelnews.com/wp-content/uploads/2022/12/banner-ads-hostitbd-300x50.jpg    300w,
                    https://royelnews.com/wp-content/uploads/2022/12/banner-ads-hostitbd-1024x169.jpg 1024w,
                    https://royelnews.com/wp-content/uploads/2022/12/banner-ads-hostitbd-768x127.jpg   768w,
                    https://royelnews.com/wp-content/uploads/2022/12/banner-ads-hostitbd-1536x254.jpg 1536w,
                    https://royelnews.com/wp-content/uploads/2022/12/banner-ads-hostitbd-2048x338.jpg 2048w
                  "
                  sizes="(max-width: 2330px) 100vw, 2330px"
                />
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!--  -->
    <div class="flex gap-4">
      <!-- step one -->
      <div class="flex flex-col md:w-1/3">
        <!-- Category Title -->
        <div class="mt-3">
          <div
            class="container mx-auto flex justify-between items-center bg-[#EDE9E9]"
          >
            <div
              class="siam w-1/6 md:w-1/2 px-2 py-2 inline-block bg-[#cc0000] text-white"
            >
              <a href="" class="flex items-center text-white">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 448 512"
                  class="w-5 h-5 mr-2"
                  fill="currentColor"
                >
                  <path
                    d="M0 96C0 78.3 14.3 64 32 64h384c17.7 0 32 14.3 32 32s-14.3 32-32 32H32C14.3 128 0 113.7 0 96zM0 256c0-17.7 14.3-32 32-32h384c17.7 0 32 14.3 32 32s-14.3 32-32 32H32c-17.7 0-32-14.3-32-32zM448 416c0 17.7-14.3 32-32 32H32c-17.7 0-32-14.3-32-32s14.3-32 32-32h384c17.7 0 32 14.3 32 32z"
                  />
                </svg>
                সম্পাদকীয়
              </a>
            </div>
          </div>
        </div>

        <!-- Article Box -->
        <div class="shadow-lg mt-3">
          <!-- Image -->
          <div class="overflow-hidden">
            <a href="">
              <img
                class="w-full h-auto"
                src="https://royelnews.com/wp-content/uploads/2024/04/IMG-20240331-WA0012-1024x576-1-600x337.jpg"
                alt=""
              />
            </a>
          </div>

          <!-- Article Content -->
          <div class="p-4 shadow-lg bg-white rounded-b-lg">
            <h4 class="text-[16px] font-bold mb-2 border-b pb-2">
              <a href="" class="text-gray-500 hover:text-blue-800"
                >রৌমারীতে চেয়ারম্যানের কক্ষে তালা</a
              >
            </h4>

            <!-- Small Image and Title -->
            <div class="flex items-center mt-4 border-t pt-4">
              <a href="" class="flex items-center space-x-2">
                <img
                  class="w-1/3 h-auto"
                  src="https://royelnews.com/wp-content/uploads/2023/11/fgfs-2009060533-600x337.jpg"
                  alt=""
                />
                <h4 class="text-sm font-medium text-black hover:text-red-600">
                  ঘুষের টাকা ফেরত চাওয়ায় বাসায় ডেকে পেটালেন প্রতিমন্ত্রী জাকির
                  হোসেন
                </h4>
              </a>
            </div>
            <div class="flex items-center mt-4 border-t pt-4">
              <a href="" class="flex items-center space-x-2">
                <img
                  class="w-1/3 h-auto"
                  src="https://royelnews.com/wp-content/uploads/2023/10/395711786_719079943577963_376892770646993724_n-1-600x337.jpg"
                  alt=""
                  decoding="async"
                  srcset="
                    https://royelnews.com/wp-content/uploads/2023/01/3-Copy-638-700x390-1.jpg         700w,
                    https://royelnews.com/wp-content/uploads/2023/01/3-Copy-638-700x390-1-300x167.jpg 300w
                  "
                  sizes="(max-width: 600px) 100vw, 600px"
                />
                <h4 class="text-sm font-medium text-black hover:text-red-600">
                  উলিপুরে বাংলাদেশ জাতীয় হিন্দু মহাজোটের সহযোগীতা, শারোদীয়
                  দূর্গা উৎসব সম্পন্ন।
                </h4>
              </a>
            </div>

            <div class="flex items-center mt-4 border-t pt-4">
              <a href="" class="flex items-center space-x-2">
                <img
                  class="w-1/3 h-auto"
                  src="https://royelnews.com/wp-content/uploads/2023/01/3-Copy-639-700x390-1.jpg"
                  alt=""
                  decoding="async"
                  srcset="
                    https://royelnews.com/wp-content/uploads/2023/01/3-Copy-637-700x390-1.jpg         700w,
                    https://royelnews.com/wp-content/uploads/2023/01/3-Copy-637-700x390-1-300x167.jpg 300w
                  "
                  sizes="(max-width: 600px) 100vw, 600px"
                />
                <h4 class="text-sm font-medium text-black hover:text-red-600">
                  রাশিয়া ছেড়ে পালিয়েছেন সাবেক ওয়াগনার কমান্ডার
                </h4>
              </a>
            </div>

            <div class="flex items-center mt-4 border-t pt-4">
              <a href="" class="flex items-center space-x-2">
                <img
                  class="w-1/3 h-auto"
                  src="https://royelnews.com/wp-content/uploads/2023/01/3-Copy-638-700x390-1.jpg"
                  alt=""
                  decoding="async"
                />
                <h4 class="text-sm font-medium text-black hover:text-red-600">
                  ৬ দশকের মধ্যে সবচেয়ে কম জন্মহার চীনে!
                </h4>
              </a>
            </div>
            <div class="bg-gray-100 p-4 mt-5">
              <h4
                class="text-right text-[14px] text-gray-600 hover:text-green-600 flex justify-end items-center"
              >
                <a href="" class="flex items-center space-x-1">
                  <span>আরো সংবাদ..</span>
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 512 512"
                    class="w-3"
                  >
                    <path
                      fill="currentColor"
                      d="M470.6 278.6c12.5-12.5 12.5-32.8 0-45.3l-160-160c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3L402.7 256 265.4 393.4c-12.5 12.5-12.5 32.8 0 45.3s32.8 12.5 45.3 0l160-160zm-352 160l160-160c12.5-12.5 12.5-32.8 0-45.3l-160-160c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3L210.7 256 73.4 393.4c-12.5 12.5-12.5 32.8 0 45.3s32.8 12.5 45.3 0z"
                    />
                  </svg>
                </a>
              </h4>
            </div>
          </div>
        </div>
      </div>
      <!-- step two -->
      <div class="md:w-1/3 sm:w-1/3">
        <div class="mt-3">
          <div
            class="container mx-auto flex justify-between items-center bg-[#EDE9E9]"
          >
            <div
              class="siam w-1/6 md:w-1/2 px-2 py-2 inline-block bg-[#cc0000] text-white"
            >
              <a
                href="https://royelnews.com/category/%e0%a6%b8%e0%a6%be%e0%a6%b0%e0%a6%be%e0%a6%a6%e0%a7%87%e0%a6%b6/"
                class="flex items-center text-white"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 448 512"
                  class="w-5 h-5 mr-2"
                  fill="currentColor"
                >
                  <path
                    d="M0 96C0 78.3 14.3 64 32 64h384c17.7 0 32 14.3 32 32s-14.3 32-32 32H32C14.3 128 0 113.7 0 96zM0 256c0-17.7 14.3-32 32-32h384c17.7 0 32 14.3 32 32s-14.3 32-32 32H32c-17.7 0-32-14.3-32-32zM448 416c0 17.7-14.3 32-32 32H32c-17.7 0-32-14.3-32-32s14.3-32 32-32h384c17.7 0 32 14.3 32 32z"
                  />
                </svg>
                বিনোদন
              </a>
            </div>
          </div>
        </div>

        <!-- Article Section -->
        <div class="shadow-lg bg-white rounded-b-lg">
          <div class="mb-4 mt-3">
            <a href="">
              <img
                src="https://royelnews.com/wp-content/uploads/2024/05/IMG-20240503-WA0011-600x337.jpg"
                alt="Main Article Image"
                class="w-full h-auto"
              />
            </a>
            <div class="p-4">
              <h4 class="text-[16px] font-bold mb-2 border-b pb-2">
                <a href="" class="text-gray-500 hover:text-blue-800">
                  রাজশাহীতে বিশ্ব মুক্ত গণমাধ্যম দিবস পালন
                </a>
              </h4>

              <!-- Small Images Section -->

              <div class="flex items-center mt-4 border-t pt-4">
                <a href="" class="flex items-center space-x-2">
                  <img
                    class="w-1/3 h-auto"
                    src="https://royelnews.com/wp-content/uploads/2024/05/IMG-20240501-WA0038-600x337.jpg"
                    alt=""
                    decoding="async"
                  />
                  <h4 class="text-sm font-medium text-black hover:text-red-600">
                    রাজশাহীতে জাতীয় দৈনিক মানবিক বাংলাদেশ পত্রিকার প্রতিষ্ঠা
                    বার্ষিকী পালন
                  </h4>
                </a>
              </div>

              <div class="flex items-center mt-4 border-t pt-4">
                <a href="" class="flex items-center space-x-2">
                  <img
                    class="w-1/3 h-auto"
                    src="https://royelnews.com/wp-content/uploads/2023/10/395711786_719079943577963_376892770646993724_n-1-600x337.jpg"
                    alt=""
                    decoding="async"
                  />
                  <h4 class="text-sm font-medium text-black hover:text-red-600">
                    উলিপুরে বাংলাদেশ জাতীয় হিন্দু মহাজোটের সহযোগীতা, শারোদীয়
                    দূর্গা উৎসব সম্পন্ন।
                  </h4>
                </a>
              </div>

              <div class="flex items-center mt-4 border-t pt-4">
                <a href="" class="flex items-center space-x-2">
                  <img
                    class="w-1/3 h-auto"
                    src="https://royelnews.com/wp-content/uploads/2023/01/3-Copy-640-700x390-1.jpg"
                    alt=""
                    decoding="async"
                  />
                  <h4 class="text-sm font-medium text-black hover:text-red-600">
                    ইতালির কিংবদন্তি অভিনেত্রী জিনা লল্লব্রিজিদা আর নেই
                  </h4>
                </a>
              </div>

              <div class="flex items-center mt-4 border-t pt-4">
                <a href="" class="flex items-center space-x-2">
                  <img
                    class="w-1/3 h-auto"
                    src="https://royelnews.com/wp-content/uploads/2023/01/3-Copy-639-700x390-1.jpg"
                    alt=""
                    decoding="async"
                  />
                  <h4 class="text-sm font-medium text-black hover:text-red-600">
                    রাশিয়া ছেড়ে পালিয়েছেন সাবেক ওয়াগনার কমান্ডার
                  </h4>
                </a>
              </div>
            </div>
            <div class="bg-gray-100 p-4">
              <h4
                class="text-right text-[14px] text-gray-600 hover:text-green-600 flex justify-end items-center"
              >
                <a href="" class="flex items-center space-x-1">
                  <span>আরো সংবাদ..</span>
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 512 512"
                    class="w-3"
                  >
                    <path
                      fill="currentColor"
                      d="M470.6 278.6c12.5-12.5 12.5-32.8 0-45.3l-160-160c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3L402.7 256 265.4 393.4c-12.5 12.5-12.5 32.8 0 45.3s32.8 12.5 45.3 0l160-160zm-352 160l160-160c12.5-12.5 12.5-32.8 0-45.3l-160-160c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3L210.7 256 73.4 393.4c-12.5 12.5-12.5 32.8 0 45.3s32.8 12.5 45.3 0z"
                    />
                  </svg>
                </a>
              </h4>
            </div>
          </div>
        </div>
      </div>
      <!-- step three -->
      <div class="md:w-1/3 sm:w-1/3">
        <!-- Category Title -->
        <div class="mt-3">
          <div
            class="container mx-auto flex justify-between items-center bg-[#EDE9E9]"
          >
            <div
              class="siam w-1/6 md:w-1/2 px-2 py-2 inline-block bg-[#cc0000] text-white"
            >
              <a href="" class="flex items-center text-white">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 448 512"
                  class="w-5 h-5 mr-2"
                  fill="currentColor"
                >
                  <path
                    d="M0 96C0 78.3 14.3 64 32 64h384c17.7 0 32 14.3 32 32s-14.3 32-32 32H32C14.3 128 0 113.7 0 96zM0 256c0-17.7 14.3-32 32-32h384c17.7 0 32 14.3 32 32s-14.3 32-32 32H32c-17.7 0-32-14.3-32-32zM448 416c0 17.7-14.3 32-32 32H32c-17.7 0-32-14.3-32-32s14.3-32 32-32h384c17.7 0 32 14.3 32 32z"
                  />
                </svg>
                সারাদেশ
              </a>
            </div>
          </div>
        </div>

        <!-- Article Section -->
        <div class="shadow-lg bg-white rounded-b-lg">
          <div class="mb-4 mt-3">
            <a href="">
              <img
                src="https://royelnews.com/wp-content/uploads/2024/09/inbound1157982578839489462-600x337.jpg"
                alt="Main Article Image"
                class="w-full h-auto"
              />
            </a>
            <div class="p-4">
              <h4 class="text-[16px] font-bold mb-2 border-b pb-2">
                <a href="" class="text-gray-500 hover:text-blue-800">
                  উলিপুরে আশিক বাবুর কবর জিয়ারত করলেন ছাত্রদলের নেতারা
                </a>
              </h4>

              <!-- Small Images Section -->

              <div class="flex items-center mt-4 border-t pt-4">
                <a href="" class="flex items-center space-x-2">
                  <img
                    class="w-1/3 h-auto"
                    src="https://royelnews.com/wp-content/uploads/2024/09/IMG-20240905-WA0006-600x337.jpg"
                    alt=""
                    decoding="async"
                  />
                  <h4 class="text-sm font-medium text-black hover:text-red-600">
                    বন্যার্তদের জন্য জেলা প্রশাসকের হাতে ছাত্রদের নগদ অর্থ
                    প্রদান
                  </h4>
                </a>
              </div>
              <div class="flex items-center mt-4 border-t pt-4">
                <a href="" class="flex items-center space-x-2">
                  <img
                    class="w-1/3 h-auto"
                    src="https://royelnews.com/wp-content/uploads/2024/09/IMG-20240903-WA0016-600x337.jpg"
                    alt=""
                    decoding="async"
                  />
                  <h4 class="text-sm font-medium text-black hover:text-red-600">
                    জাল দলিলে জমি দখলের অভিযোগ সাবেক কাউন্সিলর পল্টুর বিরুদ্ধে
                  </h4>
                </a>
              </div>
              <div class="flex items-center mt-4 border-t pt-4">
                <a href="" class="flex items-center space-x-2">
                  <img
                    class="w-1/3 h-auto"
                    src="https://royelnews.com/wp-content/uploads/2024/09/received_2866279110191873-600x337.jpeg"
                    alt=""
                    decoding="async"
                  />
                  <h4 class="text-sm font-medium text-black hover:text-red-600">
                    বৈষম্যহীন, নিরাপদ, মানবিক বাংলাদেশ গড়ার প্রত্যয়ে জাতীয়তাবাদী
                    যুবদলের মতবিনিময় সভা অনুষ্ঠিত
                  </h4>
                </a>
              </div>
              <div class="flex items-center mt-4 border-t pt-4">
                <a href="" class="flex items-center space-x-2">
                  <img
                    class="w-1/3 h-auto"
                    src="https://royelnews.com/wp-content/uploads/2024/09/inbound4061881033680595033-600x337.jpg"
                    alt=""
                    decoding="async"
                  />
                  <h4 class="text-sm font-medium text-black hover:text-red-600">
                    মিরপুর কর্পোরেট অফিসে দারিদ্র বিমোচন জনকল্যাণ প্রকল্পের
                    কর্মী সমন্বয় সভা অনুষ্ঠিত
                  </h4>
                </a>
              </div>
            </div>
            <div class="bg-gray-100 p-4">
              <h4
                class="text-right text-[14px] text-gray-600 hover:text-green-600 flex justify-end items-center"
              >
                <a href="" class="flex items-center space-x-1">
                  <span>আরো সংবাদ..</span>
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 512 512"
                    class="w-3"
                  >
                    <path
                      fill="currentColor"
                      d="M470.6 278.6c12.5-12.5 12.5-32.8 0-45.3l-160-160c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3L402.7 256 265.4 393.4c-12.5 12.5-12.5 32.8 0 45.3s32.8 12.5 45.3 0l160-160zm-352 160l160-160c12.5-12.5 12.5-32.8 0-45.3l-160-160c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3L210.7 256 73.4 393.4c-12.5 12.5-12.5 32.8 0 45.3s32.8 12.5 45.3 0z"
                    />
                  </svg>
                </a>
              </h4>
            </div>
          </div>
        </div>
      </div>

      <!-- step four -->
      <div class="md:w-1/3 sm:w-1/3">
        <!-- Category Title -->
        <div class="mt-3">
          <div
            class="container mx-auto flex justify-between items-center bg-[#EDE9E9]"
          >
            <div
              class="siam w-1/6 md:w-[150px] px-2 py-2 inline-block bg-[#cc0000] text-white"
            >
              <a href="" class="flex items-center text-white">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 448 512"
                  class="w-5 h-5 mr-2"
                  fill="currentColor"
                >
                  <path
                    d="M0 96C0 78.3 14.3 64 32 64h384c17.7 0 32 14.3 32 32s-14.3 32-32 32H32C14.3 128 0 113.7 0 96zM0 256c0-17.7 14.3-32 32-32h384c17.7 0 32 14.3 32 32s-14.3 32-32 32H32c-17.7 0-32-14.3-32-32zM448 416c0 17.7-14.3 32-32 32H32c-17.7 0-32-14.3-32-32s14.3-32 32-32h384c17.7 0 32 14.3 32 32z"
                  />
                </svg>
                অন্যান্য
              </a>
            </div>
          </div>
        </div>

        <!-- Article Section -->
        <div class="shadow-lg bg-white rounded-b-lg">
          <div class="mb-4 mt-3">
            <a href="">
              <img
                src="https://royelnews.com/wp-content/uploads/2024/09/Messenger_creation_FA6B4541-DA4A-4413-BB68-1565381D23AD-600x337.jpeg"
                alt="Main Article Image"
                class="w-full h-auto"
              />
            </a>
            <div class="p-4">
              <h4 class="text-[16px] font-bold mb-2 border-b pb-2">
                <a href="" class="text-gray-500 hover:text-blue-800">
                  নাগেশ্বরীতে দুর্নীতির তথ্য সংগ্রহে বাধা প্রদানের অভিযোগ, কে এই
                  আঙ্গুর
                </a>
              </h4>

              <!-- Small Images Section -->

              <div class="flex items-center mt-4 border-t pt-4">
                <a href="" class="flex items-center space-x-2">
                  <img
                    class="w-1/3 h-auto"
                    src="https://royelnews.com/wp-content/uploads/2024/09/Rowmari-pic-02-09-24-022-600x337.jpg"
                    alt=""
                    decoding="async"
                  />
                  <h4 class="text-sm font-medium text-black hover:text-red-600">
                    রৌমারীতে সদস্য পরিচিত কার্ড বিতরণ
                  </h4>
                </a>
              </div>
              <div class="flex items-center mt-4 border-t pt-4">
                <a href="" class="flex items-center space-x-2">
                  <img
                    class="w-1/3 h-auto"
                    src="https://royelnews.com/wp-content/uploads/2024/02/received_7083083735137742-600x337.jpeg"
                    alt=""
                    decoding="async"
                  />
                  <h4 class="text-sm font-medium text-black hover:text-red-600">
                    দৈনিক নাগরিক ভাবনা পত্রিকার ৪র্থ প্রতিষ্ঠা বার্ষিকী উদযাপন
                  </h4>
                </a>
              </div>
              <div class="flex items-center mt-4 border-t pt-4">
                <a href="" class="flex items-center space-x-2">
                  <img
                    class="w-1/3 h-auto"
                    src="https://royelnews.com/wp-content/uploads/2024/09/inbound4061881033680595033-600x337.jpg"
                    alt=""
                    decoding="async"
                  />
                  <h4 class="text-sm font-medium text-black hover:text-red-600">
                    মিরপুর কর্পোরেট অফিসে দারিদ্র বিমোচন জনকল্যাণ প্রকল্পের
                    কর্মী সমন্বয় সভা অনুষ্ঠিত।
                  </h4>
                </a>
              </div>
              <div class="flex items-center mt-4 border-t pt-4">
                <a href="" class="flex items-center space-x-2">
                  <img
                    class="w-1/3 h-auto"
                    src="https://royelnews.com/wp-content/uploads/2024/08/IMG_20240831_1303523-600x337.jpg"
                    alt=""
                    decoding="async"
                  />
                  <h4 class="text-sm font-medium text-black hover:text-red-600">
                    রৌমারীতে যুব অধিকার পরিষদের ৪র্থ প্রতিষ্ঠা বার্ষিকী পালিত
                  </h4>
                </a>
              </div>
            </div>
            <div class="bg-gray-100 p-4">
              <h4
                class="text-right text-[14px] text-gray-600 hover:text-green-600 flex justify-end items-center"
              >
                <a href="" class="flex items-center space-x-1">
                  <span>আরো সংবাদ..</span>
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 512 512"
                    class="w-3"
                  >
                    <path
                      fill="currentColor"
                      d="M470.6 278.6c12.5-12.5 12.5-32.8 0-45.3l-160-160c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3L402.7 256 265.4 393.4c-12.5 12.5-12.5 32.8 0 45.3s32.8 12.5 45.3 0l160-160zm-352 160l160-160c12.5-12.5 12.5-32.8 0-45.3l-160-160c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3L210.7 256 73.4 393.4c-12.5 12.5-12.5 32.8 0 45.3s32.8 12.5 45.3 0z"
                    />
                  </svg>
                </a>
              </h4>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!--  -->
    <div class="grid grid-cols-1 md:grid-cols-2 gap-4 mt-3">
      <!-- First ad -->
      <div class="flex justify-center md:justify-start">
        <img
          class="w-full max-w-md object-contain"
          src="https://royelnews.com/wp-content/uploads/2023/10/biggapon-1.gif"
          alt="Ad Image"
        />
      </div>

      <!-- Second ad -->
      <div class="flex justify-center md:justify-end">
        <img
          class="w-full max-w-md object-contain"
          src="https://royelnews.com/wp-content/uploads/2023/10/biggapon-1.gif"
          alt="Ad Image"
        />
      </div>
    </div>
  </div>
</template>

<script setup>
import slider from "~/components/slider.vue";
import newSlider from "~/components/newSlider.vue";
import NewsSlider from "~/components/NewsSlider.vue";
import { ref } from "vue";

// Define your slides data
const slides = ref([
  {
    image:
      "https://royelnews.com/wp-content/uploads/2024/09/received_2866279110191873-600x337.jpeg",
    link: "https://royelnews.com/link1",
    caption:
      "বৈষম্যহীন, নিরাপদ, মানবিক বাংলাদেশ গড়ার প্রত্যয়ে জাতীয়তাবাদী যুবদলের মতবিনিময় সভা অনুষ্ঠিত",
  },
  {
    image:
      "https://royelnews.com/wp-content/uploads/2024/08/IMG-725101963-600x337.jpg",
    link: "https://royelnews.com/link2",
    caption: "প্রতিশোধ নয় দেশকে নতুন ভাবে গড়তে চাই জামায়াতে ইসলামী",
  },
  {
    image:
      "https://royelnews.com/wp-content/uploads/2024/08/IMG-20240819-WA0070-600x337.jpg",
    link: "https://royelnews.com/link3",
    caption:
      "রাজশাহীতে জাঁকজমক ভাবে স্বেচ্ছাসেবক দলের ৪৪তম প্রতিষ্ঠা বার্ষিকী পালন",
  },
  {
    image:
      "https://royelnews.com/wp-content/uploads/2024/08/IMG-20240817-WA0071-600x337.jpg",
    link: "https://royelnews.com/link4",
    caption: "রাজশাহীতে ভূমি দখল-চাঁদাবাজিতে জড়িত হলে আইনে সোপর্দ করুন- মিনু",
  },
]);

const currentIndex = ref(0);

function showSlide(index) {
  currentIndex.value = index;
}

function prevSlide() {
  currentIndex.value =
    currentIndex.value > 0 ? currentIndex.value - 1 : slides.value.length - 1;
}

function nextSlide() {
  currentIndex.value =
    currentIndex.value < slides.value.length - 1 ? currentIndex.value + 1 : 0;
}

//
</script>

<style scoped>
.menu-main-menu {
  font-size: 16px;
}

.carousel-item {
  transition: all 0.5s ease-in-out;
}
</style>
