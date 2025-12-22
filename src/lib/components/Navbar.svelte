<script>
	// Navbar
</script>

<div class="sticky top-0 z-50 w-full bg-white">
	<!-- Top Banner -->
	<div class="bg-black px-4 py-2 text-center text-[11px] font-medium tracking-wide text-white">
		<a href="#" class="hover:underline">
			Open-source ATS built for your first 100 hires &rarr; Star us on GitHub
		</a>
	</div>

	<!-- Main Navigation -->
	<nav class="border-b border-gray-200 px-6 py-4">
		<div class="mx-auto flex max-w-[1400px] items-center justify-between">
			<!-- Logo and Left Links -->
			<div class="flex items-center gap-12">
				<a href="/" class="flex items-center gap-2">
					<svg width="24" height="26" viewBox="0 0 87 96" fill="none" xmlns="http://www.w3.org/2000/svg">
						<path fill-rule="evenodd" clip-rule="evenodd" d="M59.9489 37.1809C58.7302 49.9289 48.0665 59.8958 35.092 59.8958C32.3768 59.8958 29.763 59.4593 27.3158 58.6524C28.5345 45.9044 39.198 35.9375 52.1725 35.9375C54.8877 35.9375 57.5015 36.374 59.9489 37.1809ZM58.8631 27.0075C56.6988 26.5789 54.4617 26.3542 52.1725 26.3542C35.7001 26.3542 21.9251 37.9879 18.5029 53.5438C13.3593 48.9359 10.119 42.2189 10.119 34.7396C10.119 20.8461 21.2998 9.58333 35.092 9.58333C46.2061 9.58333 55.6247 16.8971 58.8631 27.0075ZM69.3789 30.9803C67.5183 13.5622 52.8775 0 35.092 0C16.0456 0 0.605469 15.5535 0.605469 34.7396C0.605469 47.6136 7.55728 58.852 17.8857 64.8531C19.7463 82.2712 34.3872 95.8333 52.1725 95.8333C71.219 95.8333 86.659 80.2798 86.659 61.0938C86.659 48.2197 79.7072 36.9816 69.3789 30.9803ZM68.7617 42.2896C65.3395 57.8455 51.5644 69.4792 35.092 69.4792C32.8028 69.4792 30.5659 69.2544 28.4016 68.8258C31.64 78.9362 41.0584 86.25 52.1725 86.25C65.9647 86.25 77.1455 74.9872 77.1455 61.0938C77.1455 53.6144 73.9054 46.8975 68.7617 42.2896Z" fill="black"/>
					</svg>
					<span class="text-xl font-bold tracking-tight text-gray-900">Cracked</span>
				</a>
				
				<div class="hidden items-center gap-8 md:flex">
					{#each ['Features', 'Pricing', 'Docs', 'GitHub'] as item}
						<a href="#" class="flex items-center gap-1 text-[11px] font-semibold tracking-widest text-gray-600 hover:text-gray-900 uppercase">
							{item}
							{#if item === 'Features'}
								<svg width="10" height="10" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="opacity-50"><path d="m6 9 6 6 6-6"/></svg>
							{/if}
						</a>
					{/each}
				</div>
			</div>

			<!-- Right Actions -->
			<div class="flex items-center gap-6">
				<a href="#" class="text-[11px] font-semibold tracking-widest text-gray-600 hover:text-gray-900 uppercase">
					Sign In
				</a>
				<a href="#" class="text-[11px] font-semibold tracking-widest text-gray-600 hover:text-gray-900 uppercase">
					Book a Demo
				</a>
				<a href="#" class="bg-gray-900 px-4 py-2 text-[11px] font-bold tracking-widest text-white transition-colors hover:bg-gray-800 uppercase">
					Get Started
				</a>
			</div>
		</div>
	</nav>
</div>