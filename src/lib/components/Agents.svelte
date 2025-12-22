<section class="py-24 bg-gray-50 border-t border-b border-gray-200">
	<div class="mx-auto max-w-[1400px] px-6">
		<div class="mb-12 text-center">
			<div class="mb-4 text-[10px] font-bold tracking-widest text-gray-500 uppercase">[02] Automated Workflows</div>
			<h2 class="text-4xl font-medium tracking-tight text-gray-900">Workflows that run on autopilot</h2>
		</div>

		<!-- Diagram Area -->
		<div class="relative mb-16 overflow-hidden rounded-xl bg-gray-900 p-12 min-h-[500px] flex items-center justify-center">
			<!-- Background Grid -->
			<div class="absolute inset-0 opacity-10" 
				style="background-image: linear-gradient(#ffffff 1px, transparent 1px), linear-gradient(to right, #ffffff 1px, transparent 1px); background-size: 50px 50px;">
			</div>
			
			<div class="relative z-10 w-full max-w-4xl">
				<!-- Central UI -->
				<div class="relative mx-auto max-w-2xl rounded-lg bg-white shadow-2xl overflow-hidden">
					<div class="border-b border-gray-100 bg-gray-50 px-4 py-2 flex justify-between items-center">
						<div class="text-xs font-semibold text-gray-600">Automated Actions (12 today)</div>
					</div>
					<div class="p-4 space-y-3">
						<!-- List Items -->
						{#each [
							{ action: 'Sourced new candidate', name: 'Sarah Chen', role: 'Senior Engineer' },
							{ action: 'Sent follow-up email', name: 'Alex Kumar', role: 'Tech Lead' },
							{ action: 'Scheduled interview', name: 'Jordan Lee', role: 'Full Stack' },
							{ action: 'Updated pipeline stage', name: 'Taylor Park', role: 'Staff Engineer' }
						] as item, i}
							<div class="flex items-center justify-between p-2 hover:bg-gray-50 rounded border border-transparent hover:border-gray-100">
								<div class="flex items-center gap-3">
									<div class="h-6 w-6 rounded bg-green-100 flex items-center justify-center">
										<svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-green-600"><path d="M20 6L9 17l-5-5"/></svg>
									</div>
									<div>
										<div class="text-xs font-medium text-gray-900">{item.action}</div>
										<div class="text-[10px] text-gray-500">{item.name} • {item.role}</div>
									</div>
								</div>
								<div class="text-[10px] text-gray-400">2 min ago</div>
							</div>
						{/each}
					</div>
					
					<!-- Notification Overlay -->
					<div class="absolute bottom-4 left-4 right-4 rounded-lg bg-purple-50 border border-purple-200 shadow-lg p-4">
						<div class="flex items-start gap-3">
							<div class="h-8 w-8 rounded bg-purple-600 flex items-center justify-center text-white flex-shrink-0">
								<svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="m12 3-1.912 5.813a2 2 0 0 1-1.275 1.275L3 12l5.813 1.912a2 2 0 0 1 1.275 1.275L12 21l1.912-5.813a2 2 0 0 1 1.275-1.275L21 12l-5.813-1.912a2 2 0 0 1-1.275-1.275L12 3Z"/></svg>
							</div>
							<div class="flex-1">
								<div class="text-xs font-semibold text-gray-900 mb-1">Workflow completed</div>
								<div class="text-[10px] text-gray-600">5 candidates moved to screening, 3 emails sent</div>
							</div>
						</div>
					</div>
				</div>

				<!-- Floating Workflow Cards -->
				<!-- Auto-sourcing -->
				<div class="absolute top-10 -left-12 bg-white rounded-lg shadow-lg p-3 flex items-center gap-3 animate-bounce" style="animation-duration: 3s;">
					<div class="h-8 w-8 rounded bg-blue-100 flex items-center justify-center text-blue-600">
						<svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="11" cy="11" r="8"/><path d="m21 21-4.35-4.35"/></svg>
					</div>
					<div>
						<div class="text-xs font-bold text-blue-600">Auto-sourcing</div>
						<div class="text-[10px] text-gray-500">Finding candidates 24/7</div>
					</div>
				</div>

				<!-- Email sequences -->
				<div class="absolute -top-6 right-12 bg-white rounded-lg shadow-lg p-3 flex items-center gap-3 animate-bounce" style="animation-duration: 4s;">
					<div class="h-8 w-8 rounded bg-green-100 flex items-center justify-center text-green-600">
						<svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"/><polyline points="22,6 12,13 2,6"/></svg>
					</div>
					<div>
						<div class="text-xs font-bold text-green-600">Email sequences</div>
						<div class="text-[10px] text-gray-500">Auto follow-ups sent</div>
					</div>
				</div>

				<!-- Pipeline updates -->
				<div class="absolute bottom-20 -right-8 bg-white rounded-lg shadow-lg p-3 flex items-center gap-3 animate-bounce" style="animation-duration: 3.5s;">
					<div class="h-8 w-8 rounded bg-purple-100 flex items-center justify-center text-purple-600">
						<svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M21 16V8a2 2 0 0 0-1-1.73l-7-4a2 2 0 0 0-2 0l-7 4A2 2 0 0 0 3 8v8a2 2 0 0 0 1 1.73l7 4a2 2 0 0 0 2 0l7-4A2 2 0 0 0 21 16z"/></svg>
					</div>
					<div>
						<div class="text-xs font-bold text-purple-600">Pipeline updates</div>
						<div class="text-[10px] text-gray-500">Stages auto-managed</div>
					</div>
				</div>
			</div>
		</div>

		<!-- Features Grid -->
		<div class="grid grid-cols-1 gap-8 md:grid-cols-3">
			<!-- Col 1 -->
			<div class="rounded-lg border border-gray-200 bg-white p-6">
				<div class="mb-4 inline-block rounded bg-purple-100 px-2 py-1 text-[10px] font-bold tracking-widest text-purple-700 uppercase">
					Auto-sourcing
				</div>
				<h3 class="mb-3 text-lg font-bold text-gray-900">Candidates while you sleep</h3>
				<p class="text-sm leading-relaxed text-gray-600">
					Set your criteria once and let <strong class="text-gray-900">automated workflows</strong> continuously find and add qualified candidates to your pipeline, 24/7.
				</p>
			</div>

			<!-- Col 2 -->
			<div class="rounded-lg border border-gray-200 bg-white p-6">
				<div class="mb-4 inline-block rounded bg-green-100 px-2 py-1 text-[10px] font-bold tracking-widest text-green-700 uppercase">
					Smart Sequences
				</div>
				<h3 class="mb-3 text-lg font-bold text-gray-900">Follow-ups on autopilot</h3>
				<p class="text-sm leading-relaxed text-gray-600">
					Create <strong class="text-gray-900">email sequences</strong> that automatically follow up with candidates, schedule interviews, and keep your pipeline moving forward.
				</p>
			</div>

			<!-- Col 3 -->
			<div class="rounded-lg border border-gray-200 bg-white p-6">
				<div class="mb-4 inline-block rounded bg-blue-100 px-2 py-1 text-[10px] font-bold tracking-widest text-blue-700 uppercase">
					Stage Automation
				</div>
				<h3 class="mb-3 text-lg font-bold text-gray-900">Pipeline that updates itself</h3>
				<p class="text-sm leading-relaxed text-gray-600">
					Set rules to automatically move candidates between stages based on their actions, responses, or time elapsed. No manual updates needed.
				</p>
			</div>
		</div>
	</div>
</section>