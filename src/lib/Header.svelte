<script>
  import infrastructure from "../assets/infrastructure.svg";
  import arrowDouble from "../assets/arrowDouble.svg";
</script>

<header
  class="text-gray-600 body-font sticky top-0 bg-opacity-60 bg-gradient-to-b from-white from-60% to-transparent"
>
  <div
    class="container mx-auto flex flex-wrap p-5 flex-col md:flex-row items-center"
  >
    <a
      href="#top"
      class="flex title-font font-medium items-center text-gray-900 mb-4 md:mb-0"
    >
      <img
        src={infrastructure}
        alt=""
        class="w-10 h-10 text-white p-2 bg-purple-400 rounded-full"
      />
      <span class="ml-3 text-xl">Hammad Ali</span>
    </a>
    <nav
      class="md:mr-auto md:ml-4 md:py-1 md:pl-4 md:border-l md:border-gray-400 flex flex-wrap items-center text-base justify-center"
    >
      <a href="#cloud" class="mr-5 hover:text-gray-900">Cloud</a>
      <a href="#certifications" class="mr-5 hover:text-gray-900"
        >Certifications</a
      >
      <a href="#frontend" class="mr-5 hover:text-gray-900"
        >Front-End Development</a
      >
      <a href="#backend" class="mr-5 hover:text-gray-900"
        >Back-End Development</a
      >
    </nav>
    <a
      href="#footerId"
      class="inline-flex items-center bg-gray-100 border-0 py-1 px-3 focus:outline-none hover:bg-gray-200 rounded text-base mt-4 md:mt-0"
      >Contact
      <img src={arrowDouble} alt="" class="w-4 h-4 ml-1 mt-0.5" />
    </a>
  </div>
</header>
