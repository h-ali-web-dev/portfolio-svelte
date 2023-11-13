<script>
  import gcp from "../assets/gcp.svg";
  import heroImg from "../assets/heroImage.jpg";
</script>

<section class="text-gray-600 body-font">
  <div
    class="container mx-auto flex px-5 py-24 md:flex-row flex-col items-center"
  >
    <div class="lg:max-w-lg lg:w-full md:w-1/2 w-5/6 mb-10 md:mb-0">
      <img
        class="object-cover object-center rounded"
        alt="hero"
        src={heroImg}
      />
    </div>
    <div
      class="lg:flex-grow md:w-1/2 lg:pl-24 md:pl-16 flex flex-col md:items-start md:text-left items-center text-center"
    >
      <h1
        class="title-font sm:text-4xl text-3xl mb-4 font-medium text-gray-900"
      >
        Certified GCP Cloud Engineer &
        <br class="hidden lg:inline-block" />Full-Stack Developer
      </h1>
      <p class="mb-8 leading-relaxed">
        Certified Developer for provisioning Cloud Infrasructure and develop
        cloud native applications with focus on cost savings and scalibility.
      </p>
      <div class="flex justify-center">
        <a
          href="#cloud"
          class="inline-flex text-white bg-purple-500 border-0 py-2 px-6 focus:outline-none hover:bg-purple-600 rounded text-lg"
          >See Cloud Providers</a
        >
        <a
          href="#certifications"
          class="ml-4 inline-flex text-gray-700 bg-gray-100 border-0 py-2 px-6 focus:outline-none hover:bg-gray-200 rounded text-lg"
          >See My Certifications</a
        >
      </div>
    </div>
  </div>
</section>
