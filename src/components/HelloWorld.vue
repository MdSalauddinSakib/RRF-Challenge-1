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
          <h2 class="text-xl font-semibold leading-8 mt-1.5">Shaumaya Qha</h2>
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
          <h2 class="text-xl font-semibold leading-8 mt-1.5">Subhangi Duhan</h2>
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
          <h2 class="text-xl font-semibold leading-8 mt-1.5">Paras Yadav</h2>
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
      <a class=" bg-white text-[#1B99D4] p-4 mt-10 flex items-center flex items-center justify-between w-[215px] rounded-[5px] border border-[#1B99D4] hover:bg-[#1B99D4] hover:text-white"
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
            <p class="text-[28px] font-bold leading-[23px] px-[61px] py-[10px]">10+ <br> <span
                class="text-base font-normal">Projects</span></p>
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
          database of authorized
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
</template>