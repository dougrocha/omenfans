<script>
	import { cn } from '$lib/utils';
	import omenFullBodyImg from '$lib/images/omen-full-body.webp';
	import valorantLogoImg from '$lib/images/valorant-logo.png';
</script>

<div class="flex items-center justify-center">
	<img src={omenFullBodyImg} alt="Omen full body" class="mt-20 w-72 select-none" />
</div>

<div class="flex flex-col items-start p-4 sm:items-center">
	<img src={valorantLogoImg} alt="Valorant logo" class="w-24 select-none" />
	<span class={cn('select-none text-6xl font-bold text-[#ece8e1]')}>Coming Soon</span>
</div>
