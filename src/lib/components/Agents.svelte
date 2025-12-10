<section class="py-24 bg-gray-50 border-t border-b border-gray-200">
	<div class="mx-auto max-w-[1400px] px-6">
		<div class="mb-12 text-center">
			<div class="mb-4 text-[10px] font-bold tracking-widest text-gray-500 uppercase">[02] AI Agents</div>
			<h2 class="text-4xl font-medium tracking-tight text-gray-900">Deploy AI Agents for every recruiter</h2>
		</div>

		<!-- Diagram Area -->
		<div class="relative mb-16 overflow-hidden rounded-xl bg-[#6b3fa0] p-12 min-h-[500px] flex items-center justify-center">
			<!-- Background Grid -->
			<div class="absolute inset-0 opacity-20" 
				style="background-image: linear-gradient(#ffffff 1px, transparent 1px), linear-gradient(to right, #ffffff 1px, transparent 1px); background-size: 50px 50px;">
			</div>
			
			<div class="relative z-10 w-full max-w-4xl">
				<!-- Central UI -->
				<div class="relative mx-auto max-w-2xl rounded-lg bg-white shadow-2xl overflow-hidden">
					<div class="border-b border-gray-100 bg-gray-50 px-4 py-2 flex justify-between items-center">
						<div class="text-xs font-semibold text-gray-600">Profiles Ready for Review (35)</div>
					</div>
					<div class="p-4 space-y-3">
						<!-- List Items -->
						{#each ['Dean Wiegand', 'Krystal Han', 'Wade Walter', 'Jenna Alvarez'] as name, i}
							<div class="flex items-center justify-between p-2 hover:bg-gray-50 rounded border border-transparent hover:border-gray-100">
								<div class="flex items-center gap-3">
									<div class="h-6 w-6 rounded-full bg-gray-200"></div>
									<div class="text-xs font-medium">{name}</div>
								</div>
								<div class="text-[10px] text-gray-400">Software Engineer</div>
								<div class="text-[10px] text-green-600 font-bold">100%</div>
							</div>
						{/each}
					</div>
					
					<!-- Chat Overlay -->
					<div class="absolute bottom-4 left-4 right-4 rounded-lg bg-white shadow-lg border border-gray-200 p-4">
						<div class="mb-2 text-xs text-gray-500">What do you think about this profile?</div>
						<div class="flex gap-2">
							<div class="h-8 flex-1 rounded bg-gray-100 p-2 text-xs text-gray-400">Tonya Rempel is a Senior Data Analyst...</div>
							<button class="h-8 w-8 rounded border border-gray-200 flex items-center justify-center text-green-500 hover:bg-green-50">
								<svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M14 9V5a3 3 0 0 0-3-3l-4 9v11h11.28a2 2 0 0 0 2-1.7l1.38-9a2 2 0 0 0-2-2.3zM7 22H4a2 2 0 0 1-2-2v-7a2 2 0 0 1 2-2h3"/></svg>
							</button>
							<button class="h-8 w-8 rounded border border-gray-200 flex items-center justify-center text-red-500 hover:bg-red-50">
								<svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M10 15v4a3 3 0 0 0 3 3l4-9V2H5.72a2 2 0 0 0-2 1.7l-1.38 9a2 2 0 0 0 2 2.3zm7-13h2.67A2.31 2.31 0 0 1 22 4v7a2.31 2.31 0 0 1-2.33 2H17"/></svg>
							</button>
						</div>
					</div>
				</div>

				<!-- Floating Agents -->
				<!-- Project Manager Agent -->
				<div class="absolute top-10 -left-12 bg-white rounded-lg shadow-lg p-3 flex items-center gap-3 animate-bounce" style="animation-duration: 3s;">
					<div class="h-8 w-8 rounded bg-pink-100 flex items-center justify-center text-pink-600">
						<svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M14.7 6.3a1 1 0 0 0 0 1.4l1.6 1.6a1 1 0 0 0 1.4 0l3.77-3.77a6 6 0 0 1-7.94 7.94l-6.91 6.91a2.12 2.12 0 0 1-3-3l6.91-6.91a6 6 0 0 1 7.94-7.94l-3.76 3.76z"/></svg>
					</div>
					<div>
						<div class="text-xs font-bold text-pink-600">Project manager agent</div>
						<div class="text-[10px] text-gray-500">35 profiles ready for review</div>
					</div>
				</div>

				<!-- Data Analyst Agent -->
				<div class="absolute -top-6 right-12 bg-white rounded-lg shadow-lg p-3 flex items-center gap-3 animate-bounce" style="animation-duration: 4s;">
					<div class="h-8 w-8 rounded bg-purple-100 flex items-center justify-center text-purple-600">
						<svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M21 16V8a2 2 0 0 0-1-1.73l-7-4a2 2 0 0 0-2 0l-7 4A2 2 0 0 0 3 8v8a2 2 0 0 0 1 1.73l7 4a2 2 0 0 0 2 0l7-4A2 2 0 0 0 21 16z"/><polyline points="3.27 6.96 12 12.01 20.73 6.96"/><line x1="12" y1="22.08" x2="12" y2="12"/></svg>
					</div>
					<div>
						<div class="text-xs font-bold text-purple-600">Data analyst agent</div>
						<div class="text-[10px] text-gray-500">Running 24/7 in background</div>
					</div>
				</div>

				<!-- Software Engineer Agent -->
				<div class="absolute bottom-20 -right-8 bg-white rounded-lg shadow-lg p-3 flex items-center gap-3 animate-bounce" style="animation-duration: 3.5s;">
					<div class="h-8 w-8 rounded bg-blue-100 flex items-center justify-center text-blue-600">
						<svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><polyline points="16 18 22 12 16 6"/><polyline points="8 6 2 12 8 18"/></svg>
					</div>
					<div>
						<div class="text-xs font-bold text-blue-600">Software engineer agent</div>
						<div class="text-[10px] text-gray-500">35 profiles ready for review</div>
					</div>
				</div>
			</div>
		</div>

		<!-- Features Grid -->
		<div class="grid grid-cols-1 gap-8 md:grid-cols-3">
			<!-- Col 1 -->
			<div class="rounded-lg border border-gray-200 bg-white p-6">
				<div class="mb-4 inline-block rounded bg-purple-100 px-2 py-1 text-[10px] font-bold tracking-widest text-purple-700 uppercase">
					AI Search
				</div>
				<h3 class="mb-3 text-lg font-bold text-gray-900">Search on autopilot</h3>
				<p class="text-sm leading-relaxed text-gray-600">
					Your <strong class="text-gray-900">AI recruiting agents</strong> search through 800M+ profiles across 30+ sources, managing the workflow end-to-end for continuous talent pipeline.
				</p>
			</div>

			<!-- Col 2 -->
			<div class="rounded-lg border border-gray-200 bg-white p-6">
				<div class="mb-4 inline-block rounded bg-green-100 px-2 py-1 text-[10px] font-bold tracking-widest text-green-700 uppercase">
					Agentic Learning
				</div>
				<h3 class="mb-3 text-lg font-bold text-gray-900">Gets better with every hire</h3>
				<p class="text-sm leading-relaxed text-gray-600">
					<strong class="text-gray-900">AI recruiting agents</strong> learn from every action, refining searches to match your hiring standards with greater precision and personalization.
				</p>
			</div>

			<!-- Col 3 -->
			<div class="rounded-lg border border-gray-200 bg-white p-6">
				<div class="mb-4 inline-block rounded bg-blue-100 px-2 py-1 text-[10px] font-bold tracking-widest text-blue-700 uppercase">
					Automated Outreach
				</div>
				<h3 class="mb-3 text-lg font-bold text-gray-900">Outreach that feels personal</h3>
				<p class="text-sm leading-relaxed text-gray-600">
					Your <strong class="text-gray-900">AI agents</strong> handle outreach and follow-ups automatically, so your team can focus on real conversations, not manual messaging.
				</p>
			</div>
		</div>
	</div>
</section>