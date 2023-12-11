<template>
    <section class="page1 w-full bg-slate-400" style="height:90vh;">
        <div class="container m-0 m-auto flex gap-4 items-center justify-center flex-col top-36 absolute">
           <div class="image w-full flex items-center justify-center"><img src="./icon.jpg" class="rounded-full w-2/12"></div>
           <div class="info flex flex-col items-center justify-center">
            <h1 class="text-6xl font-bold text-yellow-200" style="text-shadow: 0 0 5px #aaa;">ECO CLEAN</h1>
             <p class="w-1/2 text-xl p-3 rounded-xl shadow text-yellow-50" style="text-shadow: 0 0 5px #000; background: rgba(192, 192, 192, 0.285);">Lorem ipsum dolor sit amet consectetur adipisicing elit. Vitae optio facilis fugiat illo aliquam sunt aliquid dolores! Maiores, quo doloremque deserunt excepturi ullam consectetur unde nihil.</p>
             
           </div>
        </div>
    </section>
    <section class="form">
        <div class="container p-7">
    <form class="max-w-md mx-auto">
      <div class="relative z-0 w-full mb-5 group">
          <input type="text" name="floating_name" id="floating_name" class="block py-2.5 px-0 w-full text-lg text-gray-900 bg-transparent border-0 border-b-2 border-gray-300 appearance-none dark:text-white dark:border-gray-600 dark:focus:border-blue-500 focus:outline-none focus:ring-0 focus:border-blue-600 peer" placeholder=" " required />
          <label for="floating_name" class="peer-focus:font-medium absolute text-lg  text-gray-500 dark:text-gray-400 duration-300 transform -translate-y-6 scale-75 top-3 -z-10 origin-[0] peer-focus:start-0 rtl:peer-focus:translate-x-1/4 rtl:peer-focus:left-auto peer-focus:text-blue-600 peer-focus:dark:text-blue-500 peer-placeholder-shown:scale-100 peer-placeholder-shown:translate-y-0 peer-focus:scale-75 peer-focus:-translate-y-6">Ism</label>
      </div>
      <div class="relative z-0 w-full mb-5 group">
          <input type="text" name="floating_lname" id="floating_lname" class="block py-2.5 px-0 w-full text-lg  text-gray-900 bg-transparent border-0 border-b-2 border-gray-300 appearance-none dark:text-white dark:border-gray-600 dark:focus:border-blue-500 focus:outline-none focus:ring-0 focus:border-blue-600 peer" placeholder=" " required />
          <label for="floating_lname" class="peer-focus:font-medium absolute text-lg  text-gray-500 dark:text-gray-400 duration-300 transform -translate-y-6 scale-75 top-3 -z-10 origin-[0] peer-focus:start-0 rtl:peer-focus:translate-x-1/4 peer-focus:text-blue-600 peer-focus:dark:text-blue-500 peer-placeholder-shown:scale-100 peer-placeholder-shown:translate-y-0 peer-focus:scale-75 peer-focus:-translate-y-6">Familiya</label>
      </div>
      <div class="relative z-0 w-full mb-5 group">
          <input type="text" name="repeat_number" id="repeat_number" class="block py-2.5 px-0 w-full text-lg text-gray-900 bg-transparent border-0 border-b-2 border-gray-300 appearance-none dark:text-white dark:border-gray-600 dark:focus:border-blue-500 focus:outline-none focus:ring-0 focus:border-blue-600 peer" placeholder=" " required />
          <label for="repeat_number" class="peer-focus:font-medium absolute text-lg text-gray-500 dark:text-gray-400 duration-300 transform -translate-y-6 scale-75 top-3 -z-10 origin-[0] peer-focus:start-0 rtl:peer-focus:translate-x-1/4 peer-focus:text-blue-600 peer-focus:dark:text-blue-500 peer-placeholder-shown:scale-100 peer-placeholder-shown:translate-y-0 peer-focus:scale-75 peer-focus:-translate-y-6">Tell:  </label>
      </div>
      <button type="submit" class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm w-full sm:w-auto px-5 py-2.5 text-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">Submit</button>
    </form>

        </div>
    </section>
</template>

<script setup></script>
<style scoped>
.page1{
    background: url("https://wecleananyhome.com/wp-content/uploads/slide1-1532x766.jpg");
}
@media screen and (max-width: 600px) {
    img{
        width:50%;
    }
    .info{
width-space: nowrap;
        overflow:hidden;
        text-overflow: ellipsis;
    }
    .info p{
        text-align: center;
        font-size: 1em;
        width:100%;
    }
}
</style>