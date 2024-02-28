<template>

  <header class="w-full sm:h-16 p-4 h-30 border-b md:border-gray-300 md:shadow-md md:fixed top-0 left-0 bg-white z-50">
    <nav class="mr-auto ml-auto flex flex-col sm:flex-row sm:justify-between sm:items-center gap-2" style="max-width: 1280px;">
      <div class="flex flex-row justify-start items-center gap-2">
        <svg class="w-10 h-8 text-[#00b4d8]" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 24 24">
          <path fill-rule="evenodd" d="M5 10.2c.6 0 1 .4 1 1v.2l6 3.5 6-3.5v-.2a1 1 0 1 1 2 0v.8c0 .4-.2.7-.5.9l-7 4a1 1 0 0 1-1 0l-7-4A1 1 0 0 1 4 12v-.8c0-.6.5-1 1-1Zm0 5c.6 0 1 .4 1 1v.2l6 3.4 6-3.4V16a1 1 0 1 1 2 0v.9c0 .3-.2.6-.5.8l-7 4a1 1 0 0 1-1 0l-7-4A1 1 0 0 1 4 17v-1c0-.5.4-1 1-1Z" clip-rule="evenodd"/>
          <path d="M12.5 2.1a1 1 0 0 0-1 0l-7 4a1 1 0 0 0 0 1.8l7 4c.3.2.7.2 1 0l7-4a1 1 0 0 0 0-1.7l-7-4Z"/>
        </svg>
        <h3 class="font-bold text-xl">Joseph Jr.</h3>
      </div>
      <div>
        <ul class="flex sm:flex-row">
          <li class="mr-5 font-medium"><a href="#about" class="hover:text-blue-800">About</a></li>
          <li class="mr-5 font-medium"><a href="#skills" class="hover:text-blue-800">Skills</a></li>
          <li class="mr-5 font-medium"><a href="#projects" class="hover:text-blue-800">Projects</a></li>
          <li class="font-medium"><a href="#contact" class="hover:text-blue-800">Contact</a></li>
        </ul>
      </div>
    </nav>
  </header>

  <section class="h-auto lg:h-screen md:h-screen flex flex-col md:flex-row md:items-center mx-auto px-4 mt-20 lg:mt-0" style="max-width: 1280px;">
    <div class="flex flex-col md:flex-row justify-between max-w-2xl md:max-w-4xl lg:max-w-6xl gap-3">
      <div class="md:w-1/2 md:order-1">
        <img src="../assets/profile4.png" alt="Profile Image" class="rounded-lg mx-auto w-72 h-72 md:w-96 md:h-96">
      </div>
      <div class="md:w-1/2 text-center md:text-left">
        <p class="text-xl font-medium mb-4">Hello, <span class="text-blue-800">I'm</span></p>
        <h1 class="text-4xl font-bold text-blue-800 mb-5">Joseph Dela Cruz Jr.</h1>
        <p class="text-2xl mb-5 font-semibold">Software Engineer</p>
        <p class="text-xl text-justify leading-8">I'm a skilled and creative developer with a passion and dedication in 
          creating fully functional applications, responsive and user-friendly. I've worked on diverse projects ranging from web applications, 
          desktop applications, AI systems, and Arduino.</p>
        <div class="flex flex-col md:flex-row mt-5">
          <a href="#contact" class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded mb-2 md:mb-0 md:mr-2">Get in touch</a>
          <a href="resume.pdf" target="_blank" class="bg-transparent hover:bg-blue-500 text-blue-700 font-semibold hover:text-white py-2 px-4 border border-blue-500 hover:border-transparent rounded">Resume</a>
        </div>
      </div>
    </div>
  </section>

  <section id="about" class="h-auto lg:h-72 md:h-72 mx-auto px-4 mt-10 lg:mt-0 mb-10" style="max-width: 1280px;">
    <div class="flex flex-col md:flex-row justify-between items-center w-full gap-6">
      <div class="md:w-1/4">
        <img src="../assets/profile1.jpg" alt="Profile Image" class="rounded-full mx-auto w-56 h-56 md:w-48 md:h-48 lg:w-64 lg:h-64 shadow-2xl">
      </div>
      <div class="md:w-9/12">
        <div class="relative flex flex-col w-full mx-auto">
          <div class="p-6">
            <h5 class="block mb-2 text-4xl font-semibold leading-snug tracking-normal text-blue-800 text-center">
              About Me
            </h5>
            <p class="block text-base text-justify">
              Passionate and adaptive, I am a dedicated software engineer known for crafting innovative solutions and thriving in dynamic environments. 
              My love for coding goes beyond the lines of code, and I am committed to delivering excellence in every project. With a keen eye for detail 
              and a collaborative spirit, I work seamlessly in teams, bringing my adaptive mindset and passion for problem-solving to create impactful 
              and scalable solutions. If you're looking for a software engineer who excels in adaptability, dedication, and collaborative teamwork, 
              I'm eager to contribute my skills to your projects. Explore my portfolio to see the exciting projects I've had the privilege to work on!
            </p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section id="skills" class="h-auto lg:h-96 md:h-96 mx-auto px-4 mt-10 md:mt-40 mb-10" style="max-width: 1280px;">
    <h5 class="text-center block mb-10 text-4xl font-semibold leading-snug tracking-normal text-blue-800">My Skills</h5>
    <div class="flex flex-col md:flex-row justify-between items-center w-full gap-6">
      <div class="bg-white shadow-md bg-clip-border h-72 w-full rounded">
        <svg class="w-12 h-12 text-[#ff661a] bg-blue-50 mx-auto shadow-md bg-clip-border mt-4 mb-2 rounded-xl" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 24 24">
          <path d="m3 2 1.6 17.8L12 22l7.5-2.2L21 2H3Zm14 6H9l.2 2H17l-.6 6.6-4.2 1.4-4.3-1.4-.3-3h2l.2 1.4 2.4.8 2.3-.7.3-3H7.4L7 6h10.4L17 8Z"/>
        </svg>
        <h3 class="mb-2 text-2xl font-semibold text-center">Front end</h3>
        <p class="text-center">HTML <br> CCS <br> Javascript  <br> Bootstrap <br> Tailwindcss <br> Vuejs</p>
      </div>
      <div class="bg-white shadow-md bg-clip-border h-72 w-full rounded">
        <svg class="w-12 h-12 text-[#66b3ff] bg-blue-50 mx-auto shadow-md bg-clip-border mt-4 mb-2 rounded-xl" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24">
          <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="m8 8-4 4 4 4m8 0 4-4-4-4m-2-3-4 14"/>
        </svg>
        <h3 class="mb-2 text-2xl font-semibold text-center">Back end</h3>
        <p class="text-center">Php <br> Python <br> Laravel <br> Flask <br> Mysql <br> Microsoft Sql server</p>
      </div>
      <div class="bg-white shadow-md bg-clip-border h-72 w-full rounded">
        <svg class="w-12 h-12 text-[#ffbf80] bg-blue-50 mx-auto shadow-md bg-clip-border mt-4 mb-2 rounded-xl" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 24 24">
          <path d="M12 6.2 7 9.4l5 3.2-5 3.2-5-3.3 5-3.1-5-3.2L7 3l5 3.2ZM7 17.8l5-3.2 5 3.2-5 3.2-5-3.2Z"/>
          <path d="m12 12.5 5-3.1-5-3.2L17 3l5 3.2-5 3.2 5 3.2-5 3.2-5-3.3Z"/>
        </svg>
        <h3 class="mb-2 text-2xl font-semibold text-center">Other</h3>
        <p class="text-center">Git <br> Github <br> Netlify <br> VS code <br> Audrino <br> Computer Vision</p>
      </div>
    </div>
  </section>

  <section id="projects" class="h-auto mx-auto px-4 mt-10 md:mt-40 mb-10" style="max-width: 1280px;">
    <h5 class="text-center block mb-10 text-4xl font-semibold leading-snug tracking-normal text-blue-800">Recent Projects</h5>
    
    <div class="grid grid-rows-2 grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-x-8 gap-y-8">
      <div class="w-auto rounded overflow-hidden shadow-lg bg-white">
        <img class="w-full" src="../assets/forecast.jpg" alt="forecast">
        <div class="flex flex-col md:min-h-[450px]">
          <div class="px-6 py-4">
            <div class="font-bold text-xl mb-2">Budget Forecasting App</div><hr>
            <p class="text-gray-700 text-base text-justify mt-2">
              This application is a simulation tool designed for hoteliers, empowering them to make informed decisions by providing precise 
              forecasts and enabling optimal pricing and revenue management strategies. By inputting anticipated revenue and expenses, the 
              tool generates a comprehensive hotel budget simulation, including calculations for the number of rooms, occupancy rates, and 
              average daily rates (ADR) on a monthly basis.
            </p>
            <p class="text-sm font-semibold mt-5">
              Tech used: Vuejs, Bootstrap, Javascript
            </p>
          </div>
          <div class="px-6 pt-4 pb-6 self-start mt-auto">
            <a href="https://budgetforecast.netlify.app" target="_blank" class="inline-flex items-center px-3 py-2 text-sm font-medium text-center text-white bg-gray-700 rounded-lg hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-gray-700 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
              View more
              <svg class="rtl:rotate-180 w-3.5 h-3.5 ms-2" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 14 10">
                  <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M1 5h12m0 0L9 1m4 4L9 9"/>
              </svg>
            </a>
          </div>
        </div>
      </div>

      <div class="w-auto rounded overflow-hidden shadow-lg bg-white">
        <img class="w-full" src="../assets/todolist.jpg" alt="todo app">
        <div class="flex flex-col md:min-h-[450px]">
          <div class="px-6 py-4">
            <div class="font-bold text-xl mb-2">TodoList App</div><hr>
            <p class="text-gray-700 text-base text-justify mt-2"> 
              This application revolves around a responsive and straightforward to-do list, focusing on basic CRUD operations for creating, 
              updating, and deleting tasks with ease on any device.
            </p>
            <p class="text-sm font-semibold mt-5">
              Tech used: Vuejs, Vuetify, Nuxtjs, Vuex, Local Storage
            </p>
          </div>
          <div class="px-6 pt-4 pb-6 self-start mt-auto">
            <a href="https://todolistvuejs24.netlify.app" target="_blank" class="mt-auto inline-flex items-center px-3 py-2 text-sm font-medium text-center text-white bg-gray-700 rounded-lg hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-gray-700 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
              View more
              <svg class="rtl:rotate-180 w-3.5 h-3.5 ms-2" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 14 10">
                  <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M1 5h12m0 0L9 1m4 4L9 9"/>
              </svg>
            </a>
          </div> 
        </div>
      </div>

      <div class="w-auto rounded overflow-hidden shadow-lg bg-white">
        <img class="w-full" src="../assets/rikdo.jpg" alt="RIKDO dbms">
        <div class="flex flex-col md:min-h-[450px]">
          <div class="px-6 py-4">
            <div class="font-bold text-xl mb-2">Document Management System</div><hr>
            <p class="text-gray-700 text-base text-justify mt-2">
              This thesis project provides a student-centric platform where scholars can submit their research documents. This system ensures 
              efficient evaluation by professors, complete with real-time email notifications, and upon meeting criteria, approved documents 
              are seamlessly posted online for future researchers' reference, fostering a collaborative and accessible academic environment.
            </p>
            <p class="text-sm font-semibold mt-5">
              Tech used: Php, Ajax, Argon Bootstrap, Xampp, Mysql, Godaddy Hosting Service, CPanel, SMTP Email, SSL
            </p>
          </div>
          <div class="px-6 pt-4 pb-6 self-start mt-auto">
            <a href="https://github.com/josephjrdlc21/rikdo-dbms.git" target="_blank" class="inline-flex items-center px-3 py-2 text-sm font-medium text-center text-white bg-gray-700 rounded-lg hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-gray-700 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
              View more
              <svg class="rtl:rotate-180 w-3.5 h-3.5 ms-2" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 14 10">
                  <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M1 5h12m0 0L9 1m4 4L9 9"/>
              </svg>
            </a>
          </div>
        </div>
      </div>

      <div class="w-auto rounded overflow-hidden shadow-lg bg-white">
        <img class="w-full" src="../assets/aoi.jpg" alt="aoi">
        <div class="flex flex-col md:min-h-[450px]">
          <div class="px-6 py-4">
            <div class="font-bold text-xl mb-2">Optical Inspection App</div><hr>
            <p class="text-gray-700 text-base text-justify mt-2">
              The application was empowered by computer vision with Python. Specifically designed for notebook motherboards, this system boasts an impressive 
              80 to 90 percent accuracy rate in flawlessly detecting defective components, ensuring a reliable and efficient quality control process.
            </p>
            <p class="text-sm font-semibold mt-5">
              Tech used: Python, OpenCv, Microsoft SQL server, Python tkinter, IIS Manager
            </p>
          </div>
          <div class="px-6 pt-4 pb-6 self-start mt-auto">
            <a href="https://github.com/josephjrdlc21/aoi-inspect.git" target="_blank" class="inline-flex items-center px-3 py-2 text-sm font-medium text-center text-white bg-gray-700 rounded-lg hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-gray-700 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
              View more
              <svg class="rtl:rotate-180 w-3.5 h-3.5 ms-2" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 14 10">
                  <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M1 5h12m0 0L9 1m4 4L9 9"/>
              </svg>
            </a>
          </div>
        </div>
      </div>

      <div class="w-auto rounded overflow-hidden shadow-lg bg-white">
        <img class="w-full" src="../assets/crems.jpg" alt="crems">
        <div class="flex flex-col md:min-h-[450px]">
          <div class="px-6 py-4">
            <div class="font-bold text-xl mb-2">Item Management System</div><hr>
            <p class="text-gray-700 text-base text-justify mt-2">
              A web application tailored for jigs and fixtures. Customers can seamlessly request items, and with real-time status updates set by administrators, 
              track the progress of their requests. This user-friendly platform ensures efficient communication and transparency throughout the item management
              process.
            </p>
            <p class="text-sm font-semibold mt-5">
              Tech used: Php, Laravel, Bootstrap, Microsoft SQL server, IIS Manager
            </p>
          </div>
          <div class="px-6 pt-4 pb-6 self-start mt-auto">
            <a href="#" class="inline-flex items-center px-3 py-2 text-sm font-medium text-center text-white bg-gray-700 rounded-lg hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-gray-700 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
              View more
              <svg class="rtl:rotate-180 w-3.5 h-3.5 ms-2" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 14 10">
                  <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M1 5h12m0 0L9 1m4 4L9 9"/>
              </svg>
            </a>
          </div>
        </div>
      </div>

      <div class="w-auto rounded overflow-hidden shadow-lg bg-white">
        <img class="w-full" src="../assets/audrino.jpg" alt="audrino">
        <div class="flex flex-col md:min-h-[450px]">
          <div class="px-6 py-4">
            <div class="font-bold text-xl mb-2">Auto Switching Circuit</div><hr>
            <p class="text-gray-700 text-base text-justify mt-2">
              The application is powered by Arduino technology. This innovative solution simulates cable connections, automatically switching between cables for 
              testing purposes. Enhancing efficiency and precision in the testing process, this application ensures seamless and reliable testing 
              with minimal manual intervention.
            </p>
            <p class="text-sm font-semibold mt-5">
              Tech used: C++, Audrino
            </p>
          </div>
          <div class="px-6 pt-4 pb-6 self-start mt-auto">
            <a href="https://github.com/josephjrdlc21/auto-switch-circuit.git" target="_blank" class="inline-flex items-center px-3 py-2 text-sm font-medium text-center text-white bg-gray-700 rounded-lg hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-gray-700 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
              View more
              <svg class="rtl:rotate-180 w-3.5 h-3.5 ms-2" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 14 10">
                  <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M1 5h12m0 0L9 1m4 4L9 9"/>
              </svg>
            </a>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section id="contact" class="h-auto mx-auto px-4 mt-10 md:mt-40 mb-20" style="max-width: 1280px;">
    <h5 class="text-center block mb-10 text-4xl font-semibold leading-snug tracking-normal text-blue-800">Contact</h5>
    <div class="bg-white shadow-md bg-clip-border h-72 w-full rounded flex items-center justify-center">
      <div class="p-8">
        <p class="text-center text-base">I have experienced in building dynamic applications. <br>If you are interested in hiring me
          for your projects.<br>Please use the form to get in touch.<br> 
        </p>
        <h3 class="text-xl font-semibold text-center mt-4">You can also find me on the following channel</h3>
        <div class="flex flex-row justify-center items-center gap-4 mt-5">
          <a href="https://twitter.com/JosephJr_DLC" target="_blank">
            <svg class="w-[32px] h-[32px] bg-blue-500 text-white rounded-sm" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 24 24">
              <path fill-rule="evenodd" d="M22 5.9c-.7.3-1.5.5-2.4.6a4 4 0 0 0 1.8-2.2c-.8.5-1.6.8-2.6 1a4.1 4.1 0 0 0-6.7 1.2 4 4 0 0 0-.2 2.5 11.7 11.7 0 0 1-8.5-4.3 4 4 0 0 0 1.3 5.4c-.7 0-1.3-.2-1.9-.5a4 4 0 0 0 3.3 4 4.2 4.2 0 0 1-1.9.1 4.1 4.1 0 0 0 3.9 2.8c-1.8 1.3-4 2-6.1 1.7a11.7 11.7 0 0 0 10.7 1A11.5 11.5 0 0 0 20 8.5V8a10 10 0 0 0 2-2.1Z" clip-rule="evenodd"/>
            </svg>
          </a>
          <a href="https://www.linkedin.com/in/joseph-dela-cruz-jr-b3b457278/" target="_blank">
            <svg class="w-[32px] h-[32px] bg-blue-900 text-white rounded-sm" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 24 24">
              <path fill-rule="evenodd" d="M12.5 8.8v1.7a3.7 3.7 0 0 1 3.3-1.7c3.5 0 4.2 2.2 4.2 5v5.7h-3.2v-5c0-1.3-.2-2.8-2.1-2.8-1.9 0-2.2 1.3-2.2 2.6v5.2H9.3V8.8h3.2ZM7.2 6.1a1.6 1.6 0 0 1-2 1.6 1.6 1.6 0 0 1-1-2.2A1.6 1.6 0 0 1 6.6 5c.3.3.5.7.5 1.1Z" clip-rule="evenodd"/>
              <path d="M7.2 8.8H4v10.7h3.2V8.8Z"/>
            </svg>  
          </a>  
          <a href="https://github.com/josephjrdlc21" target="_blank">
            <svg class="w-[32px] h-[32px] bg-gray-100 text-gray-800 rounded-sm" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 24 24">
              <path fill-rule="evenodd" d="M12 2c-2.4 0-4.7.9-6.5 2.4a10.5 10.5 0 0 0-2 13.1A10 10 0 0 0 8.7 22c.5 0 .7-.2.7-.5v-2c-2.8.7-3.4-1.1-3.4-1.1-.1-.6-.5-1.2-1-1.5-1-.7 0-.7 0-.7a2 2 0 0 1 1.5 1.1 2.2 2.2 0 0 0 1.3 1 2 2 0 0 0 1.6-.1c0-.6.3-1 .7-1.4-2.2-.3-4.6-1.2-4.6-5 0-1.1.4-2 1-2.8a4 4 0 0 1 .2-2.7s.8-.3 2.7 1c1.6-.5 3.4-.5 5 0 2-1.3 2.8-1 2.8-1 .3.8.4 1.8 0 2.7a4 4 0 0 1 1 2.7c0 4-2.3 4.8-4.5 5a2.5 2.5 0 0 1 .7 2v2.8c0 .3.2.6.7.5a10 10 0 0 0 5.4-4.4 10.5 10.5 0 0 0-2.1-13.2A9.8 9.8 0 0 0 12 2Z" clip-rule="evenodd"/>
            </svg>
          </a>  
          <a href="https://www.facebook.com/josephjr.delacruz.16" target="_blank">
            <svg class="w-[32px] h-[32px] bg-blue-500 text-white rounded-sm" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 24 24">
              <path fill-rule="evenodd" d="M13.1 6H15V3h-1.9A4.1 4.1 0 0 0 9 7.1V9H7v3h2v10h3V12h2l.6-3H12V6.6a.6.6 0 0 1 .6-.6h.5Z" clip-rule="evenodd"/>
            </svg>
          </a>  
        </div>
      </div>
    </div>
    <h5 class="text-center block text-2xl font-semibold leading-snug tracking-normal mt-10">Get in Touch</h5>
    <form action="#" class="space-y-4 mx-auto mt-5 w-full max-w-[650px]">
      <div>
        <input type="text" id="name" class="shadow-sm bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-500 focus:border-primary-500 block w-full p-2.5 dark:border-gray-600 dark:placeholder-gray-400 dark:focus:ring-primary-500 dark:focus:border-primary-500 dark:shadow-sm-light" placeholder="Name" required>
      </div>
      <div>
        <input type="email" id="email" class="shadow-sm bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-500 focus:border-primary-500 block w-full p-2.5 dark:border-gray-600 dark:placeholder-gray-400 dark:focus:ring-primary-500 dark:focus:border-primary-500 dark:shadow-sm-light" placeholder="Email" required>
      </div>
      <div class="sm:col-span-2">
        <textarea id="message" rows="6" class="block p-2.5 w-full text-sm text-gray-900 bg-gray-50 rounded-lg shadow-sm border border-gray-300 focus:ring-primary-500 focus:border-primary-500 dark:border-gray-600 dark:placeholder-gray-400 dark:focus:ring-primary-500 dark:focus:border-primary-500" placeholder="Enter your message"></textarea>
      </div>
      <button type="submit" class="bg-blue-500 hover:bg-blue-700 text-white py-2 px-2 rounded block mx-auto">Send Message</button>
    </form>
  </section>

  <footer class="mt-10 md:mt-40 w-full h-32 bg-[#f2f2f2] mx-auto px-4" style="max-width: 1280px;">
    <div class="mt-4 border-t-2 border-white flex flex-col md:flex-row justify-between items-center gap-2">
      <div class="mt-5">
        <h3 class="font-semibold text-xl">Joseph Dela Cruz Jr.</h3>
      </div>
      <div class="mt-5">
        <div class="flex flex-row justify-between items-center gap-4">
          <a href="https://twitter.com/JosephJr_DLC" target="_blank">
            <svg class="w-[29px] h-[29px] text-gray-800 rounded-sm" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 24 24">
              <path fill-rule="evenodd" d="M22 5.9c-.7.3-1.5.5-2.4.6a4 4 0 0 0 1.8-2.2c-.8.5-1.6.8-2.6 1a4.1 4.1 0 0 0-6.7 1.2 4 4 0 0 0-.2 2.5 11.7 11.7 0 0 1-8.5-4.3 4 4 0 0 0 1.3 5.4c-.7 0-1.3-.2-1.9-.5a4 4 0 0 0 3.3 4 4.2 4.2 0 0 1-1.9.1 4.1 4.1 0 0 0 3.9 2.8c-1.8 1.3-4 2-6.1 1.7a11.7 11.7 0 0 0 10.7 1A11.5 11.5 0 0 0 20 8.5V8a10 10 0 0 0 2-2.1Z" clip-rule="evenodd"/>
            </svg>
          </a>
          <a href="https://www.linkedin.com/in/joseph-dela-cruz-jr-b3b457278/" target="_blank">
            <svg class="w-[29px] h-[29px] text-gray-800 rounded-sm" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 24 24">
              <path fill-rule="evenodd" d="M12.5 8.8v1.7a3.7 3.7 0 0 1 3.3-1.7c3.5 0 4.2 2.2 4.2 5v5.7h-3.2v-5c0-1.3-.2-2.8-2.1-2.8-1.9 0-2.2 1.3-2.2 2.6v5.2H9.3V8.8h3.2ZM7.2 6.1a1.6 1.6 0 0 1-2 1.6 1.6 1.6 0 0 1-1-2.2A1.6 1.6 0 0 1 6.6 5c.3.3.5.7.5 1.1Z" clip-rule="evenodd"/>
              <path d="M7.2 8.8H4v10.7h3.2V8.8Z"/>
            </svg>  
          </a>  
          <a href="https://github.com/josephjrdlc21" target="_blank">
            <svg class="w-[29px] h-[29px] text-gray-800 rounded-sm" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 24 24">
              <path fill-rule="evenodd" d="M12 2c-2.4 0-4.7.9-6.5 2.4a10.5 10.5 0 0 0-2 13.1A10 10 0 0 0 8.7 22c.5 0 .7-.2.7-.5v-2c-2.8.7-3.4-1.1-3.4-1.1-.1-.6-.5-1.2-1-1.5-1-.7 0-.7 0-.7a2 2 0 0 1 1.5 1.1 2.2 2.2 0 0 0 1.3 1 2 2 0 0 0 1.6-.1c0-.6.3-1 .7-1.4-2.2-.3-4.6-1.2-4.6-5 0-1.1.4-2 1-2.8a4 4 0 0 1 .2-2.7s.8-.3 2.7 1c1.6-.5 3.4-.5 5 0 2-1.3 2.8-1 2.8-1 .3.8.4 1.8 0 2.7a4 4 0 0 1 1 2.7c0 4-2.3 4.8-4.5 5a2.5 2.5 0 0 1 .7 2v2.8c0 .3.2.6.7.5a10 10 0 0 0 5.4-4.4 10.5 10.5 0 0 0-2.1-13.2A9.8 9.8 0 0 0 12 2Z" clip-rule="evenodd"/>
            </svg>
          </a>  
          <a href="https://www.facebook.com/josephjr.delacruz.16" target="_blank">
            <svg class="w-[29px] h-[29px] text-gray-800 rounded-sm" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 24 24">
              <path fill-rule="evenodd" d="M13.1 6H15V3h-1.9A4.1 4.1 0 0 0 9 7.1V9H7v3h2v10h3V12h2l.6-3H12V6.6a.6.6 0 0 1 .6-.6h.5Z" clip-rule="evenodd"/>
            </svg>
          </a>  
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
  
</script>

<style>
  body{
    background: #f2f2f2;
  }
</style>