<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'GameMaker';
</script>

<svg
  version="1.1"
  xmlns="http://www.w3.org/2000/svg"
  width={size}
  height={size}
  viewBox="0 0 512 512"
  fill={color}
  {...$$restProps}
  {role}
  aria-label={ariaLabel}
  on:click
  on:keydown
  on:keyup
  on:focus
  on:blur
  on:mouseenter
  on:mouseleave
  on:mouseover
  on:mouseout
  ><path
    d="M0,107.7220001c0,0,67.3211365,0,73.5117493,0c7.7081909,0,13.0353088,1.1938782,17.4066391,9.328949l28.0440445,48.8353119l-42.5495758,73.4947357L0,107.7220001z M157.8041687,381.2163391c10.6023712,17.9993896,26.5059357,23.1783447,40.6835327,23.1783447c12.5749054,0,38.2566223,0,38.2566223,0l43.7596741-75.1678162h-67.0511017l-41.9951782-71.9917297l85.754837-149.5135193h-86.1077271l-85.754837,148.454834C85.3499908,256.1764526,147.2017975,363.2169495,157.8041687,381.2163391z M298.1802368,183.1220856l42.7210388,72.785141L255.2883148,404.394989h86.2717133l84.7832947-148.4877625c0,0-52.0557251-89.8311615-69.2808228-119.7632751c-11.6084595-20.1720581-23.2168884-28.4223404-45.6004028-28.4223404c-3.7182007,0-36.3058472,0-36.3058472,0l-42.59552,74.8780899L298.1802368,183.1220856z M392.6841431,346.3493652c0,0,22.2633057,39.0150757,27.0559692,46.4750977c4.7926941,7.4599915,6.8250122,11.5705261,15.7618713,11.5705261c6.6856384,0,76.4980164,0,76.4980164,0l-76.4440002-132.7228088L392.6841431,346.3493652z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'GameMaker';
-->
