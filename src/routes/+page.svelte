<script>
  import Icon from "../components/Icon.svelte";
</script>

<div class="bg-azul-oscuro text-white fixed left-0 top-0 w-full h-full flex flex-col items-center justify-center px-3">
	<img src="./images/logo.svg" class="h-28 md:h-40 w-auto" alt="" />
	<div class="text-center mt-8 uppercase text-[1.1rem] md:text-[1.4rem]">
		<p>Automatización de portones <span class="hidden sm:inline-block">·</span> Cortinas metálicas</p>
		<p>Herrería en general</p>
	</div>
	<div class="text-sm md:text-base font-bold text-white/60 uppercase mt-10 mb-4 bg-slate-400/50 py-1 px-2">
		Contactanos:
	</div>
	<div class="flex flex-col md:flex-row gap-6 md:gap-10 border border-slate-400/80 py-4 px-6">
		<div class="flex justify-center md:justify-normal">
			<a href="https://wa.me/5493815143604" target="_blank">
				<Icon icon="whatsapp" classes="fill-white" />
			</a>
			<a href="https://wa.me/5493815143604" target="_blank">
				<span class="text-lg sm:text-xl inline-block ml-3">+54 9 381 514-3604</span>
			</a>
		</div>
		<div class="flex gap-3">
			<a href="https://www.facebook.com/lm.automatic.ok" target="_blank">
				<Icon icon="facebook" classes="fill-white" />
			</a>
			<a href="https://www.instagram.com/lm.automatic.ok" target="_blank">
				<Icon icon="instagram" classes="fill-white" />
			</a>
			<span class="text-lg sm:text-xl inline-block">@lm.automatic.ok</span>
		</div>
	</div>
</div>