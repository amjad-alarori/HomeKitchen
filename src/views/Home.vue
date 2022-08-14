<script>
import AppBanner from '@/components/shared/AppBanner';
import ProjectsGrid from '../components/projects/ProjectsGrid.vue';
import Button from '../components/reusable/Button.vue';
import Slider from '../components/Slider.vue';
export default {
	name: 'Home',
	components: {
    AppBanner,
    ProjectsGrid,
    Button,
    Slider
},
};
</script>

<template>



	<div class="container mx-auto">
		<!-- Banner -->
		<AppBanner class="mb-5 sm:mb-8" />



		

		<!-- Projects -->
		<ProjectsGrid />
		

		<!-- Load more projects button -->
		<div class="mt-10 sm:mt-20 flex justify-center">
			<router-link
				to="/projects"
				class="text-md font-general-medium bg-red-400 hover:bg-red-600 text-white shadow-sm rounded-md px-5 py-2.5 duration-300"
				aria-label="More Meals"
			>
				<Button title="More Meals" />
			</router-link>
		</div>
		<!--
  This example requires Tailwind CSS v2.0+ 
  
  This example requires some changes to your config:
  
  ```
  // tailwind.config.js
  module.exports = {
    // ...
    plugins: [
      // ...
      require('@tailwindcss/aspect-ratio'),
    ],
  }
  ```
-->
<!-- font-general-semibold text-2xl sm:text-5xl font-semibold mb-2 text-ternary-dark dark:text-ternary-light -->
<div class="relative py-16 text-ternary-dark dark:text-ternary-light">
  <div class="hidden absolute top-0 inset-x-0 h-1/2 text-ternary-dark dark:text-ternary-light lg:block" aria-hidden="true"></div>
  <div class="max-w-7xl mx-auto bg-red-400 lg:bg-transparent lg:px-8">
    <div class="lg:grid lg:grid-cols-12">
      <div class="relative z-10 lg:col-start-1 lg:row-start-1 lg:col-span-4 lg:py-16 lg:bg-transparent">
        <div class="absolute inset-x-0 h-1/2 text-ternary-dark dark:text-ternary-light lg:hidden" aria-hidden="true"></div>
        <div class="max-w-md mx-auto px-4 sm:max-w-3xl sm:px-6 lg:max-w-none lg:p-0">
          <div class="aspect-w-10 aspect-h-6 sm:aspect-w-2 sm:aspect-h-1 lg:aspect-w-1">
            <img class="object-cover object-center rounded-3xl shadow-2xl" src="https://apicms.thestar.com.my/uploads/images/2020/09/21/868326.jpg" alt="">
          </div>
        </div>
      </div>

      <div class="relative bg-red-400 lg:col-start-3 lg:row-start-1 lg:col-span-10 lg:rounded-3xl lg:grid lg:grid-cols-10 lg:items-center">
        <div class="hidden absolute inset-0 overflow-hidden rounded-3xl lg:block" aria-hidden="true">
          <svg class="absolute bottom-full left-full transform translate-y-1/3 -translate-x-2/3 xl:bottom-auto xl:top-0 xl:translate-y-0" width="404" height="384" fill="none" viewBox="0 0 404 384" aria-hidden="true">
            <defs>
              <pattern id="64e643ad-2176-4f86-b3d7-f2c5da3b6a6d" x="0" y="0" width="20" height="20" patternUnits="userSpaceOnUse">
                <rect x="0" y="0" width="4" height="4" class="text-red-500" fill="currentColor" />
              </pattern>
            </defs>
            <rect width="404" height="384" fill="url(#64e643ad-2176-4f86-b3d7-f2c5da3b6a6d)" />
          </svg>
          <svg class="absolute top-full transform -translate-y-1/3 -translate-x-1/3 xl:-translate-y-1/2" width="404" height="384" fill="none" viewBox="0 0 404 384" aria-hidden="true">
            <defs>
              <pattern id="64e643ad-2176-4f86-b3d7-f2c5da3b6a6d" x="0" y="0" width="20" height="20" patternUnits="userSpaceOnUse">
                <rect x="0" y="0" width="4" height="4" class="text-red-500" fill="currentColor" />
              </pattern>
            </defs>
            <rect width="404" height="384" fill="url(#64e643ad-2176-4f86-b3d7-f2c5da3b6a6d)" />
          </svg>
        </div>
        <div class="relative max-w-md mx-auto py-12 px-4 space-y-6 sm:max-w-3xl sm:py-16 sm:px-6 lg:max-w-none lg:p-0 lg:col-start-4 lg:col-span-6">
          <h2 class="text-3xl tracking-tight font-bold text-white" id="join-heading">Join our team</h2>
          <p class="text-lg text-white">Varius facilisi mauris sed sit. Non sed et duis dui leo, vulputate id malesuada non. Cras aliquet purus dui laoreet diam sed lacus, fames.</p>
          <a class="block w-full py-3 px-5 text-center bg-white border border-transparent rounded-md shadow-md text-base font-medium text-red-700 hover:bg-gray-50 sm:inline-block sm:w-auto" href="#">Explore open positions</a>
        </div>
      </div>
    </div>
  </div>
