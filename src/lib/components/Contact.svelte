<section class="w-full bg-white py-16 md:py-24" id="contact">
	<div class="mx-auto grid max-w-[1800px] grid-cols-1 gap-16 px-6 md:px-12 lg:grid-cols-2 lg:gap-24 lg:px-20">
		<!-- Left Column -->
		<div class="flex flex-col justify-between">
			<div>
				<h2 class="mb-8 text-3xl font-bold leading-tight tracking-tight text-black md:text-4xl">
					Get started with reliable<br />
					facility maintenance today.
				</h2>
			</div>

			<div class="mt-12 lg:mt-auto">
				<p class="font-bold text-black">Gallery Facility Services</p>
				<p class="text-gray-600">Commercial Property Maintenance</p>
				<a href="tel:317-953-2544" class="mt-2 block text-lg font-bold text-black underline decoration-1 underline-offset-4 hover:decoration-2">
					317-953-2544
				</a>
				<p class="mt-4 text-gray-600">
					3815 River Crossing Parkway, Suite 100<br />
					Indianapolis, IN 46240
				</p>
			</div>
		</div>

		<!-- Right Column: Form -->
		<div>
			<div class="mb-12 aspect-[4/3] w-full overflow-hidden bg-gray-100">
				<img
					src="/generated/image-friendly-facility-services-manager-with--1767891508992-5.webp"
					alt="Gallery Facility Services representative"
					class="h-full w-full object-cover object-center"
				/>
			</div>

			<form class="flex flex-col gap-6">
				<div class="grid grid-cols-1 gap-6 md:grid-cols-2">
					<div class="flex flex-col gap-2">
						<label for="firstname" class="text-xs font-bold uppercase tracking-wider text-black">First Name</label>
						<input type="text" id="firstname" placeholder="First Name" class="border-b border-gray-300 py-2 text-gray-900 placeholder-gray-400 focus:border-black focus:outline-none" />
					</div>
					<div class="flex flex-col gap-2">
						<label for="lastname" class="text-xs font-bold uppercase tracking-wider text-black">Last Name</label>
						<input type="text" id="lastname" placeholder="Last Name" class="border-b border-gray-300 py-2 text-gray-900 placeholder-gray-400 focus:border-black focus:outline-none" />
					</div>
				</div>

				<div class="flex flex-col gap-2">
					<label for="email" class="text-xs font-bold uppercase tracking-wider text-black">Email Address</label>
					<input type="email" id="email" placeholder="Email" class="border-b border-gray-300 py-2 text-gray-900 placeholder-gray-400 focus:border-black focus:outline-none" />
				</div>

				<div class="flex flex-col gap-2">
					<label for="phone" class="text-xs font-bold uppercase tracking-wider text-black">Phone Number</label>
					<input type="tel" id="phone" placeholder="(317) 555-0100" class="border-b border-gray-300 py-2 text-gray-900 placeholder-gray-400 focus:border-black focus:outline-none" />
				</div>

				<div class="flex flex-col gap-2">
					<label for="message" class="text-xs font-bold uppercase tracking-wider text-black">Tell us about your maintenance needs</label>
					<textarea id="message" rows="3" placeholder="Describe your property and service requirements..." class="border-b border-gray-300 py-2 text-gray-900 placeholder-gray-400 focus:border-black focus:outline-none"></textarea>
				</div>

				<div class="mt-4 flex items-start gap-3">
					<input type="checkbox" id="privacy" class="mt-1 h-4 w-4 border-gray-300 text-black focus:ring-black" />
					<label for="privacy" class="text-xs leading-relaxed text-gray-600">
						I agree to be contacted regarding my facility maintenance inquiry. View our <a href="#" class="underline">Privacy Policy</a>.
					</label>
				</div>

				<button type="submit" class="mt-8 w-full bg-black py-4 px-8 text-center text-sm font-bold uppercase tracking-wider text-white transition-opacity hover:opacity-90">
					Submit Work Order
				</button>
			</form>
		</div>
	</div>
</section>
