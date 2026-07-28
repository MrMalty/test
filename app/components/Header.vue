<template>
  <header
    class="w-full bg-headbg text-headtext shadow-[0_3px_10px_rgba(0,0,0,0.15)]"
  >
    <div
      class="mx-auto h-[120px] flex justify-between items-center max-w-[1280px] max-md:flex-col max-md:h-auto max-md:p-5"
    >
      <a
        href="/"
        class="text-[30px] font-bold text-headtext no-underline w-[380px]"
        ><img src="/images/logo.png"
      /></a>

      <nav class="flex list-none gap-[35px]">
        <ul class="flex list-none gap-[35px]">
          <li>
            <a
              class="no-underline text-headtext text-base font-medium transition-colors duration-300 relative hover:text-headtexth relative after:content-[''] after:absolute after:left-0 after:-bottom-2 after:w-0 after:h-[2px] after:bg-headtexth after:transition-all after:duration-300 hover:after:w-full"
              href="/"
              >Home</a
            >
          </li>
          <li>
            <a
              class="no-underline text-headtext text-base font-medium transition-colors duration-300 relative hover:text-headtexth relative after:content-[''] after:absolute after:left-0 after:-bottom-2 after:w-0 after:h-[2px] after:bg-headtexth after:transition-all after:duration-300 hover:after:w-full"
              href="/#about"
              >About</a
            >
          </li>
          <li>
            <a
              class="no-underline text-headtext text-base font-medium transition-colors duration-300 relative hover:text-headtexth relative after:content-[''] after:absolute after:left-0 after:-bottom-2 after:w-0 after:h-[2px] after:bg-headtexth after:transition-all after:duration-300 hover:after:w-full"
              href="/#services"
              >Services</a
            >
          </li>
          <li>
            <a
              class="no-underline text-headtext text-base font-medium transition-colors duration-300 relative hover:text-headtexth relative after:content-[''] after:absolute after:left-0 after:-bottom-2 after:w-0 after:h-[2px] after:bg-headtexth after:transition-all after:duration-300 hover:after:w-full"
              href="/portfolio"
              >Portfolio</a
            >
          </li>
          <li>
            <a
              class="no-underline text-headtext text-base font-medium transition-colors duration-300 relative hover:text-headtexth relative after:content-[''] after:absolute after:left-0 after:-bottom-2 after:w-0 after:h-[2px] after:bg-headtexth after:transition-all after:duration-300 hover:after:w-full"
              href="#"
              >Contact</a
            >
          </li>
        </ul>
      </nav>
    </div>
  </header>
</template>
