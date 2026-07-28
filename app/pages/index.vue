<template>
  <main>
    <!-- Hero Section -->
    <section class="bg-pagebg py-[80px] px-[20px]">
      <div
        class="max-w-[1180px] mx-auto flex items-center justify-between gap-[20px] md:gap-[10px]"
      >
        <div class="flex-1">
          <h1 class="text-[38px] md:text-[52px] leading-[1.2] text-headhtext">
            Welcome to <span class="text-headhextra">MyWebsite</span>
          </h1>

          <p class="mt-[20px] text-[18px] text-gentext max-w-[550px]">
            We create modern digital solutions that help businesses grow,
            improve productivity, and connect with customers.
          </p>

          <div
            class="mt-[35px] flex max-md:flex-col max-md:items-center gap-[20px]"
          >
            <a
              href="#"
              class="px-[30px] py-[14px] rounded-lg no-underline font-bold bg-butcol text-buttext"
            >
              Get Started
            </a>

            <a
              href="#"
              class="px-[30px] py-[14px] rounded-lg no-underline font-bold border-2 border-butbor text-butbortext"
            >
              Learn More
            </a>
          </div>
        </div>

        <div class="w-[250px] md:w-[750px]">
          <img src="/images/image01.png" alt="" />
        </div>
      </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-[70px] px-[20px] text-center">
      <h2 class="text-headhtext text-[36px]">Our Services</h2>

      <div
        class="max-w-[1100px] mx-auto my-[40px] grid grid-cols-1 md:grid-cols-3 gap-[30px]"
      >
        <div
          class="bg-pagebg p-[35px] rounded-[15px] shadow-[0_5px_20px_rgba(0,0,0,0.08)]"
        >
          <h3 class="mb-[15px] text-sectionhead">Web Development</h3>
          <p>Modern responsive websites built with the latest technologies.</p>
        </div>

        <div
          class="bg-pagebg p-[35px] rounded-[15px] shadow-[0_5px_20px_rgba(0,0,0,0.08)]"
        >
          <h3 class="mb-[15px] text-sectionhead">IT Solutions</h3>
          <p>Reliable computer, networking, and business technology support.</p>
        </div>

        <div
          class="bg-pagebg p-[35px] rounded-[15px] shadow-[0_5px_20px_rgba(0,0,0,0.08)]"
        >
          <h3 class="mb-[15px] text-sectionhead">Cloud Services</h3>
          <p>Secure cloud solutions designed for today's businesses.</p>
        </div>
      </div>
    </section>

    <!-- About Section -->
    <section
      id="about"
      class="bg-headbg text-headtext py-[70px] px-[20px] text-center"
    >
      <div>
        <h2 class="text-[36px]">About Us</h2>

        <p class="max-w-[700px] mx-auto my-[20px] text-[18px]">
          We specialise in delivering reliable technology solutions with a focus
          on quality, security, and customer satisfaction.
        </p>
      </div>
    </section>

    <!-- Call To Action -->
    <section class="py-[70px] px-[20px] text-center">
      <h2 class="text-[36px] text-headhtext">
        Ready to start your next project?
      </h2>

      <p class="m-[20px]">Contact us today and let's build something great.</p>

      <a
        href="#"
        class="inline-block px-[30px] py-[14px] rounded-lg no-underline font-bold bg-butprimary text-white"
      >
        Contact Us
      </a>
    </section>
  </main>
</template>
