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

    <!-- Header body-->
    <div class="bg-[url('/wave-haikei.svg')] bg-no-repeat bg-cover bg-center px-[72px] text-white relative py-12">
      <div>
        <img class="absolute bottom-0 left-1/3 -translate-x-1/4 h-[550px]" src="../assets/img/header-man.png" alt="">
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
            class="bg-[#1b99d4] text-white font-semibold py-2.5 px-5 rounded-[5px] cursor-pointer hover:bg-[#1b99d4d2] flex items-center gap-[15px]">Get
            in Touch <img src="../assets/img/right-arrow.png" alt=""></button>
        </div>
      </div>
    </div>
  </section>
  <!-- Header end -->

  <!-- trending -->
  <section class="container my-[70px]">
    <div class="flex justify-around shadow-[1px_5px_50px_0px_rgba(84,99,122,0.10)] py-8 px-10">
      <div class="flex gap-5">
        <img class="bg-[#F4F6F9] p-2.5 rounded-full" src="../assets/img/trending-up.png" alt="">
        <div>
          <h2 class="text-[#27B94E] text-3xl font-bold items-center">126%</h2>
          <p class="text-[#4D607D]">170% Average Salary Hike</p>
        </div>
      </div>
      <div class="flex gap-5">
        <img class="bg-[#F4F6F9] p-2.5 rounded-full" src="../assets/img/Briefcase.png" alt="">
        <div>
          <h2 class="text-[#FFA41B] text-3xl font-bold items-center">100+</h2>
          <p class="text-[#4D607D]">Job Placments</p>
        </div>
      </div>
      <div class="flex gap-5">
        <img class="bg-[#F4F6F9] p-2.5 rounded-full" src="../assets/img/ChalkboardTeacher.png" alt="">
        <div>
          <h2 class="text-[#D60000] text-3xl font-bold items-center">Live</h2>
          <p class="text-[#4D607D]">Interactive Sessions</p>
        </div>
      </div>
    </div>
  </section>
  <!-- trending end -->

  <!-- RELATED COURSES -->
  <section class="container bg-[#F8FBFB] py-[70px]">
    <div class="text-center">
      <p class="text-[#1B99D4] text-base font-semibold tracking-[1.6px]">RELATED COURSES</p>
      <h2 class="text-4xl font-semibold mt-3.5">Why Join this Program ?</h2>
    </div>
    <!-- cart -->
    <div class="flex gap-9 pt-12">
      <div
        class="flex flex-col items-center gap-6 text-center p-8 bg-white rounded-2xl shadow-[0.914px_4.57px_45.7px_0px_rgba(84,99,122,0.10)]">
        <img class="bg-[#1B99D4] p-4 rounded-full" src="../assets/img/hourglass.png" alt="">
        <h2 class="text-[21px] font-semibold">Real Work Experience</h2>
        <p class="text-[#6F6B80] text-base">Work with companies directly on software development projects to master your
          skills
          and build a strong
          project portfolio to get your.</p>
      </div>
      <div
        class="flex flex-col items-center gap-6 text-center p-8 bg-white rounded-2xl shadow-[0.914px_4.57px_45.7px_0px_rgba(84,99,122,0.10)]">
        <img class="bg-[#1B99D4] p-4 rounded-full" src="../assets/img/hourglass.png" alt="">
        <h2 class="text-[21px] font-semibold">Guaranteed job referral</h2>
        <p class="text-[#6F6B80] text-base">Our program seeks to eliminate financial risk in the upskilling journey with
          our guaranteed Job referrals option</p>
      </div>
      <div
        class="flex flex-col items-center gap-6 text-center p-8 bg-white rounded-2xl shadow-[0.914px_4.57px_45.7px_0px_rgba(84,99,122,0.10)]">
        <img class="bg-[#1B99D4] p-4 rounded-full" src="../assets/img/hourglass.png" alt="">
        <h2 class="text-[21px] font-semibold">Crack FAANG Interview</h2>
        <p class="text-[#6F6B80] text-base">Interact and Learn from mentors working in top product based companies to
          crack interviews for your dream role.</p>
      </div>
    </div>
  </section>
</template>