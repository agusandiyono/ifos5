<template>
  <div>
  <!-- ====== Navbar Section Start -->
    <div
      class="ud-header absolute top-0 left-0 z-40 flex w-full items-center bg-white shadow-lg"
    >
      <div class="container">
        <div class="relative -mx-4 flex items-center justify-between">
          <div class="w-60 max-w-full">
            <a href="index.html" class="navbar-logo block w-full py-5">
              <img class="header-logo w-32" src="logokecil.png">
            </a>
          </div>
          <div class="flex w-full items-center justify-end px-4">
            <div>
              <button
                id="navbarToggler"
                class="absolute right-4 top-1/2 block -translate-y-1/2 rounded-lg px-3 py-[6px] ring-primary focus:ring-2 lg:hidden"
              >
                <span
                  class="relative my-[6px] block h-[2px] w-[30px] bg-white"
                ></span>
                <span
                  class="relative my-[6px] block h-[2px] w-[30px] bg-white"
                ></span>
                <span
                  class="relative my-[6px] block h-[2px] w-[30px] bg-white"
                ></span>
              </button>
              <nav
                id="navbarCollapse"
                class="absolute right-4 top-full hidden w-full max-w-[250px] rounded-lg bg-white py-5 shadow-lg lg:static lg:block lg:w-full lg:max-w-full lg:bg-transparent lg:py-0 lg:px-4 lg:shadow-none xl:px-6"
              >
                <ul class="blcok lg:flex">
                  <!-- <li class="group relative">
                    <a
                      href="#home"
                      class="ud-menu-scroll mx-8 flex py-2 text-base text-dark group-hover:text-green-600 lg:mr-0 lg:inline-flex lg:py-6 lg:px-0 lg:text-gray lg:group-hover:text-gray lg:group-hover:opacity-70"
                    >
                      Beranda
                    </a>
                  </li> -->
                  <li class="group relative">
                    <a
                      href="/#sponsor"
                      class="ud-menu-scroll mx-8 flex py-2 text-base text-dark group-hover:text-green-600 lg:mr-0 lg:ml-7 lg:inline-flex lg:py-6 lg:px-0 lg:text-gray lg:group-hover:text-gray lg:group-hover:opacity-70 xl:ml-12"
                    >
                      Support
                    </a>
                  </li>
                  <li class="group relative">
                    <a
                      href="/#lomba"
                      class="ud-menu-scroll mx-8 flex py-2 text-base text-dark group-hover:text-green-600 lg:mr-0 lg:ml-7 lg:inline-flex lg:py-6 lg:px-0 lg:text-gray lg:group-hover:text-gray lg:group-hover:opacity-70 xl:ml-12"
                    >
                      Lomba
                    </a>
                  </li>
                  <li class="group relative">
                    <a
                      href="/#team"
                      class="ud-menu-scroll mx-8 flex py-2 text-base text-dark group-hover:text-green-600 lg:mr-0 lg:ml-7 lg:inline-flex lg:py-6 lg:px-0 lg:text-gray lg:group-hover:text-gray lg:group-hover:opacity-70 xl:ml-12"
                    >
                      Daftar
                    </a>
                  </li>
                  <li class="group relative">
                    <a
                      href="/#contact"
                      class="ud-menu-scroll mx-8 flex py-2 text-base text-dark group-hover:text-green-600 lg:mr-0 lg:ml-7 lg:inline-flex lg:py-6 lg:px-0 lg:text-gray lg:group-hover:text-gray lg:group-hover:opacity-70 xl:ml-12"
                    >
                      Kontak
                    </a>
                  </li>
                </ul>
              </nav>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- ====== Navbar Section End -->


    <!-- ====== Hero Section Start -->
    <div
      id="home"
      class="relative overflow-hidden bg-transparent pt-[120px] md:pt-[130px] lg:pt-[160px]"
    >

      <div class="container px-4">
        <div class="container flex flex-wrap items-center">

          <img class="object-cover" src="banner2.png">
        </div>
        <p class="text-center text-gray-600">
          IFOS ( Islamic Festival Of Smanexix ) adalah sebuah festival seni dan budaya Islam serta kompetisi pengetahuan Islam yang diadakan oleh Sie Kerohanian Islam  (SKI) SMAN 19 Surabaya, dan merupakan program kerja terbesar di setiap tahunnya.
        </p>
      </div>
    </div>
    <!-- ====== Hero Section End -->

    <!-- ====== Hero Sponsor Start -->
    <section id="sponson" class="pt-5 md:pt-[120px]">
      <div class="container px-4">
        <div class="flex flex-wrap">
          <div class="mx-4 w-full">
            <div class="mx-auto mb-[60px] max-w-[620px] text-center lg:mb-20">
              <h2
                class="mb-4 text-3xl font-bold text-gray-500 sm:text-4xl md:text-[42px]"
              >
                SUPPORT BY
              </h2>
            </div>
          </div>
        </div>
        <div class="flex flex-wrap">
          <div class="mx-4 w-full">
            <div class="wow fadeInUp" data-wow-delay=".2s">
              <div class="ud-brands-logo flex flex-wrap items-center">
                <div class="ud-single-logo mr-10 mb-5 max-w-[140px]">
                  <a
                    href="#"
                    target="_blank"
                    rel="nofollow noopner"
                  >
                    <img
                      src="sponsor/sponsor1.png"
                      alt="tailgrids"
                      class="grayscale duration-300 hover:filter-none"
                    />
                  </a>
                </div>
                <div class="ud-single-logo mr-10 mb-5 max-w-[140px]">
                  <a
                    href="#"
                    target="_blank"
                    rel="nofollow noopner"
                  >
                    <img
                      src="sponsor/sponsor2.png"
                      alt="ayroui"
                      class="grayscale duration-300 hover:filter-none"
                    />
                  </a>
                </div>
                <div class="ud-single-logo mr-10 mb-5 max-w-[140px]">
                  <a
                    href="#"
                    target="_blank"
                    rel="nofollow noopner"
                  >
                    <img
                      src="sponsor/sponsor3.png"
                      alt="uideck"
                      class="grayscale duration-300 hover:filter-none"
                    />
                  </a>
                </div>
                <div class="ud-single-logo mr-10 mb-5 max-w-[140px]">
                  <a
                    href="#"
                    target="_blank"
                    rel="nofollow noopner"
                  >
                    <img
                      src="sponsor/sponsor4.png"
                      alt="graygrids"
                      class="grayscale duration-300 hover:filter-none"
                    />
                  </a>
                </div>
                <div class="ud-single-logo mr-10 mb-5 max-w-[140px]">
                  <a
                    href="#"
                    target="_blank"
                    rel="nofollow noopner"
                  >
                    <img
                      src="sponsor/sponsor5.png"
                      alt="lineicons"
                      class="grayscale duration-300 hover:filter-none"
                    />
                  </a>
                </div>
                <div class="ud-single-logo mr-10 mb-5 max-w-[140px]">
                  <a
                    href="#"
                    target="_blank"
                    rel="nofollow noopner"
                  >
                    <img
                      src="sponsor/sponsor6.png"
                      alt="tailgrids"
                      class="grayscale duration-300 hover:filter-none"
                    />
                  </a>
                </div>
                <div class="ud-single-logo mr-10 mb-5 max-w-[140px]">
                  <a
                    href="#"
                    target="_blank"
                    rel="nofollow noopner"
                  >
                    <img
                      src="sponsor/sponsor7.png"
                      alt="ayroui"
                      class="grayscale duration-300 hover:filter-none"
                    />
                  </a>
                </div>
                <div class="ud-single-logo mr-10 mb-5 max-w-[140px]">
                  <a
                    href="#"
                    target="_blank"
                    rel="nofollow noopner"
                  >
                    <img
                      src="sponsor/sponsor8.png"
                      alt="uideck"
                      class="grayscale duration-300 hover:filter-none"
                    />
                  </a>
                </div>
                <div class="ud-single-logo mr-10 mb-5 max-w-[140px]">
                  <a
                    href="#"
                    target="_blank"
                    rel="nofollow noopner"
                  >
                    <img
                      src="sponsor/sponsor9.png"
                      alt="graygrids"
                      class="grayscale duration-300 hover:filter-none"
                    />
                  </a>
                </div>
                <div class="ud-single-logo mr-10 mb-5 max-w-[140px]">
                  <a
                    href="#"
                    target="_blank"
                    rel="nofollow noopner"
                  >
                    <img
                      src="sponsor/sponsor10.png"
                      alt="lineicons"
                      class="grayscale duration-300 hover:filter-none"
                    />
                  </a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- ====== Hero Section End -->

    <!-- ====== Lomba Start ====== -->
    <section id="lomba" class="pt-10 pb-10 md:pt-[120px] bg-gray-200">
      <div class="container px-4">
        <div class="flex flex-wrap">
          <div class="mx-4 w-full">
            <div class="mx-auto mb-[60px] max-w-[620px] text-center lg:mb-20">
              <h2
                class="mb-4 text-3xl font-bold text-dark sm:text-4xl md:text-[42px]"
              >
                DAFTAR LOMBA
              </h2>
            </div>
          </div>
        </div>
        <div class="flex flex-wrap">
          <div class="w-full px-4 pb-4 md:w-1/2 lg:w-1/3">
            <img
              src="lomba/1kaligrafi.png"
              class="duration-300 hover:filter-none"
            />
          </div>
          <div class="w-full px-4 pb-4 md:w-1/2 lg:w-1/3">
            <img
              src="lomba/2tartil.png"
              class="duration-300 hover:filter-none"
            />
          </div>
          <div class="w-full px-4 pb-4 md:w-1/2 lg:w-1/3">
            <img
              src="lomba/3albanjari.png"
              class="duration-300 hover:filter-none"
            />
          </div>
          <div class="w-full px-4 pb-4 md:w-1/2 lg:w-1/3">
            <img
              src="lomba/4cci.png"
              class="duration-300 hover:filter-none"
            />
          </div>
          <div class="w-full px-4 pb-4 md:w-1/2 lg:w-1/3">
            <img
              src="lomba/5daismp.png"
              class="duration-300 hover:filter-none"
            />
          </div>
          <div class="w-full px-4 pb-4 md:w-1/2 lg:w-1/3">
            <img
              src="lomba/6daisma.png"
              class="duration-300 hover:filter-none"
            />
          </div>
        </div>
      </div>
    </section>
    <!-- ====== Testimonials End ====== -->


