<template>
    

    <nav class="bg-white border-gray-200 dark:bg-gray-900 shadow-lg">
      <div class="max-w-screen-xl flex flex-wrap items-center justify-between mx-auto p-4">
        <a href="https://flowbite.com/" class="flex items-center space-x-3 rtl:space-x-reverse">
            <img src="./icon.jpg" class="w-16" alt="Flowbite Logo" />
            <span class="self-center text-3xl font-semibold whitespace-nowrap" style="color: rgb(215, 215, 2); text-shadow:0 0 5px yellow">Eco Clean</span>
        </a>
        <button data-collapse-toggle="navbar-default" type="button" class="inline-flex items-center p-2 w-10 h-10 justify-center text-sm text-gray-500 rounded-lg md:hidden hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200 dark:text-gray-400 dark:hover:bg-gray-700 dark:focus:ring-gray-600" aria-controls="navbar-default" aria-expanded="false">
            <span class="sr-only">Open main menu</span>
            <svg class="w-5 h-5" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 17 14">
                <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M1 1h15M1 7h15M1 13h15"/>
            </svg>
        </button>
        <div class="hidden w-full md:block md:w-auto" id="navbar-default">
          <ul class="font-medium flex flex-col items-center justify-center p-4 md:p-0 mt-4 border border-gray-100 rounded-lg bg-gray-50 md:flex-row md:space-x-8 rtl:space-x-reverse md:mt-0 md:border-0 md:bg-white dark:bg-gray-800 md:dark:bg-gray-900 dark:border-gray-700">
            <li>
              <a href="#" class="block py-2 px-3  text-gray-900  bg-yellow-300 rounded md:bg-transparent  md:p-0 dark:text-white md:dark:hover:text-yellow-300 text-xl md:hover:text-yellow-300" aria-current="page" @click="gotoHome">Home</a>
            </li>
            <li>
              <a href="#" class="block py-2 px-3 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-yellow-300 md:p-0 dark:text-white md:dark:hover:text-yellow-300 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent text-xl">About</a>
            </li>
            <li>
              <a href="#" class="block py-2 px-3 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-yellow-300 md:p-0 dark:text-white md:dark:hover:text-yellow-300 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent text-xl">Services</a>
            </li>
            <li>
                <button @click="gotoFormPage"
        class="px-6 py-2 text-xl font-semibold text-white  border-b-4 rounded shadow-lg bg-yellow-200 border-yellow-300 shadow-yellow-400 hover:border-yellow-600">Contact</button>
            </li>
          </ul>
        </div>
      </div>
    </nav>

</template>
<script>
export default {
    methods: {
        gotoFormPage() {
            this.$router.push('/form')
    },
        gotoHome() {
          this.$router.push("/secction1")
        }
    }
}

</script>
<style scoped></style>