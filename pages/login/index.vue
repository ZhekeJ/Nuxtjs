<template>
  <div class="justify-center ">
        <title>Login</title>
        <div class="lg:flex">
            <div class="lg:w-full">
                <div class="flex justify-center py-12 bg-blue-600 lg:justify-center lg:px-12">
                    <div class="flex items-center cursor-pointer">

                        <div class="mt-2 mb-2 ml-2 text-2xl font-semibold tracking-wide text-indigo-800">Corporate Action Analysis</div>
                    </div>
                </div>
                <div class="px-12 mt-2 sm:px-24 md:px-48 lg:px-12 lg:mt-16 xl:px-24 xl:max-w-2xl">
                    <h2 class="mr-3 rounded bg-white-100 text-white-500 btn hover:bg-blue-900 hover:text-white">Login</h2>
                    <div class="mt-12">
                        <form>
                            <div>
                                <div class="text-sm font-bold tracking-wide text-gray-700">Email Address</div>
                                <input class="w-full py-2 text-lg border-b border-gray-300 focus:outline-none focus:border-indigo-500" type="" placeholder="jzheke@gmail.com">
                            </div>
                            <div class="mt-8">
                                <div class="flex items-center justify-between">
                                    <div class="text-sm font-bold tracking-wide text-gray-700">
                                        Password
                                    </div>
                                    <div>
                                        <a class="text-xs font-semibold text-indigo-600 cursor-pointer font-display hover:text-indigo-800">
                                            Forgot Password?
                                        </a>
                                    </div>
                                </div>
                                <input class="w-full py-2 text-lg border-b border-gray-300 focus:outline-none focus:border-indigo-500" type="" placeholder="Enter your password">
                            </div>
                            <div class="mt-10">
                                <button @click="$nuxt.$router.push('/dashboard')" class="w-full p-4 font-semibold tracking-wide text-gray-100 bg-indigo-500 rounded-full shadow-lg font-display focus:outline-none focus:shadow-outline hover:bg-indigo-600">
                                    LogIn
                                </button>
                            </div>
                        </form>
                        <div class="flex mt-12 text-sm font-semibold text-center text-gray-700 font-display">
                         <a class="text-indigo-600 cursor-pointer hover:text-indigo-800">Sign up</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
   </div>
</template>
