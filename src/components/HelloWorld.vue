
<template>
  <!-- Header -->
  <section class="">
    <!-- navbar -->
    <div class="container flex justify-between items-center my-[26px]">
      <div class="flex items-center gap-2.5 cursor-pointer">
        <img src="../assets/img/logo.png" alt="">
        <h2 class="text-[22px] font-bold">My_Tutor</h2>
      </div>
      <div class="flex items-center gap-9 text-base">
        <ul class="flex gap-11 text-[#424352]">
          <li class="hover:text-[#1b99d4]"><a href="#">About Us</a></li>
          <li class="hover:text-[#1b99d4]"><a href="#">Courses</a></li>
          <li class="hover:text-[#1b99d4]"><a href="#">Events</a></li>
          <li class="hover:text-[#1b99d4]"><a href="#">Blogs</a></li>
        </ul>
        <button
          class="bg-[#1b99d4] text-white font-semibold py-2.5 px-5 rounded-[5px] cursor-pointer hover:bg-[#1b99d4d2]">Apply
          Now</button>
      </div>
    </div>

    <!-- Header -->
    <div
      class="bg-[url('./src/assets/img/wave-haikei.svg')] bg-no-repeat bg-cover bg-center px-[72px] text-white relative py-12">
      <div>
        <img class="absolute bottom-0 left-1/3 -translate-x-1/5 h-[550px]" src="../assets/img/header-man.png" alt="">
      </div>
      <div class="flex justify-between items-center">
        <div class="">
          <!-- text -->
          <p class="bg-[#3a9bc9] inline-block p-2 font-medium mb-5">Specialization over generalization</p>
          <h1 class="text-[42px] font-bold mb-5">Advanced Data Science <br>
            & AI Course</h1>
          <p class="text-[17px] text-[#ffffffcc] mb-5">Equip yourself with data science skills through live, <br>
            interactive
            lectures guided by industry expert
            mentors
          </p>
          <p class="text-3xl">Live Interactive Classes</p>
          <a class=" bg-white text-black p-4 mt-10 flex items-center justify-between w-[215px] rounded-[5px]" href="#">
            <img class="w-[20px]" src="../assets/img/download-icon.svg" alt=""> Download Brochure</a>
        </div>
        <!-- form -->
        <div class="z-10 bg-white p-8 rounded-xl">
          <h2 class="text-black text-4xl font-bold mb-3.5">We’re here to help!</h2>
          <p class="text-[#666666] text-lg mb-11">Please contact us in case of any query.</p>
          <form action="" class="flex flex-col gap-8 mb-11">
            <input
              class="bg-white focus:ring-2 focus:ring-blue-500 focus:outline-none border border-[#E6E9FC] text-[#727695] px-3 py-3.5"
              type="text" placeholder="Your name">
            <input
              class="bg-white focus:ring-2 focus:ring-blue-500 focus:outline-none border border-[#E6E9FC] text-[#727695] px-3 py-3.5"
              type="text" placeholder="Your email address">
            <input
              class="bg-white focus:ring-2 focus:ring-blue-500 focus:outline-none border border-[#E6E9FC] text-[#727695] px-3 py-3.5"
              type="text" placeholder="Your phone number">
            <select
              class="bg-white focus:ring-2 focus:ring-blue-500 focus:outline-none border border-[#E6E9FC] text-[#727695] px-3 py-3.5"
              name="" id="" placeholder="Select Course">
              <option value="ff">Select Course</option>
              <option value="ff">Group 1</option>
            </select>
          </form>
          <button
            class="bg-[#1b99d4] text-white font-semibold py-2.5 px-5 rounded-[5px] cursor-pointer hover:bg-[#1b99d4d2]">Get
            in Touch</button>
        </div>
      </div>
    </div>
  </section>
</template>

