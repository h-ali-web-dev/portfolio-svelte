<script>
  import react from "../assets/react.svg";
  import vue from "../assets/vue.svg";
  import svelte from "../assets/svelte.svg";
  import flutter from "../assets/flutter.svg";
</script>

<section class="text-gray-600 body-font" id="frontend">
  <div class="container px-5 py-24 mx-auto">
    <div class="text-center mb-20">
      <h1
        class="sm:text-3xl text-2xl font-medium title-font text-gray-900 mb-4"
      >
        Front-End Development
      </h1>
      <p
        class="text-base leading-relaxed xl:w-2/4 lg:w-3/4 mx-auto text-gray-500s"
      >
        Beautiful and User Engaging User Interfaces
      </p>
      <div class="flex mt-6 justify-center">
        <div class="w-16 h-1 rounded-full bg-purple-500 inline-flex" />
      </div>
    </div>
    <div
      class="flex sm:flex-row flex-col sm:-m-4 -mb-10 -mt-4 md:space-y-0 space-y-6 mx-auto"
    >
      <div class="p-4 md:w-1/4 flex flex-col text-center items-center">
        <div
          class="w-20 h-20 inline-flex items-center justify-center rounded-full bg-purple-100 text-purple-500 mb-5 flex-shrink-0"
        >
          <img src={react} alt="" srcset="" />
        </div>
        <div class="flex-grow">
          <h2 class="text-gray-900 text-lg title-font font-medium mb-3">
            React
          </h2>
        </div>
      </div>
      <div class="p-4 md:w-1/4 flex flex-col text-center items-center">
        <div
          class="w-20 h-20 inline-flex items-center justify-center rounded-full bg-purple-100 text-purple-500 mb-5 flex-shrink-0"
        >
          <img src={vue} alt="" srcset="" />
        </div>
        <div class="flex-grow">
          <h2 class="text-gray-900 text-lg title-font font-medium mb-3">Vue</h2>
        </div>
      </div>
      <div class="p-4 md:w-1/4 flex flex-col text-center items-center">
        <div
          class="w-20 h-20 inline-flex items-center justify-center rounded-full bg-purple-100 text-purple-500 mb-5 flex-shrink-0"
        >
          <img src={svelte} alt="" srcset="" />
        </div>
        <div class="flex-grow">
          <h2 class="text-gray-900 text-lg title-font font-medium mb-3">
            Svelte
          </h2>
        </div>
      </div>
      <div class="p-4 md:w-1/4 flex flex-col text-center items-center">
        <div
          class="w-20 h-20 inline-flex items-center justify-center rounded-full bg-purple-100 text-purple-500 mb-5 flex-shrink-0"
        >
          <img src={flutter} alt="" srcset="" />
        </div>
        <div class="flex-grow">
          <h2 class="text-gray-900 text-lg title-font font-medium mb-3">
            Flutter
          </h2>
        </div>
      </div>
    </div>
  </div>
</section>
