<script>
	export let size = '24';
	export let color = 'currentColor';
	export let ariaLabel = 'Zeit';
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
	aria-label={ariaLabel}><polygon points="256,30 512,482 0,482" /></svg
>
