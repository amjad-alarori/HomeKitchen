<script>
import feather from 'feather-icons';

export default {
	name: 'Home',
	data: () => {
		return {
			theme: '',
		};
	},
	created() {
		this.theme = localStorage.getItem('theme') || 'light';
	},
	mounted() {
		feather.replace();
		this.theme = localStorage.getItem('theme') || 'light';
	},
	updated() {
		feather.replace();
	},
	methods: {},
};
</script>

<template>
	<section
		class="flex items-center sm:flex-row mt-12 sm:mt-10"
	>
		<!-- Banner left contents -->
		<div class="w-full md:w-1/3 text-left">
			<h1
				class="font-general-semibold text-3xl md:text-3xl xl:text-4xl text-center sm:text-left text-ternary-dark dark:text-primary-light uppercase"
			>
				Hi, We Are Home Kitchen
			</h1>
			<p
				class="font-general-medium mt-2 text-lg sm:text-xl  xl:text-2xl text-center sm:text-left leading-none text-gray-400"
			>
				A Home Served Meals Platform
			</p>

			<div class="flex items-center sm:flex-row mt-12 sm:mt-10">
			<img width="230" height="100" src="https://homemeal.de/wp-content/uploads/2021/12/button.png" data-src="https://homemeal.de/wp-content/uploads/2021/12/button.png" class="attachment-full size-full ls-is-cached lazyloaded" alt="image">
			<img width="230" height="100" src="https://homemeal.de/wp-content/uploads/2021/12/button2.png" data-src="https://homemeal.de/wp-content/uploads/2021/12/button2.png" class="attachment-full size-full ls-is-cached lazyloaded" alt="image">
			</div>
		</div>

		<!-- Banner right illustration -->
<div class="w-full md:w-1/3 text-left" id="divCheckbox" style="visibility: hidden; display:inline;"></div>


		<div class="md:w-1/3 text-right float-right">
			<img
				v-if="theme === 'light'"
				src="@/assets/images/phone1.png"
				alt="Developer"
			/>
			
			<img
				v-else
				src="@/assets/images/phone1.png"
				alt="Developer"
			/>
		</div>
		<div class="md:w-1/3 text-left float-left">
			<img
				v-if="theme === 'light'"
				src="@/assets/images/phone.png"
				alt="Developer"
			/>
			
			<img
				v-else
				src="@/assets/images/phone.png"
				alt="Developer"
			/>
		</div>
	</section>
</template>

<style scoped></style>
