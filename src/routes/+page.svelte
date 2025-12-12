<script lang="ts">
	import { onMount } from 'svelte';

	let scrollY = 0;
</script>

<svelte:head>
	<title>Avocado Creative - Professional Brand Identity Design for Small Businesses</title>
	<meta name="description" content="Transform your brand identity with strategic design systems that scale. Professional branding for small businesses without the agency price tag or endless timelines." />
</svelte:head>

<svelte:window bind:scrollY />

<div class="font-sans text-gray-900 antialiased selection:bg-primary-200 selection:text-primary-900">
	<!-- Hero Section -->
	<section class="relative min-h-screen w-full bg-gradient-to-b from-gray-950 via-gray-900 to-gray-50 text-white px-6 md:px-12 lg:px-24 pt-32 pb-24 flex flex-col justify-between">
		<div class="max-w-5xl">
			<h1 class="font-serif text-5xl md:text-7xl lg:text-8xl leading-[1.1] md:leading-[1.1] tracking-tight">
				Transform your brand identity with strategic design systems that scale.
			</h1>
			<p class="text-xl md:text-2xl text-gray-300 mt-8 max-w-3xl">
				Professional branding for small businesses without the agency price tag or endless timelines.
			</p>
		</div>

		<div class="mt-24 flex gap-4">
			<a href="#work" class="inline-flex items-center justify-center px-6 py-3 bg-primary-500 text-white rounded-full text-sm font-medium hover:bg-primary-600 transition-colors duration-300">
				See our work
			</a>
			<a href="#process" class="inline-flex items-center justify-center px-6 py-3 border border-white/30 rounded-full text-sm font-medium hover:bg-white hover:text-gray-900 transition-colors duration-300 backdrop-blur-sm">
				Our process
			</a>
		</div>
	</section>

	<!-- Who We Serve -->
	<section class="bg-white px-6 md:px-12 lg:px-24 py-16 md:py-24">
		<p class="text-lg md:text-xl text-gray-600 mb-12">Trusted by small businesses across industries</p>
		
		<div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-6 gap-4 md:gap-8">
			<!-- Business type badges -->
			{#each ['Restaurants', 'Cafés', 'Retail', 'Wellness', 'Professional Services', 'Hospitality'] as businessType}
				<div class="h-20 bg-gray-50 border border-gray-200 rounded-lg flex items-center justify-center hover:border-primary-400 hover:bg-primary-50 transition-all duration-300">
					<span class="font-medium text-gray-700 text-sm text-center px-2">{businessType}</span>
				</div>
			{/each}
		</div>
	</section>

    <!-- Work Section -->
    <section class="bg-white px-6 md:px-12 lg:px-24 py-12 md:py-24" id="work">
        <div class="flex flex-col md:flex-row justify-between items-end mb-16 md:mb-24">
            <h2 class="font-serif text-3xl md:text-4xl lg:text-5xl text-gray-900">Brand identities that grow with your business</h2>
            <a href="/work" class="hidden md:inline-flex items-center text-gray-500 hover:text-gray-900 transition-colors mt-4 md:mt-0">
                View all projects <span class="ml-2">→</span>
            </a>
        </div>

        <div class="space-y-24 md:space-y-32">
            <!-- Project 1: Farm-to-Table Restaurant -->
            <div class="group grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
                <div class="lg:col-span-4 space-y-6">
                    <h3 class="font-serif text-3xl md:text-4xl text-gray-900">Farm-to-Table Restaurant</h3>
                    <p class="text-gray-600 text-lg leading-relaxed">
                        Complete brand identity system for a local restaurant, from logo design to menu layouts, signage, and digital presence. Created a warm, authentic identity that reflects their commitment to fresh, local ingredients.
                    </p>
                    <div class="flex flex-wrap gap-2 pt-2">
                        <span class="px-3 py-1 border border-gray-200 rounded-full text-xs font-medium text-gray-600">Brand Identity</span>
                        <span class="px-3 py-1 border border-gray-200 rounded-full text-xs font-medium text-gray-600">Print Design</span>
                        <span class="px-3 py-1 border border-gray-200 rounded-full text-xs font-medium text-gray-600">Signage</span>
                    </div>
                </div>
                <div class="lg:col-span-8">
                    <div class="aspect-[16/9] bg-gray-100 rounded-lg overflow-hidden relative group-hover:scale-[1.02] transition-transform duration-500 ease-out">
                        <img src="/generated/image-modern-restaurant-interior-with-branded--1765497799068-4.webp" alt="Restaurant branding" class="w-full h-full object-cover" />
                    </div>
                </div>
            </div>

            <!-- Project 2: Artisan Coffee Shop -->
            <div class="group grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
                <div class="lg:col-span-4 space-y-6">
                    <h3 class="font-serif text-3xl md:text-4xl text-gray-900">Artisan Coffee Shop</h3>
                    <p class="text-gray-600 text-lg leading-relaxed">
                        A cohesive brand identity that extends across cups, packaging, signage, and digital touchpoints. Designed to create a memorable experience that keeps customers coming back.
                    </p>
                    <div class="flex flex-wrap gap-2 pt-2">
                        <span class="px-3 py-1 border border-gray-200 rounded-full text-xs font-medium text-gray-600">Brand Identity</span>
                        <span class="px-3 py-1 border border-gray-200 rounded-full text-xs font-medium text-gray-600">Packaging</span>
                        <span class="px-3 py-1 border border-gray-200 rounded-full text-xs font-medium text-gray-600">Environmental Design</span>
                    </div>
                </div>
                <div class="lg:col-span-8">
                    <div class="aspect-[16/9] bg-gray-100 rounded-lg overflow-hidden relative group-hover:scale-[1.02] transition-transform duration-500 ease-out">
                        <img src="/generated/image-coffee-shop-counter-with-branded-cups-pa-1765497802253-5.webp" alt="Coffee shop branding" class="w-full h-full object-cover" />
                    </div>
                </div>
            </div>

            <!-- Project 3: Boutique Retail -->
            <div class="group grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
                <div class="lg:col-span-4 space-y-6">
                    <h3 class="font-serif text-3xl md:text-4xl text-gray-900">Boutique Retail</h3>
                    <p class="text-gray-600 text-lg leading-relaxed">
                        A sophisticated brand system for a boutique retail store, including logo, shopping bags, tags, and in-store materials. Clean, modern aesthetic that elevates the shopping experience and builds brand recognition.
                    </p>
                    <div class="flex flex-wrap gap-2 pt-2">
                        <span class="px-3 py-1 border border-gray-200 rounded-full text-xs font-medium text-gray-600">Brand Identity</span>
                        <span class="px-3 py-1 border border-gray-200 rounded-full text-xs font-medium text-gray-600">Packaging</span>
                        <span class="px-3 py-1 border border-gray-200 rounded-full text-xs font-medium text-gray-600">Retail Design</span>
                    </div>
                </div>
                <div class="lg:col-span-8">
                    <div class="aspect-[16/9] bg-gray-100 rounded-lg overflow-hidden relative group-hover:scale-[1.02] transition-transform duration-500 ease-out">
                        <img src="/generated/image-boutique-retail-store-interior-with-bran-1765497805276-6.webp" alt="Retail branding" class="w-full h-full object-cover" />
                    </div>
                </div>
            </div>

            <!-- Project 4: Wellness Studio -->
            <div class="group grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
                <div class="lg:col-span-4 space-y-6">
                    <h3 class="font-serif text-3xl md:text-4xl text-gray-900">Wellness Studio</h3>
                    <p class="text-gray-600 text-lg leading-relaxed">
                        Calming, professional brand identity for a wellness and yoga studio. Created a cohesive system that extends from signage and business cards to digital platforms, reflecting the studio's peaceful, centered approach.
                    </p>
                    <div class="flex flex-wrap gap-2 pt-2">
                        <span class="px-3 py-1 border border-gray-200 rounded-full text-xs font-medium text-gray-600">Brand Identity</span>
                        <span class="px-3 py-1 border border-gray-200 rounded-full text-xs font-medium text-gray-600">Environmental Design</span>
                        <span class="px-3 py-1 border border-gray-200 rounded-full text-xs font-medium text-gray-600">Digital</span>
                    </div>
                </div>
                <div class="lg:col-span-8">
                    <div class="aspect-[16/9] bg-gray-100 rounded-lg overflow-hidden relative group-hover:scale-[1.02] transition-transform duration-500 ease-out">
                        <img src="/generated/image-wellness-studio-reception-area-with-bran-1765497807996-7.webp" alt="Wellness studio branding" class="w-full h-full object-cover" />
                    </div>
                </div>
            </div>
        </div>
        
        <div class="mt-12 md:hidden">
            <a href="/work" class="flex items-center text-gray-500 hover:text-gray-900 transition-colors">
                View all projects <span class="ml-2">→</span>
            </a>
        </div>
    </section>

    <!-- Process Section -->
    <section class="bg-gray-50 px-6 md:px-12 lg:px-24 py-12 md:py-24" id="process">
        <h2 class="font-serif text-3xl md:text-4xl lg:text-5xl text-gray-900 mb-16 max-w-3xl">A streamlined process designed for small business success</h2>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <!-- Discover -->
            <div class="bg-white p-8 rounded-xl shadow-sm hover:shadow-md transition-shadow duration-300 flex flex-col h-full min-h-[400px]">
                <h3 class="text-xl font-semibold mb-4">Discover</h3>
                <p class="text-gray-600 text-sm leading-relaxed mb-auto">
                    We start by understanding your business, values, and target audience. Through collaborative workshops, we uncover what makes your brand unique and develop a strategic foundation.
                </p>
                <div class="mt-8 flex justify-center h-48 items-end">
                    <img src="/generated/image-close-up-of-hands-sketching-logo-concept-1765497788600-1.webp" alt="Discovery process" class="h-full w-full object-cover rounded-lg" />
                </div>
            </div>

            <!-- Design -->
            <div class="bg-white p-8 rounded-xl shadow-sm hover:shadow-md transition-shadow duration-300 flex flex-col h-full min-h-[400px]">
                <h3 class="text-xl font-semibold mb-4">Design</h3>
                <p class="text-gray-600 text-sm leading-relaxed mb-auto">
                    We craft a complete brand identity system—logo, colors, typography, and visual elements—that works seamlessly across all touchpoints, from business cards to digital platforms.
                </p>
                <div class="mt-8 flex justify-center h-48 items-end">
                    <img src="/generated/image-designer-working-on-brand-identity-syste-1765497792119-2.webp" alt="Design process" class="h-full w-full object-cover rounded-lg" />
                </div>
            </div>

            <!-- Deploy -->
            <div class="bg-white p-8 rounded-xl shadow-sm hover:shadow-md transition-shadow duration-300 flex flex-col h-full min-h-[400px]">
                <h3 class="text-xl font-semibold mb-4">Deploy</h3>
                <p class="text-gray-600 text-sm leading-relaxed mb-auto">
                    We deliver production-ready files and comprehensive brand guidelines, ensuring your team can confidently apply your new identity across every customer touchpoint.
                </p>
                <div class="mt-8 flex justify-center h-48 items-end">
                    <img src="/generated/image-small-business-storefront-with-professio-1765497795082-3.webp" alt="Deployment" class="h-full w-full object-cover rounded-lg" />
                </div>
            </div>
        </div>
    </section>

    <!-- Thoughts Section -->
    <section class="bg-white px-6 md:px-12 lg:px-24 py-12 md:py-24">
        <div class="flex flex-col md:flex-row justify-between items-end mb-12">
            <h2 class="font-serif text-3xl md:text-4xl text-gray-900">Insights on branding and small business growth</h2>
            <a href="/blog" class="hidden md:inline-flex items-center text-gray-500 hover:text-gray-900 transition-colors mt-4 md:mt-0">
                Read all articles <span class="ml-2">→</span>
            </a>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
            <!-- Blog Post 1 -->
            <div class="group cursor-pointer">
                <div class="aspect-square bg-primary-600 rounded-lg overflow-hidden mb-4 relative">
                     <div class="absolute inset-0 flex items-center justify-center text-white font-bold text-2xl text-center p-8">Why Your Brand Identity Matters More Than Ever</div>
                </div>
                <h3 class="text-sm font-medium text-gray-900 group-hover:underline">Why Your Brand Identity Matters More Than Ever</h3>
            </div>

             <!-- Blog Post 2 -->
             <div class="group cursor-pointer">
                <div class="aspect-square bg-gray-900 rounded-lg overflow-hidden mb-4 relative">
                    <div class="absolute inset-0 flex items-center justify-center text-white font-medium text-2xl text-center p-8">5 Signs It's Time to Rebrand Your Business</div>
                </div>
                <h3 class="text-sm font-medium text-gray-900 group-hover:underline">5 Signs It's Time to Rebrand Your Business</h3>
            </div>

             <!-- Blog Post 3 -->
             <div class="group cursor-pointer">
                <div class="aspect-square bg-primary-500 rounded-lg overflow-hidden mb-4 relative">
                     <div class="absolute inset-0 flex items-center justify-center text-white text-center p-8 flex-col">
                        <span class="text-sm uppercase tracking-widest mb-2">Design Systems</span>
                        <span class="text-2xl font-serif">that scale with your business</span>
                     </div>
                </div>
                <h3 class="text-sm font-medium text-gray-900 group-hover:underline">Building a Design System That Scales With Your Business</h3>
            </div>

             <!-- Blog Post 4 -->
             <div class="group cursor-pointer">
                <div class="aspect-square bg-gray-800 rounded-lg overflow-hidden mb-4 relative">
                    <div class="absolute inset-0 flex items-center justify-center text-white font-medium text-2xl text-center p-8">How to Choose the Right Colors for Your Brand</div>
                </div>
                <h3 class="text-sm font-medium text-gray-900 group-hover:underline">How to Choose the Right Colors for Your Brand</h3>
            </div>

             <!-- Blog Post 5 -->
             <div class="group cursor-pointer">
                <div class="aspect-square bg-primary-700 rounded-lg overflow-hidden mb-4 relative flex items-center justify-center">
                    <div class="text-white font-medium text-2xl text-center p-8">
                        The ROI of Professional Branding for Small Businesses
                    </div>
                </div>
                <h3 class="text-sm font-medium text-gray-900 group-hover:underline">The ROI of Professional Branding for Small Businesses</h3>
            </div>

             <!-- Blog Post 6 -->
             <div class="group cursor-pointer">
                <div class="aspect-square bg-gray-900 rounded-lg overflow-hidden mb-4 relative">
                     <div class="absolute inset-0 flex items-center justify-center text-white font-medium text-2xl text-center p-8">Restaurant Branding: Standing Out in a Crowded Market</div>
                </div>
                <h3 class="text-sm font-medium text-gray-900 group-hover:underline">Restaurant Branding: Standing Out in a Crowded Market</h3>
            </div>
        </div>
    </section>

    <!-- Newsletter Section -->
    <section class="px-6 md:px-12 lg:px-24 py-12">
        <div class="bg-gradient-to-r from-primary-100 to-primary-50 rounded-2xl p-8 md:p-16 lg:p-20">
            <h3 class="font-serif text-2xl md:text-3xl text-gray-900 mb-4">Get branding tips delivered to your inbox</h3>
            <p class="text-gray-600 mb-8 max-w-md">Monthly insights on brand strategy, design trends, and small business growth. No spam, just value.</p>
            
            <form class="flex flex-col sm:flex-row gap-4 max-w-lg">
                <input type="email" placeholder="you@yourbusiness.com" class="flex-1 bg-white/80 border-0 rounded-lg px-4 py-3 text-sm placeholder:text-gray-400 focus:ring-2 focus:ring-primary-500 outline-none" />
                <button type="submit" class="bg-primary-600 hover:bg-primary-700 text-white transition-colors px-6 py-3 rounded-lg text-sm font-medium">
                    Subscribe
                </button>
            </form>
            <p class="text-[10px] text-gray-500 mt-4">We respect your privacy. Unsubscribe anytime. By signing up, you agree to receive communications from Avocado Creative.</p>
        </div>
    </section>

    <!-- CTA Section -->
    <section class="relative bg-gradient-to-b from-gray-900 via-gray-800 to-gray-950 pt-32 pb-48 px-6 md:px-12 lg:px-24 overflow-hidden">
        <div class="max-w-5xl relative z-10">
            <h2 class="font-serif text-4xl md:text-6xl lg:text-7xl text-white leading-tight mb-8">
                Ready to transform your brand? <br />
                <span class="text-white/70">Let's create a brand identity that grows with your business—without the agency price tag or endless timelines.</span>
            </h2>
            
            <div class="mt-16 flex gap-4">
                 <a href="/contact" class="inline-flex items-center justify-center px-6 py-3 bg-primary-500 text-white rounded-full text-sm font-medium hover:bg-primary-600 transition-colors duration-300">
                    Start Your Project
                </a>
                 <a href="#process" class="inline-flex items-center justify-center px-6 py-3 border border-white/30 rounded-full text-sm font-medium text-white hover:bg-white hover:text-gray-900 transition-colors duration-300 backdrop-blur-sm">
                    Learn More
                </a>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-950 text-gray-300 px-6 md:px-12 lg:px-24 pt-24 pb-12 relative overflow-hidden">
        <div class="relative z-10">
            <div class="grid grid-cols-1 md:grid-cols-3 gap-12 mb-24">
                <div class="col-span-1 md:col-span-2">
                    <h3 class="text-3xl font-serif text-white mb-6">Avocado Creative</h3>
                    <p class="text-gray-400 mb-8 max-w-md">
                        Transforming brand identities through strategic design systems that scale across all touchpoints.
                    </p>
                    <a href="/contact" class="text-xl font-medium text-primary-400 hover:text-primary-300 transition-colors inline-flex items-center">
                        Start your project <span class="ml-2">→</span>
                    </a>
                </div>
                
                <div class="space-y-4">
                    <h4 class="font-medium text-white">Get in Touch</h4>
                    <div class="pt-4 text-sm space-y-2">
                        <p><a href="mailto:hello@avocadocreative.com" class="hover:text-primary-400 transition-colors">hello@avocadocreative.com</a></p>
                        <p class="pt-4 text-gray-500">Available for projects starting at $5,000</p>
                    </div>
                </div>
            </div>

            <div class="flex flex-col md:flex-row justify-between items-start md:items-center border-t border-white/10 pt-8 gap-6">
                <div class="flex gap-8 text-sm">
                    <a href="/work" class="hover:text-primary-400 transition-colors">Work</a>
                    <a href="/process" class="hover:text-primary-400 transition-colors">Process</a>
                    <a href="/about" class="hover:text-primary-400 transition-colors">About</a>
                    <a href="/blog" class="hover:text-primary-400 transition-colors">Blog</a>
                    <a href="/contact" class="hover:text-primary-400 transition-colors">Contact</a>
                </div>
                
                <div class="flex gap-6 text-sm">
                    <a href="#" class="hover:text-primary-400 transition-colors">LinkedIn</a>
                    <a href="#" class="hover:text-primary-400 transition-colors">Instagram</a>
                    <a href="#" class="hover:text-primary-400 transition-colors">Twitter</a>
                </div>
            </div>

            <div class="flex flex-col md:flex-row justify-between text-xs text-gray-500 mt-12 gap-4">
                <p>© 2025 Avocado Creative. All rights reserved.</p>
                <div class="flex gap-6">
                    <a href="/privacy" class="hover:text-gray-400 transition-colors">Privacy Policy</a>
                    <a href="/terms" class="hover:text-gray-400 transition-colors">Terms of Service</a>
                </div>
            </div>
        </div>
    </footer>
</div>
