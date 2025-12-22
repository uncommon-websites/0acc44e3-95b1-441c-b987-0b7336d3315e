<script>
	const logos = [
		{ name: 'Mercury', width: 100 },
		{ name: 'Vercel', width: 100 },
		{ name: 'Replicate', width: 100 },
		{ name: 'Linear', width: 80 },
		{ name: 'Supabase', width: 100 },
		{ name: 'Resend', width: 100 }
	];
</script>

<section class="relative overflow-hidden border-b border-gray-200 bg-gray-50 pt-20 pb-16">
	<!-- Geometric Decoration Top Right -->
	<div class="absolute top-0 right-0 h-64 w-64 opacity-20 pointer-events-none">
		<svg viewBox="0 0 100 100" class="h-full w-full stroke-gray-400" fill="none">
			<path d="M0 0 L100 100 M50 0 L100 50 M0 50 L50 100" stroke-width="0.5" />
			<rect x="50" y="0" width="50" height="50" stroke-width="0.5" />
		</svg>
	</div>

	<div class="mx-auto max-w-[1400px] px-6">
		<div class="max-w-3xl">
			<!-- Badge -->
			<a href="#" class="mb-8 inline-flex items-center gap-2 rounded-full border border-purple-200 bg-purple-50 px-3 py-1 text-[10px] font-bold tracking-widest text-purple-700 hover:bg-purple-100 uppercase">
				<span class="text-purple-500">Open Source</span>
				Star us on GitHub &rsaquo;
			</a>

			<!-- Headline -->
			<h1 class="mb-6 text-7xl font-medium tracking-tight text-gray-900">
				Hire your first 100 faster.
			</h1>

			<!-- Subhead -->
			<p class="mb-10 max-w-xl text-lg leading-relaxed text-gray-600">
				Cracked is the <strong class="font-semibold text-gray-900">AI-native ATS</strong> built for seed-stage founders. Replace your messy Notion pipeline with automated sourcing, workflows, and one-click imports.
			</p>

			<!-- Buttons -->
			<div class="mb-24 flex items-center gap-4">
				<a href="#" class="bg-gray-900 px-6 py-3 text-[11px] font-bold tracking-widest text-white transition-colors hover:bg-gray-800 uppercase">
					Get Started Free
				</a>
				<a href="#" class="border border-gray-200 bg-white px-6 py-3 text-[11px] font-bold tracking-widest text-gray-900 transition-colors hover:bg-gray-50 uppercase">
					Import from Notion
				</a>
			</div>
		</div>

		<!-- Logos -->
		<div class="flex flex-wrap items-center justify-between gap-8 border-t border-gray-200 pt-8 opacity-60 grayscale">
			<!-- Mercury -->
			<div class="flex items-center gap-2 text-xl font-bold text-gray-800">
				<div class="h-5 w-5 rounded-full bg-gray-800"></div>
				Mercury
			</div>
			<!-- Vercel -->
			<div class="flex items-center gap-1 text-xl font-bold text-gray-800">
				<div class="h-4 w-4 bg-gray-800" style="clip-path: polygon(50% 0%, 100% 50%, 50% 100%, 0% 50%);"></div>
				Vercel
			</div>
			<!-- Replicate -->
			<div class="text-xl font-bold text-gray-800">Replicate</div>
			<!-- Linear -->
			<div class="flex items-center gap-2 text-xl font-medium text-gray-800">
				<svg width="20" height="20" viewBox="0 0 24 24" fill="currentColor"><path d="M2 12L12 2L22 12L12 22L2 12Z"/></svg>
				Linear
			</div>
			<!-- Supabase -->
			<div class="flex items-center gap-2 text-xl font-bold text-gray-800">
				<div class="grid grid-cols-2 gap-0.5">
					<div class="h-2 w-2 bg-gray-800"></div><div class="h-2 w-2 bg-gray-800"></div>
					<div class="h-2 w-2 bg-gray-800"></div><div class="h-2 w-2 bg-gray-800"></div>
				</div>
				Supabase
			</div>
			<!-- Resend -->
			<div class="text-xl font-medium text-gray-800">Resend</div>
		</div>
	</div>
</section>