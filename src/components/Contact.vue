<template>
  <section class="py-20">
    <div class="container items-center max-w-6xl px-4 px-10 mx-auto sm:px-20 md:px-32 lg:px-16" id="contactme">
      <div class="flex flex-wrap items-center -mx-3">
        <div class="order-1 w-full px-10 lg:w-1/2 lg:order-0">
          <div class="w-full lg:max-w-md">
            <h2 class="mb-4 text-3xl text-indigo-600 font-bold leading-tight tracking-tight sm:text-4xl font-heading">Contact</h2>
            <ul>
              <li class="flex items-center py-2 space-x-4 xl:py-3">
                <img src="/images/email.png" alt="email" class="w-10 h-10">
                <div>
                  <span class="text-md text-gray-500 font-medium">rj.jovenal@gmail.com</span>
                </div>
              </li>
              <li class="flex items-center py-2 space-x-4 xl:py-3">
                <img src="/images/phone.png" alt="phone" class="w-10 h-10">
                <div>
                  <span class="font-medium text-md text-gray-500">+63 927 158 9510</span>
                </div>
              </li>
              <li class="flex items-center py-2 space-x-4 xl:py-3">
                <img src="/images/linkedin.png" alt="linkedin" class="w-10 h-10">
                <div>
                  <span class="font-medium text-md text-gray-500">linkedin.com/in/rjovenal</span>
                </div>
              </li>
            </ul>
          </div>
        </div>
        <div class="w-full px-10 mb-12 lg:w-1/2 order-1 lg:order-1 lg:mb-0 h-auto">
          <img class="mx-auto sm:max-w-sm lg:max-w-full" src="/images/profile-details.svg" alt="feature image">
        </div>
      </div>
    </div>
  </section>
  <div class="text-center">
    <h1 class="pb-10"> Made with ❤ by Ralf | Copyright © {{ new Date().getFullYear() }} </h1>
  </div>
</template>

<script>
export default {
  name: "Contact.vue"
}
</script>

<style scoped>

</style>