</div>


<br><br><br><br><br>


  <Slider />





<!-- This example requires Tailwind CSS v2.0+ -->
<div class="text-ternary-dark dark:text-ternary-light">
  <div class="max-w-7xl mx-auto py-12 px-4 text-center sm:px-6 lg:px-8 lg:py-24">
    <div class="space-y-8 sm:space-y-12">
      <div class="space-y-5 sm:mx-auto sm:max-w-xl sm:space-y-4 lg:max-w-5xl">
        <h2 class="text-3xl font-bold tracking-tight sm:text-4xl sm:tracking-tight">The People</h2>
        <p class="text-xl text-gray-500">Risus velit condimentum vitae tincidunt tincidunt. Mauris ridiculus fusce amet urna nunc. Ut nisl ornare diam in.</p>
      </div>
      <ul role="list" class="mx-auto grid grid-cols-2 gap-x-4 gap-y-8 sm:grid-cols-4 md:gap-x-6 lg:max-w-5xl lg:gap-x-8 lg:gap-y-12 xl:grid-cols-6">
        <li>
          <div class="space-y-4">
            <img class="mx-auto h-20 w-20 rounded-full lg:w-24 lg:h-24" src="https://images.unsplash.com/photo-1519244703995-f4e0f30006d5?ixlib=rb-=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=8&w=1024&h=1024&q=80" alt="">
            <div class="space-y-2">
              <div class="text-xs font-medium lg:text-sm">
                <h3>Michael Foster</h3>
                <p class="text-red-400">Co-Founder / CTO</p>
              </div>
            </div>
          </div>
        </li>
		<li>
          <div class="space-y-4">
            <img class="mx-auto h-20 w-20 rounded-full lg:w-24 lg:h-24" src="https://images.unsplash.com/photo-1550525811-e5869dd03032?ixlib=rb-=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=8&w=1024&h=1024&q=80" alt="">
            <div class="space-y-2">
              <div class="text-xs font-medium lg:text-sm">
                <h3>Michael Foster</h3>
                <p class="text-red-400">Manager</p>
              </div>
            </div>
          </div>
        </li>

<li>
          <div class="space-y-4">
            <img class="mx-auto h-20 w-20 rounded-full lg:w-24 lg:h-24" src="https://images.unsplash.com/photo-1438761681033-6461ffad8d80?ixlib=rb-=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=8&w=1024&h=1024&q=80" alt="">
            <div class="space-y-2">
              <div class="text-xs font-medium lg:text-sm">
                <h3>Michael Foster</h3>
                <p class="text-red-400">Marketer</p>
              </div>
            </div>
          </div>
        </li>

<li>
          <div class="space-y-4">
            <img class="mx-auto h-20 w-20 rounded-full lg:w-24 lg:h-24" src="https://images.unsplash.com/photo-1463453091185-61582044d556?ixlib=rb-=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=8&w=1024&h=1024&q=80" alt="">
            <div class="space-y-2">
              <div class="text-xs font-medium lg:text-sm">
                <h3>Michael Foster</h3>
                <p class="text-red-400">Chef</p>
              </div>
            </div>
          </div>
        </li>

<li>
          <div class="space-y-4">
            <img class="mx-auto h-20 w-20 rounded-full lg:w-24 lg:h-24" src="https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?ixlib=rb-=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=8&w=1024&h=1024&q=80" alt="">
            <div class="space-y-2">
              <div class="text-xs font-medium lg:text-sm">
                <h3>Michael Foster</h3>
                <p class="text-red-400">Conultant</p>
              </div>
            </div>
          </div>
        </li>

