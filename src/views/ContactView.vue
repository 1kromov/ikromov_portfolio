<template>
  <div class="bg-[#161616]">
    <div id="Contact" class="contact container mx-auto min-h-screen pt-[120px] pb-[50px] ">
    <section class="bg-[#1D1D1D] w-[70%]  mx-auto  dark:bg-gray-900">
      <div class="py-8 lg:py-16 px-4 mx-auto max-w-screen-md">
        <h2
          class="mb-4 text-4xl tracking-tight font-extrabold text-center  text-white"
        >
          Contact Us
        </h2>
        <p
          class="mb-8 lg:mb-16 font-light text-center text-white dark:text-gray-400 sm:text-xl"
        >
          Got a technical issue? Want to send feedback about a beta feature?
          Need details about our Business plan? Let us know.
        </p>
        <form action="#" class="space-y-8">
          <div class="">
            <label
              for="email"
              class="block mb-2 text-sm font-medium  text-white"
              >Your email</label
            >
            <input
              type="email"
              id="email"
              class="shadow-sm bg-gray-700 border border-gray-300 text-gray-900 text-sm rounded-lg   block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 placeholder-white  dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500 dark:shadow-sm-light"
              placeholder="name@flowbite.com"
              required
            />
          </div>
          <div>
            <label
              for="subject"
              class="block mb-2 text-sm font-medium text-white dark:text-gray-300"
              >Subject</label
            >
            <input
              type="text"
              id="subject"
              class="block p-3 w-full bg-gray-700 text-sm text-gray-900  rounded-lg border border-gray-300 shadow-sm placeholder-white "
              placeholder="Let us know how we can help you"
              required
            />
          </div>
          <div class="sm:col-span-2">
            <label
              for="message"
              class="block mb-2 text-sm font-medium text-white dark:text-gray-400"
              >Your message</label
            >
            <textarea
              id="message"
              rows="6"
              class="block p-2.5 w-full placeholder-white  bg-gray-700 text-sm text-gray-900  rounded-lg shadow-sm border border-gray-300 focus:ring-primary-500 focus:border-primary-500 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500"
              placeholder="Leave a comment..."
            ></textarea>
          </div>
          <button
            type="submit"
            class="py-3 px-5 text-sm font-medium text-center text-white rounded-lg bg-primary-700 sm:w-fit hover:bg-primary-800 focus:ring-4 focus:outline-none focus:ring-primary-300 dark:bg-primary-600 dark:hover:bg-primary-700 dark:focus:ring-primary-800"
          >
            Send message
          </button>
        </form>
      </div>
    </section>
  </div>
  </div>

</template>
<script>
export default {
  name: "ContactView",
};
</script>
<style></style>
