<script>
	export let size = '24';
	export let color = 'currentColor';
	export let ariaLabel = 'PNPM';
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
		d="M502,10v140H362V10H502 M326,10v140H186V10H326 M150,10v140H10V10H150 M502,186v140H362V186H502 M512,0H352v160h160V0L512,0z M336,0H176v160h160V0L336,0z M160,0H0v160h160V0L160,0z M512,176H352v160h160V176L512,176z M336,336H176V176h160V336z M336,352H176v160h160V352z M512,352H352v160h160V352z M160,352H0v160h160V352z"
	/></svg
>