<li>
          <div class="space-y-4">
            <img class="mx-auto h-20 w-20 rounded-full lg:w-24 lg:h-24" src="https://images.unsplash.com/photo-1487412720507-e7ab37603c6f?ixlib=rb-=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=8&w=1024&h=1024&q=80" alt="">
            <div class="space-y-2">
              <div class="text-xs font-medium lg:text-sm">
                <h3>Michael Foster</h3>
                <p class="text-red-400">CEO</p>
              </div>
            </div>
          </div>
        </li>

<li>
          <div class="space-y-4">
            <img class="mx-auto h-20 w-20 rounded-full lg:w-24 lg:h-24" src="https://images.unsplash.com/photo-1500648767791-00dcc994a43e?ixlib=rb-=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=8&w=1024&h=1024&q=80" alt="">
            <div class="space-y-2">
              <div class="text-xs font-medium lg:text-sm">
                <h3>Michael Foster</h3>
                <p class="text-red-400">Developer</p>
              </div>
            </div>
          </div>
        </li>

<li>
          <div class="space-y-4">
            <img class="mx-auto h-20 w-20 rounded-full lg:w-24 lg:h-24" src="https://images.unsplash.com/photo-1500917293891-ef795e70e1f6?ixlib=rb-=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=8&w=1024&h=1024&q=80" alt="">
            <div class="space-y-2">
              <div class="text-xs font-medium lg:text-sm">
                <h3>Michael Foster</h3>
                <p class="text-red-400">Driver</p>
              </div>
            </div>
          </div>
        </li>

<li>
          <div class="space-y-4">
            <img class="mx-auto h-20 w-20 rounded-full lg:w-24 lg:h-24" src="https://images.unsplash.com/photo-1501031170107-cfd33f0cbdcc?ixlib=rb-=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=8&w=1024&h=1024&q=80" alt="">
            <div class="space-y-2">
              <div class="text-xs font-medium lg:text-sm">
                <h3>Michael Foster</h3>
                <p class="text-red-400">Tester</p>
              </div>
            </div>
          </div>
        </li>

<li>
          <div class="space-y-4">
            <img class="mx-auto h-20 w-20 rounded-full lg:w-24 lg:h-24" src="https://images.unsplash.com/photo-1502685104226-ee32379fefbe?ixlib=rb-=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=8&w=1024&h=1024&q=80" alt="">
            <div class="space-y-2">
              <div class="text-xs font-medium lg:text-sm">
                <h3>Michael Foster</h3>
                <p class="text-red-400">Chef</p>
              </div>
            </div>
          </div>
        </li>

<li>
          <div class="space-y-4">
            <img class="mx-auto h-20 w-20 rounded-full lg:w-24 lg:h-24" src="https://images.unsplash.com/photo-1504703395950-b89145a5425b?ixlib=rb-=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=8&w=1024&h=1024&q=80" alt="">
            <div class="space-y-2">
              <div class="text-xs font-medium lg:text-sm">
                <h3>Michael Foster</h3>
                <p class="text-red-400">Cleaner</p>
              </div>
            </div>
          </div>
        </li>
		<li>
          <div class="space-y-4">
            <img class="mx-auto h-20 w-20 rounded-full lg:w-24 lg:h-24" src="https://images.unsplash.com/photo-1505840717430-882ce147ef2d?ixlib=rb-=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=8&w=1024&h=1024&q=80" alt="">
            <div class="space-y-2">
              <div class="text-xs font-medium lg:text-sm">
                <h3>Michael Foster</h3>
                <p class="text-red-400">Partner</p>
              </div>
            </div>
          </div>
        </li>
		<li>
          <div class="space-y-4">
            <img class="mx-auto h-20 w-20 rounded-full lg:w-24 lg:h-24" src="https://images.unsplash.com/photo-1506980595904-70325b7fdd90?ixlib=rb-=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=8&w=1024&h=1024&q=80" alt="">
            <div class="space-y-2">
              <div class="text-xs font-medium lg:text-sm">
                <h3>Michael Foster</h3>
                <p class="text-red-400">Desginer</p>
              </div>
            </div>
          </div>
        </li>





        <!-- More people... -->
      </ul>
    </div>
  </div>
</div>


