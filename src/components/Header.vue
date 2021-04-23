<template>
	<header class="text-center bg-blue-800 text-white p-4 mb-10">
		<div class="text-3xl md:text-5xl font-bold mb-3">
			<i class="fa fa-viruses"></i>
			Covid-19 Tracker
		</div>

		<p>
			Build by
			<a
				class="text-blue-300"
				href="https://github.com/arpangreat"
				target="_blank"
				>Swastik Acharyya</a
			>
		</p>
	</header>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";

@Options({})
export default class Header extends Vue {
	msg!: string;
}
</script>
