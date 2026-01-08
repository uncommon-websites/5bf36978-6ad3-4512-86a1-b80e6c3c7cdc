<section class="w-full bg-white py-16 md:py-24" id="process">
	<div class="mx-auto grid max-w-[1800px] grid-cols-1 gap-16 px-6 md:px-12 lg:grid-cols-2 lg:gap-24 lg:px-20">
		<!-- Left Column -->
		<div class="flex flex-col justify-between">
			<div>
				<h2 class="mb-8 text-4xl font-bold leading-tight tracking-tight text-black md:text-5xl lg:text-6xl">
					Fast, reliable service.<br />
					Simple process.
				</h2>
				<p class="mb-8 max-w-md text-lg leading-relaxed text-gray-800">
					Our streamlined workflow ensures your commercial property stays operational with minimal disruption.
				</p>
				<a href="tel:317-953-2544" class="text-lg font-medium text-black underline decoration-1 underline-offset-4 hover:decoration-2">
					Call 317-953-2544
				</a>
			</div>
		</div>

		<!-- Right Column: Steps -->
		<div>
			<div class="flex flex-col">
				{#each [
					{ id: 1, title: 'Submit Work Order' },
					{ id: 2, title: 'Assessment & Quote' },
					{ id: 3, title: 'Schedule Service' },
					{ id: 4, title: 'Expert Execution' },
					{ id: 5, title: 'Quality Inspection' },
					{ id: 6, title: 'Ongoing Maintenance' }
				] as step}
					<div class="group flex cursor-pointer items-center justify-between border-b border-gray-200 py-6 transition-colors hover:bg-gray-50">
						<div class="flex items-center gap-6">
							<div class="flex h-8 w-8 items-center justify-center rounded-full bg-black text-sm font-bold text-white">
								{step.id}
							</div>
							<span class="text-xl font-medium text-gray-900">{step.title}</span>
						</div>
						<svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1" class="text-gray-400 transition-transform group-hover:rotate-90 group-hover:text-black">
							<line x1="12" y1="5" x2="12" y2="19"></line>
							<line x1="5" y1="12" x2="19" y2="12"></line>
						</svg>
					</div>
				{/each}
			</div>

			<div class="mt-12">
				<a href="#contact" class="inline-block w-full bg-black py-4 px-8 text-center text-sm font-bold uppercase tracking-wider text-white transition-opacity hover:opacity-90 md:w-auto">
					Get Started Today
				</a>
			</div>
		</div>
	</div>
</section>
