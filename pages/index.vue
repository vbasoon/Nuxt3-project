<template>
  <section class="text-gray-600 body-font">
    <h1 class="text-center font-bold text-2xl pt-4">Section 1</h1>
    <div
      class="container px-5 py-24 mx-auto flex flex-wrap border-red-500 border-2"
    >
      <div class="lg:w-2/3 mx-auto w-full">
        <div class="flex flex-wrap py-32 px-10 relative mb-4 border-green-500">
          <img
            alt="gallery"
            class="w-full object-cover h-full object-center block absolute inset-0 opacity-90"
            src="https://picsum.photos/600/300?random=1"
          />
          <div class="flex flex-col items-start z-10 text-white h-80 w-1/3">
            <p class="top-0 topic">Новости</p>
            <h2 class="title text-2xl font-medium title-font mb-2">
              Shooting Stars
            </h2>
            <p class="leading-relaxed text-red">
              Lorem ipsum dolor sit amet consectetur, adipisicing elit. Facere
              corrupti iste iure a deserunt nostrum praesentium, mollitia totam
              exercitationem eveniet ipsum? Facilis velit delectus ex amet.
              Deleniti similique eligendi atque magnam qui reiciendis expedita
              sit. Deserunt repellat optio, et, incidunt, ad vero atque dolores
              aut laborum sapiente aliquam quos iure.
            </p>
            <div class="flex w-full info text-white mt-10">
              <span class="mr-20">Author</span>
              <span>Time mark</span>
            </div>
          </div>
        </div>
        <div class="flex flex-wrap -mx-2">
          <div class="px-2 w-1/2">
            <div
              class="flex flex-wrap w-full sm:py-24 py-16 sm:px-10 px-6 relative"
            >
              <img
                alt="gallery"
                class="w-full object-cover h-full object-center block opacity-95 absolute inset-0"
                src="https://picsum.photos/600/300?random=2"
              />
              <div class="text-center relative z-10 w-full">
                <p class="top-0 topic">Истории</p>
                <h2 class="text-xl font-medium title-font mb-2 text-white">
                  Shooting Stars
                </h2>
                <p class="leading-relaxed text-white">
                  Skateboard +1 mustache fixie paleo lumbersexual.
                </p>
                <div class="flex justify-between mt-10 w-full info text-white">
                  <span class="mr-20">Author</span>
                  <span>Time mark</span>
                </div>
              </div>
            </div>
          </div>
          <div class="px-2 w-1/2">
            <div
              class="flex flex-wrap w-full sm:py-24 py-16 sm:px-10 px-6 relative"
            >
              <img
                alt="gallery"
                class="w-full object-cover h-full object-center block opacity-80 absolute inset-0"
                src="https://picsum.photos/600/300?random=3"
              />
              <div class="text-center relative z-10 w-full">
                <p class="top-0 topic">Блоги</p>
                <h2 class="text-xl text-white font-medium title-font mb-2">
                  Shooting Stars
                </h2>
                <p class="leading-relaxed text-white">
                  Skateboard +1 mustache fixie paleo lumbersexual.
                </p>
                <div class="flex justify-between mt-10 w-full info text-white">
                  <span class="mr-20">Author</span>
                  <span>Time mark</span>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
  <section class="text-gray-600 body-font">
    <h1 class="text-center font-bold text-2xl pt-4">Section 2</h1>
    <div
      class="container px-5 py-24 mx-auto flex flex-wrap border-red-500 border-2"
    >
      <div class="flex flex-wrap md:-m-2 -m-1">
        <div class="flex flex-wrap w-1/2">
          <div class="md:p-2 p-1 w-1/2">
            <img
              alt="gallery"
              class="w-full object-cover h-full object-center block"
              src="https://picsum.photos/600/300?random=1"
            />
          </div>
          <div class="md:p-2 p-1 w-1/2">
            <img
              alt="gallery"
              class="w-full object-cover h-full object-center block"
              src="https://picsum.photos/600/300?random=2"
            />
          </div>
          <div class="md:p-2 p-1 w-full">
            <img
              alt="gallery"
              class="w-full h-full object-cover object-center block"
              src="https://picsum.photos/600/300?random=3"
            />
          </div>
        </div>
        <div class="flex flex-wrap w-1/2">
          <div class="md:p-2 p-1 w-full">
            <img
              alt="gallery"
              class="w-full h-full object-cover object-center block"
              src="https://picsum.photos/600/300?random=4"
            />
          </div>
          <div class="md:p-2 p-1 w-1/2">
            <img
              alt="gallery"
              class="w-full object-cover h-full object-center block"
              src="https://picsum.photos/600/300?random=5"
            />
          </div>
          <div class="md:p-2 p-1 w-1/2">
            <img
              alt="gallery"
              class="w-full object-cover h-full object-center block"
              src="https://picsum.photos/600/300?random=6"
            />
          </div>
        </div>
      </div>
    </div>
  </section>
  <section class="text-gray-600 body-font">
    <h1 class="text-center font-bold text-2xl pt-4">Section 3</h1>
    <div class="container px-5 py-24 mx-auto border-red-500 border-2">
      <!-- component -->
      <!-- This is an example component -->
      <div class="max-w-2xl mx-auto">
        <div id="default-carousel" class="relative" data-carousel="static">
          <!-- Carousel wrapper -->
          <div
            class="overflow-hidden relative h-56 rounded-lg sm:h-64 xl:h-80 2xl:h-96"
          >
            <!-- Item 1 -->
            <div class="hidden duration-700 ease-in-out" data-carousel-item>
              <span
                class="absolute top-1/2 left-1/2 text-2xl font-semibold text-white -translate-x-1/2 -translate-y-1/2 sm:text-3xl dark:text-gray-800"
                >First Slide</span
              >
              <img
                src="https://flowbite.com/docs/images/carousel/carousel-1.svg"
                class="block absolute top-1/2 left-1/2 w-full -translate-x-1/2 -translate-y-1/2"
                alt="..."
              />
            </div>
            <!-- Item 2 -->
            <div class="hidden duration-700 ease-in-out" data-carousel-item>
              <img
                src="https://flowbite.com/docs/images/carousel/carousel-2.svg"
                class="block absolute top-1/2 left-1/2 w-full -translate-x-1/2 -translate-y-1/2"
                alt="..."
              />
            </div>
            <!-- Item 3 -->
            <div class="hidden duration-700 ease-in-out" data-carousel-item>
              <img
                src="https://flowbite.com/docs/images/carousel/carousel-3.svg"
                class="block absolute top-1/2 left-1/2 w-full -translate-x-1/2 -translate-y-1/2"
                alt="..."
              />
            </div>
          </div>
          <!-- Slider indicators -->
          <div
            class="flex absolute bottom-5 left-1/2 z-30 space-x-3 -translate-x-1/2"
          >
            <button
              type="button"
              class="w-3 h-3 rounded-full"
              aria-current="false"
              aria-label="Slide 1"
              data-carousel-slide-to="0"
            ></button>
            <button
              type="button"
              class="w-3 h-3 rounded-full"
              aria-current="false"
              aria-label="Slide 2"
              data-carousel-slide-to="1"
            ></button>
            <button
              type="button"
              class="w-3 h-3 rounded-full"
              aria-current="false"
              aria-label="Slide 3"
              data-carousel-slide-to="2"
            ></button>
          </div>
          <!-- Slider controls -->
          <button
            type="button"
            class="flex absolute top-0 left-0 z-30 justify-center items-center px-4 h-full cursor-pointer group focus:outline-none"
            data-carousel-prev
          >
            <span
              class="inline-flex justify-center items-center w-8 h-8 rounded-full sm:w-10 sm:h-10 bg-white/30 dark:bg-gray-800/30 group-hover:bg-white/50 dark:group-hover:bg-gray-800/60 group-focus:ring-4 group-focus:ring-white dark:group-focus:ring-gray-800/70 group-focus:outline-none"
            >
              <svg
                class="w-5 h-5 text-white sm:w-6 sm:h-6 dark:text-gray-800"
                fill="none"
                stroke="currentColor"
                viewBox="0 0 24 24"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M15 19l-7-7 7-7"
                ></path>
              </svg>
              <span class="hidden">Previous</span>
            </span>
          </button>
          <button
            type="button"
            class="flex absolute top-0 right-0 z-30 justify-center items-center px-4 h-full cursor-pointer group focus:outline-none"
            data-carousel-next
          >
            <span
              class="inline-flex justify-center items-center w-8 h-8 rounded-full sm:w-10 sm:h-10 bg-white/30 dark:bg-gray-800/30 group-hover:bg-white/50 dark:group-hover:bg-gray-800/60 group-focus:ring-4 group-focus:ring-white dark:group-focus:ring-gray-800/70 group-focus:outline-none"
            >
              <svg
                class="w-5 h-5 text-white sm:w-6 sm:h-6 dark:text-gray-800"
                fill="none"
                stroke="currentColor"
                viewBox="0 0 24 24"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M9 5l7 7-7 7"
                ></path>
              </svg>
              <span class="hidden">Next</span>
            </span>
          </button>
        </div>

        <p class="mt-5">
          This carousel slider component is part of a larger, open-source
          library of Tailwind CSS components. Learn more by going to the
          official
          <a
            class="text-blue-600 hover:underline"
            href="https://flowbite.com/docs/getting-started/introduction/"
            target="_blank"
            >Flowbite Documentation</a
          >.
        </p>
        <!-- <script src="https://unpkg.com/flowbite@1.4.0/dist/flowbite.js"></script> -->
      </div>
    </div>
  </section>
  <section class="text-gray-600 body-font">
    <h1 class="text-center font-bold text-2xl pt-4">Section 4</h1>
    <div class="container px-5 py-24 mx-auto border-red-500 border-2">
      <div class="flex flex-col text-center w-full mb-20">
        <h1
          class="sm:text-3xl text-2xl font-medium title-font mb-4 text-gray-900"
        >
          Master Cleanse Reliac Heirloom
        </h1>
        <p class="lg:w-2/3 mx-auto leading-relaxed text-base">
          Whatever cardigan tote bag tumblr hexagon brooklyn asymmetrical
          gentrify, subway tile poke farm-to-table. Franzen you probably haven't
          heard of them man bun deep jianbing selfies heirloom.
        </p>
      </div>
      <div class="flex flex-wrap -m-4">
        <div class="lg:w-1/3 sm:w-1/2 p-4">
          <div class="flex relative">
            <img
              alt="gallery"
              class="absolute inset-0 w-full h-full object-cover object-center"
              src="https://picsum.photos/600/300?random=1"
            />
            <div
              class="px-8 py-10 relative z-10 w-full border-4 border-gray-200 bg-white opacity-0 hover:opacity-100"
            >
              <h2
                class="tracking-widest text-sm title-font font-medium text-indigo-500 mb-1"
              >
                THE SUBTITLE
              </h2>
              <h1 class="title-font text-lg font-medium text-gray-900 mb-3">
                Shooting Stars
              </h1>
              <p class="leading-relaxed">
                Photo booth fam kinfolk cold-pressed sriracha leggings jianbing
                microdosing tousled waistcoat.
              </p>
            </div>
          </div>
        </div>
        <div class="lg:w-1/3 sm:w-1/2 p-4">
          <div class="flex relative">
            <img
              alt="gallery"
              class="absolute inset-0 w-full h-full object-cover object-center"
              src="https://picsum.photos/600/300?random=2"
            />
            <div
              class="px-8 py-10 relative z-10 w-full border-4 border-gray-200 bg-white opacity-0 hover:opacity-100"
            >
              <h2
                class="tracking-widest text-sm title-font font-medium text-indigo-500 mb-1"
              >
                THE SUBTITLE
              </h2>
              <h1 class="title-font text-lg font-medium text-gray-900 mb-3">
                The Catalyzer
              </h1>
              <p class="leading-relaxed">
                Photo booth fam kinfolk cold-pressed sriracha leggings jianbing
                microdosing tousled waistcoat.
              </p>
            </div>
          </div>
        </div>
        <div class="lg:w-1/3 sm:w-1/2 p-4">
          <div class="flex relative">
            <img
              alt="gallery"
              class="absolute inset-0 w-full h-full object-cover object-center"
              src="https://picsum.photos/600/300?random=3"
            />
            <div
              class="px-8 py-10 relative z-10 w-full border-4 border-gray-200 bg-white opacity-0 hover:opacity-100"
            >
              <h2
                class="tracking-widest text-sm title-font font-medium text-indigo-500 mb-1"
              >
                THE SUBTITLE
              </h2>
              <h1 class="title-font text-lg font-medium text-gray-900 mb-3">
                The 400 Blows
              </h1>
              <p class="leading-relaxed">
                Photo booth fam kinfolk cold-pressed sriracha leggings jianbing
                microdosing tousled waistcoat.
              </p>
            </div>
          </div>
        </div>
        <div class="lg:w-1/3 sm:w-1/2 p-4">
          <div class="flex relative">
            <img
              alt="gallery"
              class="absolute inset-0 w-full h-full object-cover object-center"
              src="https://picsum.photos/600/300?random=4"
            />
            <div
              class="px-8 py-10 relative z-10 w-full border-4 border-gray-200 bg-white opacity-0 hover:opacity-100"
            >
              <h2
                class="tracking-widest text-sm title-font font-medium text-indigo-500 mb-1"
              >
                THE SUBTITLE
              </h2>
              <h1 class="title-font text-lg font-medium text-gray-900 mb-3">
                Neptune
              </h1>
              <p class="leading-relaxed">
                Photo booth fam kinfolk cold-pressed sriracha leggings jianbing
                microdosing tousled waistcoat.
              </p>
            </div>
          </div>
        </div>
        <div class="lg:w-1/3 sm:w-1/2 p-4">
          <div class="flex relative">
            <img
              alt="gallery"
              class="absolute inset-0 w-full h-full object-cover object-center"
              src="https://picsum.photos/600/300?random=5"
            />
            <div
              class="px-8 py-10 relative z-10 w-full border-4 border-gray-200 bg-white opacity-0 hover:opacity-100"
            >
              <h2
                class="tracking-widest text-sm title-font font-medium text-indigo-500 mb-1"
              >
                THE SUBTITLE
              </h2>
              <h1 class="title-font text-lg font-medium text-gray-900 mb-3">
                Holden Caulfield
              </h1>
              <p class="leading-relaxed">
                Photo booth fam kinfolk cold-pressed sriracha leggings jianbing
                microdosing tousled waistcoat.
              </p>
            </div>
          </div>
        </div>
        <div class="lg:w-1/3 sm:w-1/2 p-4">
          <div class="flex relative">
            <img
              alt="gallery"
              class="absolute inset-0 w-full h-full object-cover object-center"
              src="https://picsum.photos/600/300?random=6"
            />
            <div
              class="px-8 py-10 relative z-10 w-full border-4 border-gray-200 bg-white opacity-0 hover:opacity-100"
            >
              <h2
                class="tracking-widest text-sm title-font font-medium text-indigo-500 mb-1"
              >
                THE SUBTITLE
              </h2>
              <h1 class="title-font text-lg font-medium text-gray-900 mb-3">
                Alper Kamu
              </h1>
              <p class="leading-relaxed">
                Photo booth fam kinfolk cold-pressed sriracha leggings jianbing
                microdosing tousled waistcoat.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style></style>
