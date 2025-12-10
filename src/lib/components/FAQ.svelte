<script>
	let openIndex = 0;
	const faqs = [
		{
			question: "Who can use Juicebox?",
			answer: "Juicebox is built for recruiters. If you are searching for hard-to-find talent, Juicebox is a fit for you. We work with companies ranging from Fortune 500 to boutique recruiting agencies — and hopefully, you too."
		},
		{
			question: "Can I try Juicebox for free?",
			answer: "Yes! We offer a free trial so you can experience the power of our AI agents firsthand."
		},
		{
			question: "Can I use Juicebox with my team?",
			answer: "Absolutely. Juicebox is designed for collaboration, allowing your entire recruiting team to share insights and candidate pools."
		},
		{
			question: "How long does it take to set up and start using Juicebox?",
			answer: "You can get started in minutes. Our onboarding is streamlined to get you sourcing candidates immediately."
		},
		{
			question: "Does Juicebox have global candidate data?",
			answer: "Yes, we have access to over 800M+ profiles globally across various industries and regions."
		},
		{
			question: "Will it integrate with my ATS or CRM?",
			answer: "We integrate with all major ATS and CRM platforms including Greenhouse, Lever, Ashby, and more."
		}
	];
</script>

<section class="py-24">
	<div class="mx-auto max-w-[1400px] px-6">
		<div class="grid grid-cols-1 gap-16 lg:grid-cols-12">
			<!-- Left Side -->
			<div class="lg:col-span-4">
				<div class="mb-4 text-[10px] font-bold tracking-widest text-gray-500 uppercase">[06] FAQ</div>
				<h2 class="mb-6 text-4xl font-medium tracking-tight text-gray-900">Your questions, answered</h2>
				<p class="mb-8 text-lg leading-relaxed text-gray-600">
					We're here to help. Reach out to our sales team for guidance on how to integrate Juicebox into your recruiting workflow.
				</p>
				<a href="#" class="inline-block bg-gray-900 px-6 py-3 text-[11px] font-bold tracking-widest text-white transition-colors hover:bg-gray-800 uppercase">
					Book a Demo
				</a>
			</div>

			<!-- Right Side (Accordion) -->
			<div class="lg:col-span-8">
				<div class="divide-y divide-gray-200 border-t border-b border-gray-200">
					{#each faqs as faq, i}
						<div class="group">
							<button 
								class="flex w-full items-center justify-between py-6 text-left focus:outline-none"
								onclick={() => openIndex = openIndex === i ? -1 : i}
							>
								<span class="text-lg font-medium text-gray-900">{faq.question}</span>
								<span class="ml-4 flex h-6 w-6 items-center justify-center text-gray-400">
									{#if openIndex === i}
										<svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M18 6L6 18M6 6l12 12"/></svg>
									{:else}
										<svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M12 5v14M5 12h14"/></svg>
									{/if}
								</span>
							</button>
							{#if openIndex === i}
								<div class="pb-6 text-gray-600 leading-relaxed">
									{faq.answer}
								</div>
							{/if}
						</div>
					{/each}
				</div>
			</div>
		</div>
	</div>
</section>