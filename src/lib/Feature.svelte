<script>
  import aws from "../assets/aws.svg";
  import gcp from "../assets/gcp.svg";
  import azure from "../assets/azure.svg";
  import arrow from "../assets/arrow.svg";
</script>

<section class="text-gray-600 body-font">
  <div class="container px-5 py-24 mx-auto">
    <div class="text-center mb-20">
      <h1
        class="sm:text-3xl text-2xl font-medium title-font text-gray-900 mb-4"
      >
        Cloud Infrastructure
      </h1>
      <p
        class="text-base leading-relaxed xl:w-2/4 lg:w-3/4 mx-auto text-gray-500s"
      >
        Proficient with the Best Cloud Infrastructure providers
      </p>
      <div class="flex mt-6 justify-center">
        <div class="w-16 h-1 rounded-full bg-purple-500 inline-flex" />
      </div>
    </div>
    <div
      class="flex flex-wrap sm:-m-4 -mx-4 -mb-10 -mt-4 md:space-y-0 space-y-6"
    >
      <div class="p-4 md:w-1/3 flex flex-col text-center items-center">
        <div
          class="w-20 h-20 inline-flex items-center justify-center rounded-full bg-purple-100 text-purple-500 mb-5 flex-shrink-0"
        >
          <img src={aws} alt="" srcset="" />
        </div>
        <div class="flex-grow">
          <h2 class="text-gray-900 text-lg title-font font-medium mb-3">
            Amazon Web Services
          </h2>
          <p class="leading-relaxed text-base">
            The most popular cloud provider for startups and businesses with the
            best support for fexible infrastructure.
          </p>
          <a
            href="http://aws.amazon.com/"
            class="mt-3 text-purple-500 inline-flex items-center"
            >Learn More

            <img src={arrow} alt="" class="w-4 h-4 ml-1 text-purple-500" />
          </a>
        </div>
      </div>
      <div class="p-4 md:w-1/3 flex flex-col text-center items-center">
        <div
          class="w-20 h-20 inline-flex items-center justify-center rounded-full bg-purple-100 text-purple-500 mb-5 flex-shrink-0"
        >
          <img src={gcp} alt="" srcset="" />
        </div>
        <div class="flex-grow">
          <h2 class="text-gray-900 text-lg title-font font-medium mb-3">
            Google Cloud Platform
          </h2>
          <p class="leading-relaxed text-base">
            The Best cloud provider for Serverless applications with focus on
            the most cost-savings for businesses. Ideal option for startups with
            free credits from google.
          </p>
          <a
            href="http://cloud.google.com/"
            class="mt-3 text-purple-500 inline-flex items-center"
            >Learn More
            <img src={arrow} alt="" class="w-4 h-4 ml-1 text-purple-500" />
          </a>
        </div>
      </div>
      <div class="p-4 md:w-1/3 flex flex-col text-center items-center">
        <div
          class="w-20 h-20 inline-flex items-center justify-center rounded-full bg-purple-100 text-purple-500 mb-5 flex-shrink-0"
        >
          <img src={azure} alt="" srcset="" />
        </div>
        <div class="flex-grow">
          <h2 class="text-gray-900 text-lg title-font font-medium mb-3">
            Azure
          </h2>
          <p class="leading-relaxed text-base">
            The cloud platform with focus on government compliances and security
            regulations for enterprise operations. Best DevOps services with
            tight integrations with Github.
          </p>
          <a
            href="http://azure.microsoft.com"
            class="mt-3 text-purple-500 inline-flex items-center"
            >Learn More
            <img src={arrow} alt="" class="w-4 h-4 ml-1 text-purple-500" />
          </a>
        </div>
      </div>
    </div>
    <button
      class="flex mx-auto mt-16 text-white bg-purple-500 border-0 py-2 px-8 focus:outline-none hover:bg-purple-600 rounded text-lg"
      >Certifications</button
    >
  </div>
</section>