<!-- This example requires Tailwind CSS v2.0+ -->
<div class="text-ternary-dark dark:text-ternary-light">
<div class="text-ternary-dark dark:text-ternary-light pt-12 sm:pt-16">
  <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="max-w-4xl mx-auto text-center">
      <h2 class="text-3xl font-bold tracking-tight sm:text-4xl sm:tracking-tight">How Home Kitchen works</h2>
    </div><br><br>
  </div>
    <div class="mt-10 pb-12 text-ternary-dark dark:text-ternary-light sm:pb-16">
      <div class="relative">
        <div class="absolute inset-0 h-1/2 text-ternary-dark dark:text-ternary-light"></div>
        <div class="relative max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
          <div class="max-w-4xl mx-auto">
            <dl class="rounded-lg text-ternary-dark dark:text-ternary-light shadow-lg sm:grid sm:grid-cols-3">
              <div class="flex flex-col border-b border-gray-100 p-6 text-center sm:border-0 sm:border-r">
          <P class="order-1 text-5xl tracking-tight font-bold sm:tracking-tight">1</P><br><br>
                <dd class="order-1 text-5xl tracking-tight font-bold text-red-400">Choose a Home Chef</dd>
              </div>
              <div class="flex flex-col border-t border-b border-gray-100 p-6 text-center sm:border-0 sm:border-l sm:border-r">
          <P class="order-1 text-5xl tracking-tight font-bold sm:tracking-tight">2</P><br><br>
                <dd class="order-1 text-5xl tracking-tight font-bold text-red-400">Pick your dishes</dd>
              </div>
              <div class="flex flex-col border-t border-gray-100 p-6 text-center sm:border-0 sm:border-l">
          <P class="order-1 text-5xl tracking-tight font-bold sm:tracking-tight">3</P><br><br>
                <dd class="order-1 text-5xl tracking-tight font-bold text-red-400">Get your delivery</dd>
              </div>
            </dl>
          </div>
        </div>
      </div>
    </div>
  </div>
  </div><br><br><br><br><br>


<!-- This example requires Tailwind CSS v2.0+ -->

