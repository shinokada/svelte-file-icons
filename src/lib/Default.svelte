<script>
	export let size = '24';
	export let color = 'currentColor';
	export let ariaLabel = 'Default';
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
	><path d="M288,32H0v448h384V128L288,32z M352,448H32V64h224l96,96V448z" /></svg
>
