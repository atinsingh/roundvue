<template>
<div class="relative overflow-hidden bg-blue-800">
    <main class="mt-16 mb-16 sm:mt-24">
      <div class="mx-auto max-w-7xl">
        <div class="lg:grid lg:grid-cols-12 lg:gap-8">
          <div class="px-4 sm:px-6 sm:text-center md:max-w-2xl md:mx-auto lg:col-span-6 lg:text-left lg:flex lg:items-center">
            <div>
              <a href="#" class="inline-flex items-center p-2 pr-2 text-white bg-gray-900 rounded-lg sm:text-base lg:text-sm xl:text-base hover:text-gray-200">
                <span class="px-3 py-0.5 text-white text-xs font-semibold leading-5 uppercase tracking-wide bg-indigo-500 rounded-full animate-pulse">Become a mentor</span>
                <span class="ml-4 text-sm">Signup today</span>
                <!-- Heroicon name: chevron-right -->
                <svg  class="w-5 h-5 ml-2 text-gray-500" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" aria-hidden="true">
                  <path fill-rule="evenodd" d="M7.293 14.707a1 1 0 010-1.414L10.586 10 7.293 6.707a1 1 0 011.414-1.414l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414 0z" clip-rule="evenodd" />
                </svg>
              </a>
              <h1 class="mt-4 text-4xl font-extrabold tracking-tight text-white sm:mt-5 sm:leading-none lg:mt-6 lg:text-5xl xl:text-6xl">
                <span class="md:block">Outperfom interviews with</span>
                <span class="text-blue-300 md:block">Top Companies</span>
              </h1>
              <p class="mt-3 text-base text-gray-300 sm:mt-5 sm:text-xl lg:text-lg xl:text-xl">
               Take advantage of Pragra mentor's help to clear your interviews in top companies across globe and covert into a high paying job offer.
              </p>
              <p class="mt-8 text-sm font-semibold tracking-wide text-white uppercase sm:mt-10">Mentors from :</p>
              <div class="w-full mt-5 sm:mx-auto sm:max-w-lg lg:ml-0">
                <div class="flex flex-wrap items-start justify-between">
                  <div class="flex justify-center px-1">
                    <img class="h-9 sm:h-10" src="https://cdn.freebiesupply.com/images/large/2x/amazon-logo-transparent.png" alt="Tuple">
                  </div>
                  <div class="flex justify-center px-1">
                    <img class="h-9 sm:h-10" src="https://assets.stickpng.com/images/580b57fcd9996e24bc43c51f.png" alt="Workcation">
                  </div>
                  <div class="flex justify-center px-1">
                    <img class="h-9 sm:h-10" src="https://logodownload.org/wp-content/uploads/2014/09/facebook-logo-6.png" alt="StaticKit">
                  </div>
                   <div class="flex justify-center px-1">
                    <img class="h-9 sm:h-10" src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a4/Toronto-Dominion_Bank_logo.svg/670px-Toronto-Dominion_Bank_logo.svg.png" alt="StaticKit">
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="mt-16 sm:mt-24 lg:mt-0 lg:col-span-6">
            <div class="bg-white sm:max-w-md sm:w-full sm:mx-auto sm:rounded-lg sm:overflow-hidden">
              <div class="px-4 py-8 sm:px-10">
                <div class="border-b-4 border-gray-100">
                  <p class="text-lg font-medium text-center text-blue-700">
                    Get Info.
                  </p>
                </div>
                <div class="mt-6">
                  <form action="#" method="POST" class="space-y-6">
                    <div>
                      <label for="name" class="sr-only">Full name</label>
                      <input type="text" name="name" id="name" autocomplete="name" placeholder="Full name" required class="block w-full border-gray-300 rounded-md shadow-sm focus:ring-indigo-500 focus:border-indigo-500 sm:text-sm">
                    </div>

                    <div>
                      <label for="mobile-or-email" class="sr-only">Mobile number or email</label>
                      <input type="text" name="mobile-or-email" id="mobile-or-email" autocomplete="email" placeholder="Mobile number or email" required class="block w-full border-gray-300 rounded-md shadow-sm focus:ring-indigo-500 focus:border-indigo-500 sm:text-sm">
                    </div>

                    <div>
                      <label for="password" class="sr-only">Password</label>
                      <input id="password" name="password" type="password" placeholder="Password" autocomplete="current-password" required class="block w-full border-gray-300 rounded-md shadow-sm focus:ring-indigo-500 focus:border-indigo-500 sm:text-sm">
                    </div>

                    <div>
                      <button type="submit" class="flex justify-center w-full px-4 py-2 text-sm font-medium text-white bg-indigo-600 border border-transparent rounded-md shadow-sm hover:bg-indigo-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-500">
                        Send Me info
                      </button>
                    </div>
                  </form>
                </div>
              </div>
              <div class="px-4 py-6 border-t-2 border-gray-200 bg-gray-50 sm:px-10">
                <p class="text-xs leading-5 text-gray-500">By signing up, you agree to our <a href="#" class="font-medium text-gray-900 hover:underline">Terms</a>, <a href="#" class="font-medium text-gray-900 hover:underline">Data Policy</a> and <a href="#" class="font-medium text-gray-900 hover:underline">Cookies Policy</a>.</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </main>
</div>
</template>