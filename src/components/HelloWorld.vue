<template>
  <!-- Header -->
  <section class="">
    <!-- navbar -->
    <div class="container flex justify-between items-center my-[26px]">
      <!-- logo -->
      <div class="flex items-center gap-2.5 cursor-pointer">
        <img src="../assets/img/logo.png" alt="">
        <h2 class="text-[22px] font-bold">My_Tutor</h2>
      </div>
      <!-- menu -->
      <div class="flex items-center gap-9 text-base">
        <ul class="flex gap-11 text-[#424352]">
          <li class="hover:text-[#1b99d4]"><a href="#">About Us</a></li>
          <li class="hover:text-[#1b99d4]"><a href="#">Courses</a></li>
          <li class="hover:text-[#1b99d4]"><a href="#">Events</a></li>
          <li class="hover:text-[#1b99d4]"><a href="#">Blogs</a></li>
        </ul>
        <!-- button -->
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
  <!-- RELATED COURSES End -->

  <!-- Alumni Section -->
  <section class="container py-[70px]">
    <div class="text-center">
      <p class="text-[#1B99D4] text-base font-semibold tracking-[1.6px]">Our Alumni Placed</p>
      <h2 class="text-4xl font-semibold mt-3.5 text-[#231F40]">Explore Our Alumni & Connect With Them</h2>
    </div>
    <!-- cart -->
    <div class="flex gap-9 pt-12">
      <div class="p-5 bg-white rounded-xl shadow-[1px_5px_50px_0px_rgba(84,99,122,0.10)]">
        <div class="flex items-start justify-between">
          <img class="rounded-full w-[72px] h-[72px]" src="../assets/img/man1.jpg" alt="">
          <div class="flex items-center gap-0.5 border border-[#43A55D] px-2.5 py-0.5">
            <img src="../assets/img/trending-up-green.png" alt="">
            <p class="text-[#43A55D] font-semibold tracking-[0.073px]">120% Hike</p>
          </div>
        </div>
        <div>
          <h2 class="text-xl font-semibold leading-8  ">Shaumaya Qha</h2>
          <p class="leading-8 text-base">Software Engineer</p>
          <p class="text-[#4D607D] text-base mt-2.5 leading-6">Apart from regular live classes, I was assigned with a
            Mentor
            someone from Microsoft and he guided me very well through out the course.</p>
        </div>
        <div class="flex items-center mt-9 gap-2">
          <img src="../assets/img/jpMorgan.png" alt="">
          <img src="../assets/img/arrow-right.png" alt="">
          <img src="../assets/img/Walmart_logo.png" alt="">
        </div>
        <div class="flex gap-2.5 items-center mt-3.5">
          <img src="../assets/img/linkedin.png" alt="">
          <a href="#" class="text-[#006DD9] text-lg">Read full review</a>
        </div>
      </div>

      <div class="p-5 bg-white rounded-xl shadow-[1px_5px_50px_0px_rgba(84,99,122,0.10)]">
        <div class="flex items-start justify-between">
          <img class="rounded-full w-[72px] h-[72px]" src="../assets/img/man2.jpg" alt="">
          <div class="flex items-center gap-0.5 border border-[#43A55D] px-2.5 py-0.5">
            <img src="../assets/img/trending-up-green.png" alt="">
            <p class="text-[#43A55D] font-semibold tracking-[0.073px]">90% Hike</p>
          </div>
        </div>
        <div>
          <h2 class="text-xl font-semibold leading-8  ">Subhangi Duhan</h2>
          <p class="leading-8 text-base">Software Researcher</p>
          <p class="text-[#4D607D] text-base mt-2.5 leading-6">My focus and expectations was
            more into System Design and I
            have learned a lot of it, Specially
            High Level design and that helped
            me to crack Microsoft.</p>
        </div>
        <div class="flex items-center mt-9 gap-2">
          <img src="../assets/img/jpMorgan.png" alt="">
          <img src="../assets/img/arrow-right.png" alt="">
          <img src="../assets/img/Microsoft-logo.png" alt="">
        </div>
        <div class="flex gap-2.5 items-center mt-3.5">
          <img src="../assets/img/linkedin.png" alt="">
          <a href="#" class="text-[#006DD9] text-lg">Read full review</a>
        </div>
      </div>

      <div class="p-5 bg-white rounded-xl shadow-[1px_5px_50px_0px_rgba(84,99,122,0.10)]">
        <div class="flex items-start justify-between">
          <img class="w-[72px] h-[72px]" src="../assets/img/man3.png" alt="">
          <div class="flex items-center gap-0.5 border border-[#43A55D] px-2.5 py-0.5">
            <img src="../assets/img/trending-up-green.png" alt="">
            <p class="text-[#43A55D] font-semibold tracking-[0.073px]">80% Hike</p>
          </div>
        </div>
        <div>
          <h2 class="text-xl font-semibold leading-8  ">Paras Yadav</h2>
          <p class="leading-8 text-base">Software Tester</p>
          <p class="text-[#4D607D] text-base mt-2.5 leading-6">Consistency is the key, that I have
            learned from my Mentor at
            My_Tutor. He usually motivates
            me to be consistent is class and
            solving problems.</p>
        </div>
        <div class="flex items-center mt-9 gap-2">
          <img src="../assets/img/commscope.png" alt="">
          <img src="../assets/img/arrow-right.png" alt="">
          <img src="../assets/img/cohesity-logo.png" alt="">
        </div>
        <div class="flex gap-2.5 items-center mt-3.5">
          <img src="../assets/img/linkedin.png" alt="">
          <a href="#" class="text-[#006DD9] text-lg">Read full review</a>
        </div>
      </div>
    </div>

    <div class="flex justify-center pt-16">
      <button
        class="bg-[#1b99d4] text-white font-semibold py-2.5 px-5 rounded-[5px] cursor-pointer hover:bg-[#1b99d4d2] flex items-center gap-[15px]">Connect
        Now <img src="../assets/img/right-arrow.png" alt=""></button>
    </div>
  </section>
  <!-- Alumni Section End -->

  <!-- curriculum Section -->
  <section class="container pt-[20px] pb-[70px]">
    <div class="text-center">
      <p class="text-[#1B99D4] text-base font-semibold tracking-[1.6px]">A Roadmap For Success</p>
      <h2 class="text-4xl font-semibold mt-3.5 text-[#231F40]">Our Comprehensive curriculum, Designed for professionals
      </h2>
    </div>

    <!-- Description -->
    <div class="my-[40px] flex items-center gap-[78px]">
      <div>
        <div>
          <h2 class="text-3xl font-bold mb-[26px]">Course Description</h2>
          <p class="text-[#6F6B80] text-lg">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
            tempor incididunt ut labore et dolore magna aliqua. Quis ipsum suspendisse ultrices gravida. Risus commodo
            viverra maecenas accumsan lacus vel facilisis.</p>
        </div>

        <!-- course description -->
        <div class="mt-[31px] flex flex-col gap-[30px]">
          <select name="" id=""
            class="py-[17px] px-[29px] rounded-[5px] border border-[#D9D9D9] text-[21px] font-medium text-[#595665] focus:ring-2 focus:ring-blue-500 focus:outline-none">
            <option value="ss">
              Unit 0 - Foundation Of Programming
            </option>
          </select>
          <select name="" id=""
            class="py-[17px] px-[29px] rounded-[5px] border border-[#D9D9D9] text-[21px] font-medium text-[#595665] focus:ring-2 focus:ring-blue-500 focus:outline-none">
            <option value="ss">
              Unit 1 - Data Structures and Algorithms
            </option>
          </select>
          <select name="" id=""
            class="py-[17px] px-[29px] rounded-[5px] border border-[#D9D9D9] text-[21px] font-medium text-[#595665] focus:ring-2 focus:ring-blue-500 focus:outline-none">
            <option value="ss">
              Unit 2 - System Design in Depth
            </option>
          </select>
          <select name="" id=""
            class="py-[17px] px-[29px] rounded-[5px] border border-[#D9D9D9] text-[21px] font-medium text-[#595665] focus:ring-2 focus:ring-blue-500 focus:outline-none">
            <option value="ss">
              Unit 3 - Advance Data Structures & Algorithms
            </option>
          </select>
          <select name="" id=""
            class="py-[17px] px-[29px] rounded-[5px] border border-[#D9D9D9] text-[21px] font-medium text-[#595665] focus:ring-2 focus:ring-blue-500 focus:outline-none">
            <option value="ss">
              Unit 4 - Electives & Specialization
            </option>
          </select>
          <select name="" id=""
            class="py-[17px] px-[29px] rounded-[5px] border border-[#D9D9D9] text-[21px] font-medium text-[#595665] focus:ring-2 focus:ring-blue-500 focus:outline-none">
            <option value="ss">
              Unit 5 - Work on End to End Projects in Partnership With Startups
            </option>
          </select>
        </div>
      </div>

      <!-- Apply for Counselling Form -->
      <div
        class="bg-white p-8 shadow-[1px_5px_50px_0px_rgba(84,99,122,0.10)] text-[#727695] border-b-[5px] border-[#1B99D4]">
        <img class="" src="../assets/img/applying.jpg" alt="">
        <form action="" class="flex flex-col gap-[30px] mt-[30px]">
          <input
            class="py-[17px] px-[29px] rounded-[5px] border border-[#D9D9D9] text-[21px] font-medium focus:ring-2 focus:ring-blue-500 focus:outline-none"
            type="text" name="" id="" placeholder="Enter Full Name">
          <input
            class="py-[17px] px-[29px] rounded-[5px] border border-[#D9D9D9] text-[21px] font-medium focus:ring-2 focus:ring-blue-500 focus:outline-none"
            type="email" name="" id="" placeholder="Enter email address">
          <input
            class="py-[17px] px-[29px] rounded-[5px] border border-[#D9D9D9] text-[21px] font-medium focus:ring-2 focus:ring-blue-500 focus:outline-none"
            type="text" name="" id="" placeholder="Enter phone number">
          <select name="" id=""
            class="py-[17px] px-[29px] rounded-[5px] border border-[#D9D9D9] text-[21px] font-medium focus:ring-2 focus:ring-blue-500 focus:outline-none">
            <option value="ss" class="">
              Select Course
            </option>
          </select>
          <input class=" py-[17px] px-[29px] rounded-[5px] border border-[#D9D9D9] text-[21px] font-medium 
              focus:ring-2 focus:ring-blue-500 focus:outline-none" type="text" name="" id=""
            placeholder="Schedule Date & Time">
        </form>
        <p class=" text-sm pt-[11px] pb-[24px]">By submitting the form, you agree to our Terms and Conditions and our
          Privacy
          Policy.
        </p>
        <button
          class="bg-[#1b99d4] w-full text-[16px] text-white font-semibold py-2.5 px-5 rounded-[5px] cursor-pointer hover:bg-[#1b99d4d2]">Apply
          for Counselling</button>
      </div>
    </div>
    <div class="flex justify-center">
      <a class=" bg-white text-[#1B99D4] p-4 mt-10 flex items-center justify-between w-[215px] rounded-[5px] border border-[#1B99D4] hover:bg-[#1B99D4] hover:text-white"
        href="#">
        <svg xmlns="http://www.w3.org/2000/svg" width="15" height="15" viewBox="0 0 15 15" fill="none">
          <path
            d="M13.125 9.375V11.875C13.125 12.2065 12.9933 12.5245 12.7589 12.7589C12.5245 12.9933 12.2065 13.125 11.875 13.125H3.125C2.79348 13.125 2.47554 12.9933 2.24112 12.7589C2.0067 12.5245 1.875 12.2065 1.875 11.875V9.375"
            stroke="#1B99D4" stroke-linecap="round" stroke-linejoin="round" />
          <path d="M4.375 6.25L7.5 9.375L10.625 6.25" stroke="#1B99D4" stroke-linecap="round" stroke-linejoin="round" />
          <path d="M7.5 9.375V1.875" stroke="#1B99D4" stroke-linecap="round" stroke-linejoin="round" />
        </svg> Download Brochure</a>
    </div>
  </section>
  <!-- curriculum Section end -->

  <!-- Hands-on Projects Section -->
  <section class="container py-[70px]">
    <div class="flex justify-between items-center">
      <div>
        <h2 class="text-[48px] font-semibold mb-[19px]">Hands-on Projects</h2>
        <p class="leading-[32px] text-[#666666] text-base">Find out how our Mentor transformed their careers by giving
          <br>
          Hands on Projects.
        </p>
        <div class="mt-[25px] flex gap-[27px]">
          <div
            class="text-center text-white bg-[#20AD96] rounded-[5px] shadow-[0px_7px_29px_0px_rgba(99,99,110,0.20)] flex items-center justify-center">
            <p class="text-[28px] font-bold leading-[23px] px-[61px] py-[10px]">10+ <br> <span
                class="text-base font-normal">Projects</span></p>
          </div>
          <div
            class="text-center text-white bg-[#9747FF] rounded-[5px] shadow-[0px_7px_29px_0px_rgba(99,99,110,0.20)] flex items-center justify-center">
            <p class="text-[28px] font-bold leading-[23px] px-[61px] py-[10px]">06+ <br> <span
                class="text-base font-normal">Domains</span></p>
          </div>
        </div>
        <!-- arrow -->
        <div class="flex items-center gap-[16px] mt-[37px]">
          <div
            class="p-[30px] rounded-full shadow-[0px_0px_16px_4px_rgba(126,126,126,0.1)] hover:shadow-[0px_0px_16px_4px_rgba(126,126,126,0.4)] transition-all duration-300 cursor-pointer">
            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 16 16" fill="none">
              <path
                d="M15.0005 9.00021H3.83047L8.71047 13.8802C9.10047 14.2702 9.10047 14.9102 8.71047 15.3002C8.32047 15.6902 7.69047 15.6902 7.30047 15.3002L0.710469 8.71021C0.320469 8.32021 0.320469 7.69021 0.710469 7.30021L7.29047 0.700215C7.68047 0.310215 8.31047 0.310215 8.70047 0.700215C9.09047 1.09021 9.09047 1.72021 8.70047 2.11021L3.83047 7.00021H15.0005C15.5505 7.00021 16.0005 7.45021 16.0005 8.00021C16.0005 8.55021 15.5505 9.00021 15.0005 9.00021Z"
                fill="#323232" />
            </svg>
          </div>

          <div
            class="p-[30px] rounded-full shadow-[0px_0px_16px_4px_rgba(126,126,126,0.1)] hover:shadow-[0px_0px_16px_4px_rgba(126,126,126,0.4)] transition-all duration-300 cursor-pointer">
            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 16 16" fill="none">
              <path
                d="M1.41797 9.00021H12.588L7.70797 13.8802C7.31797 14.2702 7.31797 14.9102 7.70797 15.3002C8.09797 15.6902 8.72796 15.6902 9.11796 15.3002L15.708 8.71021C16.098 8.32021 16.098 7.69021 15.708 7.30021L9.12796 0.700215C8.73796 0.310215 8.10797 0.310215 7.71797 0.700215C7.32797 1.09021 7.32797 1.72021 7.71797 2.11021L12.588 7.00021H1.41797C0.867969 7.00021 0.417969 7.45021 0.417969 8.00021C0.417969 8.55021 0.867969 9.00021 1.41797 9.00021Z"
                fill="#323232" />
            </svg>
          </div>
        </div>
      </div>

      <!-- Authentication -->
      <div class="flex flex-col gap-5 p-10 bg-white rounded-xl shadow-[1px_5px_50px_0px_rgba(84,99,122,0.10)]">
        <h2 class="text-[#727695] text-[22px] font-bold">Authentication</h2>
        <img class="w-2/3" src="../assets/img/symantec.png" alt="">
        <p class="text-[#646464] font-base leading-[23px]">Create authentication technology to give access, Correspond
          <br> to those stored in a
          da ase of authorized
          users.
        </p>
        <div class="flex gap-[22px] items-center ">
          <p class="text-[#646464] text-lg font-medium">Tools:</p>
          <img src="../assets/img/Frame1.png" alt="">
          <img src="../assets/img/Frame2.png" alt="">
          <img src="../assets/img/Frame3.png" alt="">
          <img src="../assets/img/Frame4.png" alt="">
        </div>
      </div>
    </div>
  </section>
  <!-- Hands-on Projects Section end -->

  <!-- Course Highlights Section -->
  <section class="container py-[70px]">
    <div class="flex justify-between gap-14 ">
      <div class="flex flex-col gap-6 border border-[#D9D9D9] rounded-xl p-8 w-1/3">
        <h2 class="text-[#1B99D4] text-lg font-semibold mb-[32px]">Course Highlights</h2>
        <div class="flex gap-2 items-center text-base">
          <svg xmlns="http://www.w3.org/2000/svg" width="26" height="26" viewBox="0 0 26 26" fill="none">
            <path
              d="M9.74967 10.8332V19.4998L17.333 15.1665L9.74967 10.8332ZM22.7497 6.49984H14.538L18.1022 2.93567L17.333 2.1665L12.9997 6.49984H12.9672L8.63384 2.1665L7.88634 2.93567L11.4397 6.49984H3.24967C2.05801 6.49984 1.08301 7.47484 1.08301 8.6665V21.6665C1.08301 22.8582 2.05801 23.8332 3.24967 23.8332H22.7497C23.9413 23.8332 24.9163 22.8582 24.9163 21.6665V8.6665C24.9163 7.47484 23.9413 6.49984 22.7497 6.49984ZM22.7497 21.6665H3.24967V8.6665H22.7497V21.6665Z"
              fill="#1B99D4" />
          </svg>
          <p class="text-[#646464]">350+ Live sessions</p>
        </div>
        <div class="flex gap-2 items-center text-base">
          <svg xmlns="http://www.w3.org/2000/svg" width="26" height="26" viewBox="0 0 26 26" fill="none">
            <path
              d="M7.92407 15.0187C8.00278 15.0974 8.13228 15.0974 8.21099 15.0187L10.7958 12.4339L12.9819 14.6226C13.0606 14.7013 13.1901 14.7013 13.2688 14.6226L19.0147 8.87163C19.0934 8.79292 19.0934 8.66343 19.0147 8.58472L18.0803 7.65034C18.0016 7.57163 17.8721 7.57163 17.7934 7.65034L13.1266 12.3222L10.9405 10.1335C10.8618 10.0548 10.7323 10.0548 10.6536 10.1335L6.9897 13.7974C6.91099 13.8761 6.91099 14.0056 6.9897 14.0843L7.92407 15.0187Z"
              fill="#1B99D4" />
            <path
              d="M22.9531 4.0625H13.9141V2.4375C13.9141 2.32578 13.8227 2.23438 13.7109 2.23438H12.2891C12.1773 2.23438 12.0859 2.32578 12.0859 2.4375V4.0625H3.04688C2.59746 4.0625 2.23438 4.42559 2.23438 4.875V18.0781C2.23438 18.5275 2.59746 18.8906 3.04688 18.8906H12.0961V19.7031L7.91172 22.4479C7.81777 22.5088 7.79238 22.6332 7.85332 22.7271L8.62266 23.9256V23.9281C8.68359 24.0221 8.81055 24.0475 8.90449 23.9865L13 21.3002L17.0955 23.9865C17.1895 24.0475 17.3164 24.0221 17.3773 23.9281V23.9256L18.1467 22.7271C18.2076 22.6332 18.1797 22.5088 18.0883 22.4479L13.9141 19.7107V18.8906H22.9531C23.4025 18.8906 23.7656 18.5275 23.7656 18.0781V4.875C23.7656 4.42559 23.4025 4.0625 22.9531 4.0625ZM21.9375 17.0625H4.0625V5.89062H21.9375V17.0625Z"
              fill="#1B99D4" />
          </svg>
          <p class="text-[#646464]">15+ Industry Projects</p>
        </div>
        <div class="flex gap-2 items-center text-base">
          <svg xmlns="http://www.w3.org/2000/svg" width="26" height="26" viewBox="0 0 26 26" fill="none">
            <path
              d="M23.9941 10.4609H17.4941C17.3824 10.4609 17.291 10.5523 17.291 10.6641V11.8828C17.291 11.9945 17.3824 12.0859 17.4941 12.0859H23.9941C24.1058 12.0859 24.1972 11.9945 24.1972 11.8828V10.6641C24.1972 10.5523 24.1058 10.4609 23.9941 10.4609ZM20.5917 13.9141H17.4941C17.3824 13.9141 17.291 14.0055 17.291 14.1172V15.3359C17.291 15.4477 17.3824 15.5391 17.4941 15.5391H20.5917C20.7035 15.5391 20.7949 15.4477 20.7949 15.3359V14.1172C20.7949 14.0055 20.7035 13.9141 20.5917 13.9141ZM12.1189 8.18848H11.0195C10.8621 8.18848 10.7351 8.31543 10.7351 8.47285V14.7697C10.7351 14.8611 10.7783 14.9449 10.8519 14.9982L14.6326 17.7557C14.7595 17.8471 14.9373 17.8217 15.0287 17.6947L15.6812 16.8035V16.801C15.7726 16.674 15.7447 16.4963 15.6177 16.4049L12.4007 14.0791V8.47285C12.4033 8.31543 12.2738 8.18848 12.1189 8.18848Z"
              fill="#1B99D4" />
            <path
              d="M20.4344 17.1107H18.9668C18.8246 17.1107 18.6901 17.1844 18.6139 17.3063C18.2914 17.8166 17.9156 18.2889 17.484 18.7205C16.7401 19.4645 15.8742 20.0484 14.9119 20.4547C13.9141 20.8762 12.8553 21.0895 11.7635 21.0895C10.6692 21.0895 9.61037 20.8762 8.61506 20.4547C7.65275 20.0484 6.78693 19.4645 6.04299 18.7205C5.29904 17.9766 4.71506 17.1107 4.30881 16.1484C3.88732 15.1531 3.67404 14.0943 3.67404 13C3.67404 11.9057 3.88732 10.8494 4.30881 9.85157C4.71506 8.88926 5.29904 8.02344 6.04299 7.2795C6.78693 6.53555 7.65275 5.95157 8.61506 5.54532C9.61037 5.12383 10.6717 4.91055 11.7635 4.91055C12.8578 4.91055 13.9166 5.12383 14.9119 5.54532C15.8742 5.95157 16.7401 6.53555 17.484 7.2795C17.9156 7.71114 18.2914 8.1834 18.6139 8.69376C18.6901 8.81563 18.8246 8.88926 18.9668 8.88926H20.4344C20.6096 8.88926 20.7213 8.70645 20.6426 8.55157C18.9871 5.2584 15.6305 3.11797 11.8828 3.07481C6.39592 3.00626 1.8383 7.49786 1.82814 12.9797C1.81799 18.4717 6.26896 22.9277 11.761 22.9277C15.5569 22.9277 18.9694 20.7797 20.6426 17.4484C20.7213 17.2936 20.607 17.1107 20.4344 17.1107Z"
              fill="#1B99D4" />
          </svg>
          <p class="text-[#646464]">Life time accessibility</p>
        </div>
        <div class="flex gap-2 items-center text-base">
          <svg xmlns="http://www.w3.org/2000/svg" width="26" height="26" viewBox="0 0 26 26" fill="none">
            <path
              d="M21.6667 19.5C22.8583 19.5 23.8225 18.525 23.8225 17.3333L23.8333 5.41667C23.8333 4.225 22.8583 3.25 21.6667 3.25H4.33333C3.14167 3.25 2.16667 4.225 2.16667 5.41667V17.3333C2.16667 18.525 3.14167 19.5 4.33333 19.5H0C0 20.6917 0.975 21.6667 2.16667 21.6667H23.8333C25.025 21.6667 26 20.6917 26 19.5H21.6667ZM4.33333 5.41667H21.6667V17.3333H4.33333V5.41667ZM13 20.5833C12.4042 20.5833 11.9167 20.0958 11.9167 19.5C11.9167 18.9042 12.4042 18.4167 13 18.4167C13.5958 18.4167 14.0833 18.9042 14.0833 19.5C14.0833 20.0958 13.5958 20.5833 13 20.5833Z"
              fill="#1B99D4" />
          </svg>
          <p class="text-[#646464]">Live project experience</p>
        </div>
      </div>

      <div class="flex flex-col justify-center border border-[#D9D9D9] rounded-xl p-8">
        <h2 class="text-base text-[#646464] mb-[27px]">We are driven by the idea of program affordability. So, we give
          you several
          financial options to manage
          and budget the expenses of your course.</h2>
        <p class="text-[27px] text-[#2C2C2C] font-bold">Starting at ₹ 120,000 + GST</p>
        <div class="flex justify-between items-end">
          <p class="text-[#2C2C2C] text-base">EMI starting from: ₹ 5,900/month</p>
          <a href="#"
            class="bg-[#1b99d4] inline-block text-[16px] text-white font-semibold py-2.5 px-5 rounded-[5px] cursor-pointer hover:bg-[#1b99d4d2]">Apply
            Now</a>
        </div>
      </div>
    </div>
  </section>
  <!-- Course Highlights Section end -->

  <!-- Next Cohort Details Section -->
  <section class="container py-[70px]">
    <h2 class="text-center text-4xl font-semibold mb-[25px]">Next Cohort Details</h2>
    <div class="border border-[#D9D9D9] rounded-xl">
      <div class="text-[#272727] flex items-center justify-around py-6 ">
        <p class="text-6xl font-bold">19 <sup><sup><span
                class="text-sm font-medium tracking-[4px]">MAR</span></sup></sup>
        </p>
        <p class="text-2xl font-medium">Weekend Batch [Sat - Sun]</p>
        <a href="#"
          class="bg-[#1b99d4] text-[16px] text-white font-semibold py-2.5 px-5 rounded-[5px] cursor-pointer hover:bg-[#1b99d4d2]">Enroll
          Now</a>
      </div>
      <hr class="border-t-2 border-dashed border-[#777d8c33]">
      <div class="flex justify-around py-[30px]">
        <div>
          <p class="text-[#272727] text-base font-medium">Batch</p>
          <p class="text-[#777D8C] text-lg">Morning</p>
        </div>
        <div>
          <p class="text-[#272727] text-base font-medium">Time</p>
          <p class="text-[#777D8C] text-lg">09:00 am-12:00 pm</p>
        </div>
        <div>
          <p class="text-[#272727] text-base font-medium">Seat</p>
          <p class="text-[#777D8C] text-lg">Available</p>
        </div>
        <div>
          <p class="text-[#272727] text-base font-medium">Venue</p>
          <p class="text-[#777D8C] text-lg">Virtual Hall</p>
        </div>
      </div>
    </div>
  </section>
  <!-- Next Cohort Details Section end -->

  <!-- DISCOVER OUR MENTORS Section -->
  <section class="container pt-[20px] pb-[70px]">
    <div class="text-center">
      <p class="text-[#1B99D4] text-base font-semibold tracking-[1.6px]">DISCOVER OUR MENTORS</p>
      <h2 class="text-4xl font-semibold mt-3.5 text-[#231F40]">We have Industry Experts as Mentor who guide you with
        Career Planning & Interview Preparation
      </h2>
    </div>

    <!-- cart -->
    <div class="flex justify-between mt-[57px]">
      <div class="max-w-sm mx-auto bg-white rounded-xl shadow-[1px_5px_50px_0px_rgba(84,99,122,0.10)] overflow-hidden">
        <div>
          <img class="w-full h-68 object-cover" src="../assets/img/sachinImage 1.png" alt="">
        </div>
        <div class="flex flex-col gap-8 p-4 mt-5">
          <div class="flex items-center gap-12">
            <div>
              <h2 class="text-xl font-semibold leading-8">Sachin Sharma</h2>
              <p class="text-[#4D607D] text-base mt-2.5 leading-1">Managing Director</p>
            </div>
            <div>
              <img src="../assets/img/Microsoft-logo.png" alt="">
            </div>
          </div>
          <div class="flex gap-2.5 items-center mt-3.5">
            <img src="../assets/img/linkedin.png" alt="">
            <a href="#" class="text-[#006DD9] text-lg">View Profile</a>
          </div>
        </div>
      </div>
      <div class="max-w-sm mx-auto bg-white rounded-xl shadow-[1px_5px_50px_0px_rgba(84,99,122,0.10)] overflow-hidden">
        <div>
          <img class="w-full h-68 object-cover" src="../assets/img/sachinImage 2.png" alt="">
        </div>
        <div class="flex flex-col gap-8 p-4 mt-5">
          <div class="flex items-center gap-12">
            <div>
              <h2 class="text-xl font-semibold leading-8">Santosh Kumar
                Mishra</h2>
              <p class="text-[#4D607D] text-base mt-2.5 leading-1">Managing Director</p>
            </div>
            <div>
              <img src="../assets/img/Microsoft-logo.png" alt="">
            </div>
          </div>
          <div class="flex gap-2.5 items-center mt-3.5">
            <img src="../assets/img/linkedin.png" alt="">
            <a href="#" class="text-[#006DD9] text-lg">View Profile</a>
          </div>
        </div>
      </div>
      <div class="max-w-sm mx-auto bg-white rounded-xl shadow-[1px_5px_50px_0px_rgba(84,99,122,0.10)] overflow-hidden">
        <div>
          <img class="w-full h-68 object-cover" src="../assets/img/sachinImage 3.png" alt="">
        </div>
        <div class="flex flex-col gap-8 p-4 mt-5">
          <div class="flex items-center gap-12">
            <div>
              <h2 class="text-xl font-semibold leading-8">Prem Kumar</h2>
              <p class="text-[#4D607D] text-base mt-2.5 leading-1">Mentorship</p>
            </div>
            <div>
              <img src="../assets/img/Microsoft-logo.png" alt="">
            </div>
          </div>
          <div class="flex gap-2.5 items-center mt-3.5">
            <img src="../assets/img/linkedin.png" alt="">
            <a href="#" class="text-[#006DD9] text-lg">View Profile</a>
          </div>
        </div>
      </div>
    </div>
    <div class="text-center mt-[107px]">
      <a href="#"
        class="bg-[#1b99d4] text-[16px] text-white font-semibold py-2.5 px-5 rounded-[5px] cursor-pointer hover:bg-[#1b99d4d2]">More
        Mentor Details</a>
    </div>
  </section>
  <!-- DISCOVER OUR MENTORS Section end -->

  <!-- Thousands of stories section -->
  <section class="container py-[70px]">
    <div class="flex justify-between gap-[78px]">
      <div class="w-1/2">
        <h2 class="text-[48px] font-bold">Thousands of stories <br> of growth</h2>
        <p class="text-[#00000099]">Find out how our Learners transformed their careers after <br> learning witH us.</p>
      </div>

      <div class="w-1/2 flex flex-col gap-6 ">
        <svg xmlns="http://www.w3.org/2000/svg" width="50" height="43" viewBox="0 0 50 43" fill="none">
          <path
            d="M50 0.425743L48.847 8.27833C45.9818 8.08911 43.8155 8.59369 42.348 9.79208C40.8805 10.9905 39.9371 12.6304 39.5178 14.7118C39.0985 16.7932 38.9937 19.0953 39.2034 21.6183H50V43H29.4549V18.78C29.4549 12.1573 31.2369 7.17455 34.8008 3.83168C38.4347 0.425742 43.501 -0.709571 50 0.425743ZM20.5451 0.425743L19.392 8.27833C16.5269 8.08911 14.3606 8.59369 12.8931 9.79208C11.4256 10.9905 10.4822 12.6304 10.0629 14.7118C9.6436 16.7932 9.53878 19.0953 9.74843 21.6183H20.5451V43H0V18.78C0 12.1573 1.78197 7.17455 5.34591 3.83168C8.97973 0.425742 14.0461 -0.709571 20.5451 0.425743Z"
            fill="#1B99D4" />
        </svg>
        <p class="text-[#767676] text-base">“As a senior engineer I have specially reviewed the System Design content
          and live
          classes of My_Tutor and I
          found it more on the implementation side instead of theoretical concepts which helps to work in real-time
          environment in the organization. I would recommend My_Tutor course to get expertise in System Design.”</p>

        <div class="flex items-center justify-between">
          <div class="flex items-center gap-6">
            <img class="w-[78px] h-[78px] rounded-full" src="../assets/img/sachinImage 3.png" alt="">
            <div class="flex flex-col">
              <div>
                <p class="text-[#1B99D4] text-xl font-semibold">Prem Kumar</p>
                <div class="text-yellow-500">
                  <i class=" fa-solid fa-star"></i>
                  <i class="fa-solid fa-star"></i>
                  <i class="fa-solid fa-star"></i>
                  <i class="fa-solid fa-star"></i>
                  <i class="fa-regular fa-star"></i>
                </div>
              </div>
            </div>
          </div>

          <div class="flex gap-2.5 items-center mt-3.5">
            <img src="../assets/img/linkedin.png" alt="">
            <a href="#" class="text-[#006DD9] text-lg">View Profile</a>
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- Thousands of stories section end -->

  <!-- Frequently Asked Questions Section -->
  <section class="container py-[70px]">
    <div class="text-center">
      <p class="text-[#1B99D4] text-base font-semibold tracking-[1.6px]">ASK YOUR QUESTIONS</p>
      <h2 class="text-4xl font-semibold mt-3.5 text-[#231F40]">Frequently Asked Questions
      </h2>
    </div>

    <!-- accordion -->
    <div class="wrapper text-[#00000099] font-medium flex flex-col w-5/6 justify-center mx-auto">
      <!-- tab  1 -->
      <div class="mb-3 bg-white px-5 py-3 shadow-lg rounded-md relative">
        <input type="radio" name="faq" id="faq1" class="appearance-none peer">
        <label for="faq1"
          class="flex items-center text-lg font-semibold cursor-pointer after:absolute after:content-['+'] after:left-5 after:text-2xl after:text-[#1B99D4] peer-checked:after:transform peer-checked:after:rotate-45">
          <h3 class="px-5 text-xl text-[#212121]">How to enroll for a Course?</h3>
        </label>
        <div class=" mt-5 h-0 overflow-hidden transition ease-in-out duration-500 peer-checked:h-full">
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempora, ipsa in exercitationem animi nobis iste
            fuga natus. Lorem ipsum dolor sit amet consectetur adipisicing elit. Assumenda temporibus deserunt odit
            asperiores ipsa accusantium iusto eos tempore vel distinctio, aspernatur dolore numquam. Quam iure
            perspiciatis, commodi distinctio cupiditate eaque.</p>
        </div>
      </div>

      <!-- tab  2 -->
      <div class="mb-3 bg-white px-5 py-3 shadow-lg rounded-md relative">
        <input type="radio" name="faq" id="faq2" class="appearance-none peer">
        <label for="faq2"
          class="flex items-center text-lg font-semibold cursor-pointer after:absolute after:content-['+']   after:left-5 after:text-2xl after:text-[#1B99D4]   peer-checked:after:transform peer-checked:after:rotate-45">
          <h3 class="px-5 text-xl text-[#212121]">Can I get the recordings of my previous lectures?</h3>
        </label>
        <div class="mt-5 h-0 overflow-hidden transition ease-in-out duration-500 peer-checked:h-full">
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellendus tempore consequuntur repellat rerum,
            ipsa aperiam, non quam iste quae iusto omnis illo earum eveniet, unde animi odit esse iure pariatur?</p>
        </div>
      </div>

      <!-- tab  3 -->
      <div class="mb-3 bg-white px-5 py-3 shadow-lg rounded-md relative">
        <input type="radio" name="faq" id="faq3" class="appearance-none peer">
        <label for="faq3"
          class="flex items-center text-lg font-semibold cursor-pointer after:absolute after:content-['+'] after:left-5 after:text-2xl after:text-[#1B99D4]   peer-checked:after:transform peer-checked:after:rotate-45">
          <h3 class="px-5 text-xl text-[#212121]">Who would be the instructor for enrolled course?</h3>
        </label>
        <div class="mt-5 h-0 overflow-hidden transition ease-in-out duration-500 peer-checked:h-full">
          <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Nesciunt, vero rem possimus voluptatum aliquam
            quaerat explicabo tempora corporis tempore sapiente.</p>
        </div>
      </div>

      <!-- tab  4 -->
      <div class="mb-3 bg-white px-5 py-3 shadow-lg rounded-md relative">
        <input type="radio" name="faq" id="faq4" class="appearance-none peer">
        <label for="faq4"
          class="flex items-center text-lg font-semibold cursor-pointer after:absolute after:content-['+'] after:left-5 after:text-2xl after:text-[#1B99D4]   peer-checked:after:transform peer-checked:after:rotate-45">
          <h3 class="px-5 text-xl text-[#212121]">What kind of placement support will be given post completion of
            program?</h3>
        </label>
        <div class="mt-5 h-0 overflow-hidden transition ease-in-out duration-500 peer-checked:h-full">
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquid omnis eum dolores cumque quas, vero
            aliquam neque corrupti, ut vel, minus vitae nostrum. Sunt atque praesentium, iste laboriosam expedita quo ut
            obcaecati inventore officiis alias maxime! Sapiente, placeat iure. Optio.</p>
        </div>
      </div>
    </div>
  </section>
  <!-- Frequently Asked Questions Section end -->

  <!-- Footer Section -->
  <section class="py-[70px] bg-[#1B99D4] text-white">
    <div class="container flex justify-between">
      <div>
        <div>
          <!-- logo -->
          <div class="flex items-center gap-2.5 cursor-pointer">
            <svg xmlns="http://www.w3.org/2000/svg" width="44" height="42" viewBox="0 0 44 42" fill="none">
              <path
                d="M21.6 41.7C9.90002 41.5 0.400025 32.1 0.600025 20.7C0.800025 9.39996 10.8 -4.33922e-05 22.3 0.299957C34 0.599957 43.3 9.99996 43.2 21.4C43.1 32.7 33.4 41.9 21.6 41.7Z"
                fill="white" />
              <path
                d="M23.2002 20.7001C25.7002 19.6001 27.7002 20.3001 29.3002 22.3001C31.3002 24.8001 32.4002 27.6001 31.9002 30.8001C31.8002 31.9001 30.4002 32.0001 29.5002 32.3001C24.4002 33.9001 19.3002 33.6001 14.1002 32.2001C12.1002 31.6001 11.5002 30.5001 11.9002 28.7001C12.4002 26.0001 13.6002 23.6001 15.5002 21.6001C16.8002 20.2001 18.3002 19.6001 20.1002 20.6001C21.1002 20.3001 21.9002 20.6001 21.9002 21.7001C22.0002 23.9001 22.0002 26.2001 21.9002 28.4001C21.9002 26.6001 21.9002 24.7001 22.0002 22.9001C22.2002 22.1001 21.7002 20.9001 23.2002 20.7001Z"
                fill="#1B99D4" />
              <path
                d="M20.3 19.7998C21.3 19.8998 22.2001 19.8998 23.2001 19.9998C23.2001 20.1998 23.2001 20.4998 23.2001 20.6998C21.4001 23.2998 23.2 26.3998 21.6 29.0998C21.6 27.1998 21.6 25.3998 21.6 23.4998C21.6 22.3998 22 20.9998 20.3 20.5998C20.3 20.2998 20.3 20.0998 20.3 19.7998Z"
                fill="white" />
              <path
                d="M22.1 19.4998C25.4689 19.4998 28.2 16.7687 28.2 13.3998C28.2 10.0309 25.4689 7.2998 22.1 7.2998C18.7311 7.2998 16 10.0309 16 13.3998C16 16.7687 18.7311 19.4998 22.1 19.4998Z"
                fill="#1B99D4" />
              <path d="M22.9002 21.4004H21.5002V29.1004H22.9002V21.4004Z" fill="white" />
            </svg>
            <h2 class="text-[22px] font-bold">My_Tutor</h2>
          </div>

          <p class="font-medium text-base mt-4 leading-[28px]">It is a long established fact that a <br>
            reader will be distracted by the <br>
            readable content of a page when <br>
            looking at its layout. The point of <br> using Lorem Ipsum.</p>
          <div class="flex gap-3.5 mt-5 font-bold text-[22px]">
            <div
              class="py-4 px-6 bg-[#32a3d8] text-white cursor-pointer transition duration-300 ease-in-out hover:scale-125">
              <a href="#"><i class="fa-brands fa-facebook-f text-xl"></i></a>
            </div>
            <div
              class="py-4 px-6 bg-[#32a3d8] text-white cursor-pointer transition duration-300 ease-in-out hover:scale-125">
              <a href="#"><i class="fa-brands fa-linkedin-in text-xl"></i></a>
            </div>
            <div
              class="py-4 px-6 bg-[#32a3d8] text-white cursor-pointer transition duration-300 ease-in-out hover:scale-125">
              <a href="#"><i class="fa-brands fa-pinterest-p text-xl"></i></a>
            </div>
            <div
              class="py-4 px-6 bg-[#32a3d8] text-white cursor-pointer transition duration-300 ease-in-out hover:scale-125">
              <a href="#"><i class="fa-brands fa-twitter text-xl"></i></a>
            </div>
          </div>
        </div>
      </div>

      <div class="flex flex-col gap-4">
        <h2 class="mb-[36px] text-2xl font-semibold">Explore</h2>
        <a href="#" class="hover:underline"><i class="fa-solid fa-angles-right"></i> About Us</a>
        <a href="#" class="hover:underline"><i class="fa-solid fa-angles-right"></i> Blog</a>
        <a href="#" class="hover:underline"><i class="fa-solid fa-angles-right"></i> Campus Program</a>
        <a href="#" class="hover:underline"><i class="fa-solid fa-angles-right"></i> Become a Mentor</a>
        <a href="#" class="hover:underline"><i class="fa-solid fa-angles-right"></i> Contact us</a>
        <a href="#" class="hover:underline"><i class="fa-solid fa-angles-right"></i> Hire From us</a>
      </div>

      <div class="flex flex-col gap-4">
        <h2 class="mb-[36px] text-2xl font-semibold">Useful Links</h2>
        <a href="#" class="hover:underline"><i class="fa-solid fa-angles-right"></i> Privacy Policy</a>
        <a href="#" class="hover:underline"><i class="fa-solid fa-angles-right"></i> Terms of use</a>
        <a href="#" class="hover:underline"><i class="fa-solid fa-angles-right"></i> Refund Policy</a>
      </div>

      <div class="flex flex-col gap-4">
        <h2 class="mb-[36px] text-2xl font-semibold">Contact Info</h2>
        <div class="flex items-start gap-2">
          <i class="fa-solid fa-location-dot"></i>
          <p>4517 Washington Ave. Manchester, <br> Kentucky 39495</p>
        </div>
        <div class="flex items-center gap-2">
          <i class="fa-solid fa-phone"></i>
          <p>+91-9024250272</p>
        </div>
        <div class="flex items-center gap-2">
          <i class="fa-solid fa-envelope"></i>
          <a href="https://www.salauddinsakib99@gmail.com" target="_blank"
            class="hover:underline">salauddinsakib99@gmail.com</a>
        </div>
      </div>
    </div>
  </section>
</template>