<template>
  <div>
     <main class="px-16 py-6 bg-gray-100 md:col-span-2">
            <div class="flex justify-center md:justify-end ">
                <nuxt-link to="/login" class="mr-3 rounded bg-white-100 text-white-500 btn hover:bg-blue-900 hover:text-white">Login</nuxt-link>
                <nuxt-link to="/signup" class="ml-2 rounded bg-white-100 text-white-500 btn hover:bg-blue-900 hover:text-white">Signup</nuxt-link>
            </div>

            <div>

                <h4 class="pb-4 mt-12 font-bold uppercase border-t border-b border-gray-300">Corporate Action Analytics</h4>
                <div class="grid gap-10 mt-12 lg:grid-cols-2">
                    <!--Cards goes here or pictures goes here-->
                    <div>
                        <img src="~/assets/css/images/caa.jpeg" alt="Analytics" class="object-cover w-full h-32 sm:h-48">
                        <div class="m-4">
                            <span class="font-bold">Analytics</span>
                            <span class="block text-sm">By Josphat </span>
                        </div>

                    </div>

                    <div class="card">
                        <img src="~/assets/css/images/analytics.jpeg" alt="Nuxt" class="object-cover w-full h-32 sm:h-48">
                        <div class="m-4">
                            <span class="font-bold">Analytics</span>
                            <span class="block text-sm">By Zheke Josphat</span>
                        </div>

                    </div>
                </div>


            </div>


        </main>
  </div>
</template>
