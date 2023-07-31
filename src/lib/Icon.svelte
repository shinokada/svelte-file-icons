<script>
  import icons from './icons.js'

  export let name;
  export let width = "24";
  export let height = "24";
  export let color = 'currentColor';
  export let role = 'img';
  export let ariaLabel = name;

  $: displayIcon = icons[name]
</script>
<svg
version="1.1"
xmlns="http://www.w3.org/2000/svg"
{width}
{height}
fill={color}
{role}
aria-label={ariaLabel}
{...$$restProps}
class={$$props.class}
viewBox="0 0 512 512"
on:click
on:keydown
on:keyup
on:focus
on:blur
on:mouseenter
on:mouseleave
on:mouseover
on:mouseout
>
  {@html displayIcon.svg}
</svg>

<!--
@component
[Go to Document](https://svelte-file-icons.vercel.app/)
## Props
@prop name;
@prop width = "24";
@prop height = "24";
@prop color = 'currentColor'
@prop role = 'img';
@prop ariaLabel='icon name'
## Event
- on:click
- on:keydown
- on:keyup
- on:focus
- on:blur
- on:mouseenter
- on:mouseleave
- on:mouseover
- on:mouseout
-->