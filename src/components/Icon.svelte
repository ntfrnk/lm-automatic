<script>
	import icons from '../config/icons';

	export let icon;
	export let size = 30;
	export let classes = ''
</script>

<svg version="1.1" xmlns="http://www.w3.org/2000/svg" class="{classes}" width={size} height={size} viewBox="0 0 32 32">
	<path d={icons[icon]}></path>
</svg>