<div class="text-ternary-dark dark:text-ternary-light">

      <h2 class="text-3xl font-bold tracking-tight sm:text-4xl sm:tracking-tight">Last 30 days</h2><br><br>
      

  <dl class="mt-5 grid grid-cols-1 gap-5 sm:grid-cols-2 lg:grid-cols-3">
    <div class="relative text-ternary-dark dark:text-ternary-light pt-5 px-4 pb-12 sm:pt-6 sm:px-6 shadow rounded-lg overflow-hidden">
      <dt>
        <div class="absolute bg-red-400 rounded-md p-3">
          <!-- Heroicon name: outline/users -->
          <svg class="h-6 w-6 text-white" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" aria-hidden="true">
            <path stroke-linecap="round" stroke-linejoin="round" d="M12 4.354a4 4 0 110 5.292M15 21H3v-1a6 6 0 0112 0v1zm0 0h6v-1a6 6 0 00-9-5.197M13 7a4 4 0 11-8 0 4 4 0 018 0z" />
          </svg>
        </div>
        <p class="ml-16 text-sm font-medium text-gray-500 truncate">Total Subscribers</p>
      </dt>
      <dd class="ml-16 pb-6 flex items-baseline sm:pb-7">
        <p class="text-2xl font-semibold sm:tracking-tight">71,897</p>
        <p class="ml-2 flex items-baseline text-sm font-semibold text-green-600">
          <!-- Heroicon name: solid/arrow-sm-up -->
          <svg class="self-center flex-shrink-0 h-5 w-5 text-green-500" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" aria-hidden="true">
            <path fill-rule="evenodd" d="M5.293 9.707a1 1 0 010-1.414l4-4a1 1 0 011.414 0l4 4a1 1 0 01-1.414 1.414L11 7.414V15a1 1 0 11-2 0V7.414L6.707 9.707a1 1 0 01-1.414 0z" clip-rule="evenodd" />
          </svg>
          <span class="sr-only"> Increased by </span>
          122
        </p>
        <div class="absolute bottom-0 inset-x-0 text-ternary-dark dark:text-ternary-light px-4 py-4 sm:px-6">
          <div class="text-sm">
            <a href="#" class="font-medium text-red-400 hover:text-red-500"> View all<span class="sr-only"> Total Subscribers stats</span></a>
          </div>
        </div>
      </dd>
    </div>

    <div class="relative text-ternary-dark dark:text-ternary-light pt-5 px-4 pb-12 sm:pt-6 sm:px-6 shadow rounded-lg overflow-hidden">
      <dt>
        <div class="absolute bg-red-400 rounded-md p-3">
          <!-- Heroicon name: outline/mail-open -->
          <svg class="h-6 w-6 text-white" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" aria-hidden="true">
            <path stroke-linecap="round" stroke-linejoin="round" d="M3 19v-8.93a2 2 0 01.89-1.664l7-4.666a2 2 0 012.22 0l7 4.666A2 2 0 0121 10.07V19M3 19a2 2 0 002 2h14a2 2 0 002-2M3 19l6.75-4.5M21 19l-6.75-4.5M3 10l6.75 4.5M21 10l-6.75 4.5m0 0l-1.14.76a2 2 0 01-2.22 0l-1.14-.76" />
          </svg>
        </div>
        <p class="ml-16 text-sm font-medium text-gray-500 truncate">Avg. Open Rate</p>
      </dt>
      <dd class="ml-16 pb-6 flex items-baseline sm:pb-7">
        <p class="text-2xl font-semibold sm:tracking-tight">58.16%</p>
        <p class="ml-2 flex items-baseline text-sm font-semibold text-green-600">
          <!-- Heroicon name: solid/arrow-sm-up -->
          <svg class="self-center flex-shrink-0 h-5 w-5 text-green-500" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" aria-hidden="true">
            <path fill-rule="evenodd" d="M5.293 9.707a1 1 0 010-1.414l4-4a1 1 0 011.414 0l4 4a1 1 0 01-1.414 1.414L11 7.414V15a1 1 0 11-2 0V7.414L6.707 9.707a1 1 0 01-1.414 0z" clip-rule="evenodd" />
          </svg>
          <span class="sr-only"> Increased by </span>
          5.4%
        </p>
        <div class="absolute bottom-0 inset-x-0 text-ternary-dark dark:text-ternary-light px-4 py-4 sm:px-6">
          <div class="text-sm">
            <a href="#" class="font-medium text-red-400 hover:text-red-500"> View all<span class="sr-only"> Avg. Open Rate stats</span></a>
          </div>
        </div>
      </dd>
    </div>

    <div class="relative text-ternary-dark dark:text-ternary-light pt-5 px-4 pb-12 sm:pt-6 sm:px-6 shadow rounded-lg overflow-hidden">
      <dt>
        <div class="absolute bg-red-400 rounded-md p-3">
          <!-- Heroicon name: outline/cursor-click -->
          <svg class="h-6 w-6 text-white" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" aria-hidden="true">
            <path stroke-linecap="round" stroke-linejoin="round" d="M15 15l-2 5L9 9l11 4-5 2zm0 0l5 5M7.188 2.239l.777 2.897M5.136 7.965l-2.898-.777M13.95 4.05l-2.122 2.122m-5.657 5.656l-2.12 2.122" />
          </svg>
        </div>
        <p class="ml-16 text-sm font-medium text-gray-500 truncate">Avg. Click Rate</p>
      </dt>
      <dd class="ml-16 pb-6 flex items-baseline sm:pb-7">
        <p class="text-2xl font-semibold sm:tracking-tight">24.57%</p>
        <p class="ml-2 flex items-baseline text-sm font-semibold text-red-600">
          <!-- Heroicon name: solid/arrow-sm-down -->
          <svg class="self-center flex-shrink-0 h-5 w-5 text-red-500" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" aria-hidden="true">
            <path fill-rule="evenodd" d="M14.707 10.293a1 1 0 010 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 111.414-1.414L9 12.586V5a1 1 0 012 0v7.586l2.293-2.293a1 1 0 011.414 0z" clip-rule="evenodd" />
          </svg>
          <span class="sr-only"> Decreased by </span>
          3.2%
        </p>
        <div class="absolute bottom-0 inset-x-0 text-ternary-dark dark:text-ternary-light px-4 py-4 sm:px-6">
          <div class="text-sm">
            <a href="#" class="font-medium text-red-400 hover:text-red-500"> View all<span class="sr-only"> Avg. Click Rate stats</span></a>
          </div>
        </div>
      </dd>
    </div>
  </dl>
  </div>
</div>


	
</template>

<style scoped></style>
