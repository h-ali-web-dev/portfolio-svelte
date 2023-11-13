<script>
  import golang from "../assets/golang.svg";
  import nodejs from "../assets/nodejs.svg";
  import python from "../assets/python.svg";
</script>

<section class="text-gray-600 body-font" id="backend">
  <div class="container px-5 py-24 mx-auto">
    <div class="text-center mb-20">
      <h1
        class="sm:text-3xl text-2xl font-medium title-font text-gray-900 mb-4"
      >
        Back-End Development
      </h1>
      <p
        class="text-base leading-relaxed xl:w-2/4 lg:w-3/4 mx-auto text-gray-500s"
      >
        Fast & Efficient APIs with Database Integrations
      </p>
      <div class="flex mt-6 justify-center">
        <div class="w-16 h-1 rounded-full bg-purple-500 inline-flex" />
      </div>
    </div>
    <div
      class="flex sm:flex-row flex-col sm:-m-4 -mb-10 -mt-4 md:space-y-0 space-y-6 mx-auto"
    >
      <div class="p-4 md:w-1/3 flex flex-col text-center items-center">
        <div
          class="w-20 h-20 inline-flex items-center justify-center rounded-full bg-purple-100 text-purple-500 mb-5 flex-shrink-0"
        >
          <img src={golang} alt="" srcset="" />
        </div>
        <div class="flex-grow">
          <h2 class="text-gray-900 text-lg title-font font-medium mb-3">GO</h2>
        </div>
      </div>
      <div class="p-4 md:w-1/3 flex flex-col text-center items-center">
        <div
          class="w-20 h-20 inline-flex items-center justify-center rounded-full bg-purple-100 text-purple-500 mb-5 flex-shrink-0"
        >
          <img src={nodejs} alt="" srcset="" />
        </div>
        <div class="flex-grow">
          <h2 class="text-gray-900 text-lg title-font font-medium mb-3">
            Node.js
          </h2>
        </div>
      </div>
      <div class="p-4 md:w-1/3 flex flex-col text-center items-center">
        <div
          class="w-20 h-20 inline-flex items-center justify-center rounded-full bg-purple-100 text-purple-500 mb-5 flex-shrink-0"
        >
          <img src={python} alt="" srcset="" />
        </div>
        <div class="flex-grow">
          <h2 class="text-gray-900 text-lg title-font font-medium mb-3">
            Python
          </h2>
        </div>
      </div>
    </div>
  </div>
</section>
