<script setup></script>

<template>
  <div>
    <div class="grid grid-cols-1 place-items-center">
      <div class="text-2xl font-bold mt-20">Contact me</div>

      <span class="text-red-500 mb-20"> -- get in touch --</span>
    </div>
    <div class="grid grid-cols-2 mb-52">
      <div class="pl-20">
        <h1 class="font-bold text-2xl mb-10">Get in Touch</h1>

        <p class="mr-10">
          I would be greatful working with your Company and Give your Company
          your Desired services. Contact me for the service by email or direct
          Call
        </p>
        <ul>
          <li>Name Ram Kumar Mahato</li>
          <li>Address Kathmandu,Bagmati, Nepal</li>
          <li>Email ramshree@gmail.com</li>
          <li>Contact number +977 9821173215</li>
        </ul>
      </div>

      <div>
        <h1 class="text-2xl font-bold mb-10">Message Me</h1>
        <div class="mr-20 mb-10 text-justify">
          <form>
            <div class="relative z-0 mb-6 w-full group">
              <input
                type="text"
                name="floating_name"
                id="floating_name"
                class="block py-2.5 px-0 w-full text-sm text-gray-900 bg-transparent border-0 border-b-2 border-gray-300 appearance-none dark:text-white dark:border-gray-600 dark:focus:border-blue-500 focus:outline-none focus:ring-0 focus:border-blue-600 peer"
                placeholder=" "
                required
              />
              <label
                for="floating_name"
                class="peer-focus:font-medium absolute text-sm text-gray-500 dark:text-gray-400 duration-300 transform -translate-y-6 scale-75 top-3 -z-10 origin-[0] peer-focus:left-0 peer-focus:text-blue-600 peer-focus:dark:text-blue-500 peer-placeholder-shown:scale-100 peer-placeholder-shown:translate-y-0 peer-focus:scale-75 peer-focus:-translate-y-6"
                >Name</label
              >
            </div>
            <div class="relative z-0 mb-6 w-full group">
              <input
                type="email"
                name="floating_email"
                id="floating_email"
                class="block py-2.5 px-0 w-full text-sm text-gray-900 bg-transparent border-0 border-b-2 border-gray-300 appearance-none dark:text-white dark:border-gray-600 dark:focus:border-blue-500 focus:outline-none focus:ring-0 focus:border-blue-600 peer"
                placeholder=" "
                required
              />
              <label
                for="floating_email"
                class="peer-focus:font-medium absolute text-sm text-gray-500 dark:text-gray-400 duration-300 transform -translate-y-6 scale-75 top-3 -z-10 origin-[0] peer-focus:left-0 peer-focus:text-blue-600 peer-focus:dark:text-blue-500 peer-placeholder-shown:scale-100 peer-placeholder-shown:translate-y-0 peer-focus:scale-75 peer-focus:-translate-y-6"
                >Email</label
              >
            </div>
            <div class="relative z-0 mb-6 w-full group">
              <input
                type="text"
                name="floating_subject"
                id="floating_subject"
                class="block py-2.5 px-0 w-full text-sm text-gray-900 bg-transparent border-0 border-b-2 border-gray-300 appearance-none dark:text-white dark:border-gray-600 dark:focus:border-blue-500 focus:outline-none focus:ring-0 focus:border-blue-600 peer"
                placeholder=" "
                required
              />
              <label
                for="floating_subject"
                class="peer-focus:font-medium absolute text-sm text-gray-500 dark:text-gray-400 duration-300 transform -translate-y-6 scale-75 top-3 -z-10 origin-[0] peer-focus:left-0 peer-focus:text-blue-600 peer-focus:dark:text-blue-500 peer-placeholder-shown:scale-100 peer-placeholder-shown:translate-y-0 peer-focus:scale-75 peer-focus:-translate-y-6"
                >Subject</label
              >
            </div>
            <div class="relative z-0 mb-6 w-full group">
              <input
                type="text"
                name="floating_description"
                id="floating_description"
                class="block py-2.5 px-0 w-full text-sm text-gray-900 bg-transparent border-0 border-b-2 border-gray-300 appearance-none dark:text-white dark:border-gray-600 dark:focus:border-blue-500 focus:outline-none focus:ring-0 focus:border-blue-600 peer"
                placeholder=" "
                required
              />
              <label
                for="floating_description"
                class="peer-focus:font-medium absolute text-sm text-gray-500 dark:text-gray-400 duration-300 transform -translate-y-6 scale-75 top-3 -z-10 origin-[0] peer-focus:left-0 peer-focus:text-blue-600 peer-focus:dark:text-blue-500 peer-placeholder-shown:scale-100 peer-placeholder-shown:translate-y-0 peer-focus:scale-75 peer-focus:-translate-y-6"
                >Description</label
              >
            </div>
          </form>
        </div><a
        href="#"
        class="text-base font-semibold text-white bg-red-500 py-3 px-8 rounded-full hover:shadow-lg hover:opacity-80 transition duration-300 ease-in-out"
        >Send Message</a
      >
      </div>
    </div>
  </div>
</template>
