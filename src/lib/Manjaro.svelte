<script>
	export let size = '24';
	export let color = 'currentColor';
	export let ariaLabel = 'Manjaro';
</script>

<svg
	version="1.1"
	xmlns="http://www.w3.org/2000/svg"
	width={size}
	height={size}
	viewBox="0 0 512 512"
	fill={color}
	class={$$props.class}
	{...$$restProps}
	aria-label={ariaLabel}
	><path
		d="M0,0v512h144V144h184V0H0z M183.9999847,184L184,512h144V184H183.9999847z M368,0.000008v512h144v-512H368z"
	/></svg
>
