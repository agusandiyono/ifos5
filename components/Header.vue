<template>
  <div>
  <!-- ====== Navbar Section Start -->
    <div
      class="ud-header fixed top-0 left-0 z-40 flex w-full items-center bg-white shadow-lg "
    >
      <div class="container">
        <div class="relative -mx-2 flex items-center justify-between">
          <div class="w-40 max-w-full">
            <a href="index.html" class="navbar-logo block w-full py-5">
              <img class="header-logo w-32" src="logokecil.png">
            </a>
          </div>
          <div class="flex w-full items-center justify-end px-4">
            <div>
        
        <a
              href="https://ifos5.carrd.co/"
              class="lg:hidden mt-2 items-center px-3 py-3 text-sm w-full block text-white font-semibold bg-yellow-500 hover:bg-green-800 rounded-full shadow-sm text-center"
            >
              Daftar Sekarang
            </a>
      
              <!-- <button
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
              </button> -->
              <nav
                id="navbarCollapse"
                class="absolute right-4 top-full hidden w-full max-w-[250px] rounded-lg bg-white py-5 shadow-lg lg:static lg:block lg:w-full lg:max-w-full lg:bg-transparent lg:py-0 lg:px-4 lg:shadow-none xl:px-6"
              >
                <ul class="blcok lg:flex">
                  <li class="group relative">
                    <a
                      href="#home"
                      class="ud-menu-scroll mx-8 flex py-2 text-base text-dark group-hover:text-green-600 lg:mr-0 lg:inline-flex lg:py-6 lg:px-0 lg:text-gray lg:group-hover:text-gray lg:group-hover:opacity-70"
                    >
                      Beranda
                    </a>
                  </li>
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
      class="relative overflow-hidden bg-transparent pb-4 pt-[120px] md:pt-[130px] lg:pt-[160px]"
    >

      <div class="container px-4">
        <div class="container flex flex-wrap items-center">

          <img class="object-cover" src="banner2.png">
        </div>
        <p class="text-center text-gray-400 pt-5  ">
          IFOS ( Islamic Festival Of Smanexix ) adalah sebuah festival seni dan budaya Islam serta kompetisi pengetahuan Islam yang diadakan oleh Sie Kerohanian Islam  (SKI) SMAN 19 Surabaya, dan merupakan program kerja terbesar di setiap tahunnya.
        </p>
            <a
              href="https://ifos5.carrd.co/"
              class=" mt-6 items-center px-6 py-3 text-lg w-full block text-white font-semibold bg-green-500 hover:bg-green-800 rounded-full shadow-sm text-center"
            >
              Daftar Sekarang
            </a>
      </div>
    </div>
    <!-- ====== Hero Section End -->

    <!-- ====== Hero Sponsor Start -->
    <!-- <section id="sponsor" class="pt-5 md:pt-[50px] pb-6">
      <div class="container px-7">
        <div class="flex flex-wrap">
          <div class="mx-4 w-full">
            <div class="mx-auto mb-[25px] max-w-[600px] text-center lg:mb-10">
              <h2
                class="mb-7 text-2xl font-bold text-gray-400 sm:text-4xl md:text-[20px]"
              >
                SUPPORT BY
              </h2>
            </div>
          </div>
        </div>
        <div class="items-center justify-items-center">
          <div class="grid grid-cols-2 gap-4 sm:grid-cols-2 md:grid-cols-5 md:gap-5 pb-2" >
           
            <div class="b-[20px] pb-2 px-2 " v-for="index in 10">
              <a
                href="#"
                target="_blank"
                rel="nofollow noopner"
              >
                <img
                  :src="`sponsor/sponsor${index}.png`"
                  alt="ifos5"
                  class="w-full"
                />
              </a>
              </div>
            </div>
                
              </div>

      </div>
    </section> -->
    <!-- ====== Hero Section End -->

    <!-- ====== Lomba Start ====== -->
    <section id="lomba" class="pb-[15px] pt-[25px] bg-gray-200">
      <div class="container px-4">
        <div class="flex flex-wrap">
          <div class="mx-4 w-full">
            <div class="mx-auto mb-[30px] max-w-[620px] text-center">
              <h2
                class=" text-2xl font-bold text-gray-500 sm:text-4xl md:text-[25px]"
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
              src="lomba/3albanjari_1.png"
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
    <section id="lomba" class="px-1 pt-[25px] pb-[25px]" >
      <div class="container ">
        <div class="flex flex-wrap">
          <div class=" w-full">
            <div class="mx-auto mb-[25px] max-w-[620px] text-center lg:mb-10">
              <h2
                class="mb-3 text-2xl font-bold text-gray-400 sm:text-4xl md:text-[25px] lg:text-[10px]"
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
                <a
                href="https://drive.google.com/file/d/16Gcbi80Ty_Qz8iRwLGjcVgkLxLFv1GjX/view?usp=sharing"
                button class="absolute bg-purple-600 hover:bg-purple-800 rounded-full text-white px-10 py-2 bottom-4 left-1/2 -translate-x-1/2">Panduan
                </a>
              </div>
          </div>
          <div class="w-full px-4 pb-4 md:w-1/2 lg:w-1/4">
              <img class="header-logo" src="timeline/timeline2.png">
          </div>
          <div class="w-full px-4 pb-4 md:w-1/2 lg:w-1/4">
              <img class="header-logo" src="timeline/timeline3.png">
          </div>
          <div class="relative w-full px-4 pb-4 md:w-1/2 lg:w-1/4">
              <img class="header-logo" src="timeline/timeline4.png">
              <a
              href="https://drive.google.com/uc?export=download&id=167Q09iXRw-RpNux1NftSIen1UulyIpVV"
              button class="absolute bg-orange-600 hover:bg-orange-800 rounded-full text-center w-64 text-white px-10 py-2 bottom-9 left-2/4 -translate-x-1/2"> Unduh Poster 
              </a>
          </div>
        </div>
      </div>
    </section>
    <!-- ====== Testimonials End ====== -->

    <!-- ====== Lomba Start ====== -->
    <section id="pendaftaran" class=" pt-[20px] pb-6 bg-gray-200">
      <div class="container">
        <div class="flex flex-wrap">
          <div class="mx-4 w-full">
            <div class="mx-auto max-w-[620px] text-center ">
              <h2
                class="mb-2 text-2xl font-bold text-gray-400 sm:text-4xl md:text-[25px]"
              >
                PENDAFTARAN
              </h2>
            </div>
          </div>
        </div>
        <div class="flex flex-wrap">
          <div class="w-full px-4 pb-2 md:w-1/2 lg:w-1/5">
            <p class="text-gray-400 text-center"> Online: </p>
            <a
              href="https://ifos5.carrd.co/"
              class="mt-2 items-center py-3 text-lg w-full block text-white font-semibold bg-green-500 hover:bg-green-800 rounded-full shadow-sm text-center"
            >
              Daftar Online
            </a>
          </div>
          <div class="w-full px-4 pb-4 md:w-1/2 lg:w-1/5">
            <div class="">
              <p class="text-gray-400 text-center mb-2"> Offline: </p>
              <h2 class="mb-1 text-3xl text-center font-bold text-dark sm:text-4xl md:text-[42px]">Masjid Tis'ata Asyar</h2>
              <h2 class="text-center">Jl. Kedung Cowek No. 390 - Surabaya</h2>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- ====== Testimonials End ====== -->

    <!-- ====== Lomba Start ====== -->
    <section id="lomba" class="pt-[40px] pb-[40px] justify-items-center" >
      <div class="container px-4">
        <!-- <div class="flex flex-wrap">
          <div class="mx-2 w-full">
            <div class="mx-auto mb-[60px] max-w-[620px] text-center lg:mb-20">
              jhgjh
            </div>
          </div>
        </div> -->

  <div class=" items-center justify-items-center">
          <div class="grid grid-cols-2 gap-4 items-center lg:grid-cols-4 lg:gap-4 sm:grid-cols-2 md:grid-cols-4 md:gap-5  " >
            <!-- <div class="pb-5 w-full px-4 lg:w-1/4 sm:w-1/2" v-for="index in 10"> -->
            <!-- <div class="w-1/2 pb-[20px] px-2 " v-for="index in 10"> -->
            <div class="pb-1 px-1 " v-for="index in 4">
              <a
                href="#"
                target="_blank"
                rel="nofollow noopner"
              >
                <img
                  :src="`sosmed/sosmed${index}.png`"
                  alt="ifos5"
                  class="w-full"
                />
                
              </a>
              </div>
            </div>

        <div class="flex flex-wrap">
          <!-- <div class="w-full px-4 pb-6 md:w-1/2 lg:w-1/5">
            <div class="peta" style="width:800px">
                <div class="embed-responsive embed-responsive-21by9">
                    <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3958.1745820140363!2d112.77544491487527!3d-7.220918072908762!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2dd7f84db21a9edf%3A0x4022753dbe5c1c33!2sSMA%20Negeri%2019%20Surabaya!5e0!3m2!1sid!2sid!4v1657589466705!5m2!1sid!2sid" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
                </div>
            </div>
          </div> -->
          
<!--           
          
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
            </div>-->


<!-- Histats.com  START (hidden counter) -->
<a href="/" alt="" target="_blank" ></a>
<img  src="//sstatic1.histats.com/0.gif?4680425&101" alt="" border="0">
<!-- Histats.com  END  -->


          </div> 
        </div>
      </div>
    </section>
    <!-- ====== Testimonials End ====== -->

  </div>
</template>
