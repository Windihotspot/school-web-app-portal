<template>
  <footer class="max-w-screen-xl px-8 mx-auto">
    <div class="w-full border-y border-[#DDDDDD]">
      <div class="grid xl:grid-cols-4 lg:grid-cols-2 md:grid-cols-2 sm:grid-cols-1">
        <div
          class="md:w-full lg:w-full w-full sm:w-1/2 xl:w-fit flex flex-col sm:flex-row sm:px-6 py-6 sm:py-12 sm:space-x-10 sm:border-r-0 border-[#DDDDDD]"
        >
          <div class="sm:hidden xl:block mb-6 sm:mb-0">
            <!-- <a href="#">
              <img :src="require('~/assets/img/logo/nefa.svg')" class="w-24 -mt-2" alt="Nefa Logo" />
            </a> -->
          </div>
          <ul class="space-y-4">
            <li>Cryptocurrency</li>
            <li>Exchanges</li>
            <li>Watchlist</li>
            <li>Portfolio</li>
            <li>NFT</li>
          </ul>
        </div>
        <div
          class="md:w-full lg:w-full lg:border-r w-full sm:w-1/2 xl:w-fit sm:px-16 py-6 sm:py-12 border-t sm:border-t xl:border-r border-[#DDDDDD]"
        >
          <ul class="space-y-4">
            <li>Products</li>
            <li>About us</li>
            <li>Careers</li>
            <li>Blog</li>
            <li>Security</li>
          </ul>
        </div>
        <div
          class="md:w-full md:border-t lg:w-full w-full sm:w-1/2 xl:w-fit sm:px-16 py-6 sm:py-12 border-t sm:border-t-0 sm:border-r-0 border-[#DDDDDD]"
        >
          <ul class="space-y-4">
            <li>Help Center</li>
            <li>Contact us</li>
            <li>System status</li>
            <li>System status</li>
            <li>Privacy Policy</li>
          </ul>
        </div>
        <div
          class="md:w-full md:border-t lg:w-full sm:px-10 py-6 sm:py-12 w-full sm:w-1/2 xl:w-[22rem] space-y-4 sm:border-t border-[#DDDDDD]"
        >
          <h5 class="text-sm font-medium text-[#666666] focus:outline-none focus:shadow-outline">
            Newsletter
          </h5>
          <p class="text-sm text-[#666666] focus:outline-none focus:shadow-outline">
            Never miss anything crypto when <br class="sm:hidden" />you're on the go
          </p>
          <div class="flex items-center space-x-2">
            <input
              type="text"
              class="w-full px-2 py-4 sm:py-3 rounded-lg sm:rounded-md text-sm focus:outline-none border border-[#AAAAAA] placeholder-[#888]"
              placeholder="Enter your email"
            />
            <button
              class="bg-blue-gradient px-4 py-4 sm:py-3 rounded-md text-white hover:shadow-md transition duration-300"
            >
              <ArrowRightIcon :size="20" />
            </button>
          </div>
        </div>
      </div>
    </div>
    <div class="py-8 sm:py-4 text-center text-sm text-[#666666] hover:text-gray-900">
      &copy; Copyright 2024 . All rights reserved
    </div>
  </footer>
</template>
<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'BaseFooter'
})
</script>
