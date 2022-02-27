<template>

<!--   Section 1-->
  <section class="relative py-20 overflow-hidden">
    <div class="max-w-7xl px-10 mx-auto sm:text-center">
      <p class="mb-4 text-3xl text-indigo-600 font-bold leading-tight tracking-tight sm:text-4xl font-heading" id="projects">PROJECTS</p>
      <p class="mb-4 font-medium text-xl tracking-tight text-gray-800 xl:mb-6">Some of my works that I've made during my free time</p>

      <div class="grid grid-cols-1 gap-10 sm:grid-cols-2 lg:grid-cols-2">
        <div class="w-full border border-gray-200 rounded-lg shadow-sm">

          <div class="flex flex-col items-center justify-center p-10">
            <img class="w-16 h-16 mb-6 rounded-full" src="/images/logos/rocket.png">
            <h2 class="text-lg font-medium text-indigo-500">Subsidian</h2>
            <p class="text-gray-800">Static website made with HTML, CSS and JavaScript
            </p></div>

          <div class="flex border-t border-gray-200 divide-x divide-gray-200">
            <a href="https://rjovenal.gitlab.io/capstone1_fv/" target="_blank" class="flex-1 block p-5 text-center text-gray-800 transition duration-200 ease-out hover:bg-indigo-600 hover:text-white">
              Visit
            </a>
          </div>
        </div>
        <div class="w-full border border-gray-200 rounded-lg shadow-sm">

          <div class="flex flex-col items-center justify-center p-10">
            <img class="w-16 h-16 mb-6 rounded-full" src="/images/logos/planet-earth.png">
            <h2 class="text-lg font-medium text-indigo-500">PureGo</h2>
            <p class="text-gray-800">Paymongo Gcash Payment Integration using Laravel
            </p></div>

          <div class="flex border-t border-gray-200 divide-x divide-gray-200">
            <a href="https://purego.herokuapp.com/" target="_blank" class="flex-1 block p-5 text-center text-gray-800 transition duration-200 ease-out hover:bg-indigo-600 hover:text-white">
              Visit
            </a>
          </div>
        </div>
        <div class="w-full border border-gray-200 rounded-lg shadow-sm">

          <div class="flex flex-col items-center justify-center p-10">
            <img class="w-16 h-16 mb-6 rounded-full" src="/images/logos/notebook.png">
            <h2 class="text-lg font-medium text-indigo-500">Memotrack</h2>
            <p class="text-gray-800">A web application that saves your important memories
            </p></div>

          <div class="flex border-t border-gray-200 divide-x divide-gray-200">
            <a href="https://memotrack.herokuapp.com/" target="_blank" class="flex-1 block p-5 text-center text-gray-800 transition duration-200 ease-out hover:bg-indigo-600 hover:text-white">
              Visit
            </a>
          </div>
        </div>
      </div>

    </div>
  </section>


</template>

<script>
export default {
  name: "Project"
}
</script>

<style scoped>

</style>