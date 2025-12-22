<script>
	import Navbar from "$lib/components/Navbar.svelte";
	import Hero from "$lib/components/Hero.svelte";
	import DemoSection from "$lib/components/DemoSection.svelte";
	import Features from "$lib/components/Features.svelte";
	import Agents from "$lib/components/Agents.svelte";
	import Integrations from "$lib/components/Integrations.svelte";
	import Stories from "$lib/components/Stories.svelte";
	import Updates from "$lib/components/Updates.svelte";
	import FAQ from "$lib/components/FAQ.svelte";
	import Footer from "$lib/components/Footer.svelte";
</script>

<svelte:head>
	<title>Cracked - AI-Native ATS for Your First 100 Hires</title>
	<meta name="description" content="Replace your messy Notion pipeline with Cracked, the open-source ATS built for seed-stage founders. Automated sourcing, workflows, and one-click imports." />
</svelte:head>

<main class="font-sans text-gray-900 antialiased selection:bg-purple-200 selection:text-purple-900">
	<Navbar />
	<Hero />
	<DemoSection />
	<Features />
	<Agents />
	<Integrations />
	<Stories />
	<Updates />
	<FAQ />
	<Footer />
</main>

