<script>
  import linkedin from "../assets/linkedin.svg";
  import gmail from "../assets/gmail.svg";
  import github from "../assets/github.svg";
  import infrastructure from "../assets/infrastructure.svg";
</script>

<footer class="text-gray-600 body-font" id="footerId">
  <div
    class="container px-5 py-8 mx-auto flex items-center sm:flex-row flex-col"
  >
    <a
      href="#top"
      class="flex title-font font-medium items-center md:justify-start justify-center text-gray-900"
    >
      <img
        src={infrastructure}
        alt=""
        class="w-10 h-10 text-white p-2 bg-purple-400 rounded-full"
      />
      <span class="ml-3 text-xl">Hammad Ali</span>
    </a>
    <p
      class="text-sm text-gray-500 sm:ml-4 sm:pl-4 sm:border-l-2 sm:border-gray-200 sm:py-2 sm:mt-0 mt-4"
    >
      © {new Date().getFullYear()} Hammad
    </p>
    <span
      class="inline-flex sm:ml-auto sm:mt-0 mt-4 justify-center sm:justify-start"
    >
      <a
        href="https://github.com/h-ali-web-dev"
        class="ml-3 text-gray-500 flex flex-row items-center"
      >
        <img src={github} alt="" class="w-5 h-5" />
        <div class="hidden sm:block">GitHub</div>
      </a>
      <a
        href="mailto:hammadali965@gmail.com"
        class="ml-3 text-gray-500 flex flex-row items-center"
      >
        <img src={gmail} alt="" class=" h-5" />
        <div class="hidden sm:block">Gmail</div>
      </a>
      <a
        href="https://www.linkedin.com/in/hammad-ali-1bb21b160/"
        class="ml-3 text-gray-500 flex flex-row items-center"
      >
        <img src={linkedin} alt="" class="w-5 h-5" />
        <div class="hidden sm:block">LinkedIn</div>
      </a>
    </span>
  </div>
</footer>