<!-- ====== Lomba Start ====== -->
    <section id="lomba" class="px-5 md:pt-[120px]">
      <div class="container px-4">
        <div class="flex flex-wrap">
          <div class="mx-4 w-full">
            <div class="mx-auto mb-[60px] max-w-[620px] text-center lg:mb-20">
              <h2
                class="mb-4 text-3xl font-bold text-dark sm:text-4xl md:text-[42px]"
              >
                TIMELINE
              </h2>
            </div>
          </div>
        </div>
        <div class="flex flex-wrap">
          <div class="w-full px-4 pb-4 md:w-1/2 lg:w-1/4">
              <!-- <img class="header-logo" src="timeline/timeline1.png"> -->
              <!-- <div class="relative">
                <img class="w-full" src="timeline/timeline1.png" alt="dummy-image">
                <button class="absolute bottom-0 bg-green-500 rounded-full text-white p-2 hover:bg-green-800 m-2">Button</button>
              </div> -->
              <div class="relative">
                <img src="timeline/timeline1.png" />
                <button class="absolute bg-green-500 hover:bg-green-800 rounded-full text-white px-10 py-2 bottom-4 left-1/2 -translate-x-1/2">Download</button>
              </div>
          </div>
          <div class="w-full px-4 pb-4 md:w-1/2 lg:w-1/4">
              <img class="header-logo" src="timeline/timeline2.png">
          </div>
          <div class="w-full px-4 pb-4 md:w-1/2 lg:w-1/4">
              <img class="header-logo" src="timeline/timeline3.png">
          </div>
          <div class="w-full px-4 pb-4 md:w-1/2 lg:w-1/4">
              <img class="header-logo" src="timeline/timeline4.png">
          </div>
        </div>
      </div>
    </section>
    <!-- ====== Testimonials End ====== -->

    <!-- ====== Lomba Start ====== -->
    <section id="lomba" class="px-5 md:pt-[120px] bg-gray-200">
      <div class="container px-4">
        <div class="flex flex-wrap">
          <div class="mx-4 w-full">
            <div class="mx-auto mb-[60px] max-w-[620px] text-center lg:mb-20">
              <h2
                class="mb-4 text-3xl font-bold text-dark sm:text-4xl md:text-[42px]"
              >
                PENDAFTARAN
              </h2>
            </div>
          </div>
        </div>
        <div class="flex flex-wrap">
          <div class="w-full px-4 pb-4 md:w-1/2 lg:w-1/5">
            <p class="text-gray-400"> Online: </p>
            <a
              href="#"
              class="mt-6 items-center px-6 py-3 text-lg w-full block text-white font-semibold bg-green-500 hover:bg-green-800 rounded-full shadow-sm text-center"
            >
              Daftar Online
            </a>
          </div>
          <div class="w-full px-4 pb-4 md:w-1/2 lg:w-1/5">
            <div class="pl-20">
              <p class="text-gray-400"> Offline: </p>
              <h2 class="mb-4 text-3xl font-bold text-dark sm:text-4xl md:text-[42px]">Masjid Tis'ata Ashar</h2>
              <span>Jl. Kedung Cowek No. 390 - Surabaya</span>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- ====== Testimonials End ====== -->

    <!-- ====== Lomba Start ====== -->
    <section id="lomba" class="px-5 md:pt-[120px]">
      <div class="container px-4">
        <div class="flex flex-wrap">
          <div class="mx-4 w-full">
            <div class="mx-auto mb-[60px] max-w-[620px] text-center lg:mb-20">
              <h2
                class="mb-4 text-3xl font-bold text-dark sm:text-4xl md:text-[42px]"
              >
                KONTAK KAMI
              </h2>
            </div>
          </div>
        </div>
        <div class="flex flex-wrap">
          <div class="w-full px-4 pb-4 md:w-1/2 lg:w-1/5">
            <div class="peta" style="width:800px">
                <div class="embed-responsive embed-responsive-21by9">
                    <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3958.1745820140363!2d112.77544491487527!3d-7.220918072908762!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2dd7f84db21a9edf%3A0x4022753dbe5c1c33!2sSMA%20Negeri%2019%20Surabaya!5e0!3m2!1sid!2sid!4v1657589466705!5m2!1sid!2sid" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
                </div>
            </div>
          </div>
          <div class="w-full px-4 pb-4 md:w-1/2 lg:w-1/5">
            <div class="flex">
              <div class="w-full px-4 pb-4 md:w-1/2 lg:w-1/5">
                <img src="sosmed/whatsapp.png">
              </div>
              <div class="w-full px-4 pb-4 md:w-1/2 lg:w-1/5">
                <p class="text-green-600">0858 1099 8001</p>
                <p class="text-green-600">0896 1615 3872</p>
              </div>
            </div>
            <div class="flex">
              <div class="w-full px-4 pb-4 md:w-1/2 lg:w-1/5">
                <img src="sosmed/web.png">
              </div>
              <div class="w-full px-4 pb-4 md:w-1/2 lg:w-1/5">
                <p class="text-green-600">www.ifos5skinexix.com</p>
              </div>
            </div>
            <div class="flex">
              <div class="w-full px-4 pb-4 md:w-1/2 lg:w-1/5">
                <img src="sosmed/ig.png">
              </div>
              <div class="w-full px-4 pb-4 md:w-1/2 lg:w-1/5">
                <p class="text-green-600">ifos.skinexixsby</p>
              </div>
            </div>
            <div class="flex">
              <div class="w-full px-4 pb-4 md:w-1/2 lg:w-1/5">
                <img src="sosmed/gmail.png">
              </div>
              <div class="w-full px-4 pb-4 md:w-1/2 lg:w-1/5">
                <p class="text-green-600">ifos.skinexixsby@gmail.com</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- ====== Testimonials End ====== -->

  </div>
</template>
