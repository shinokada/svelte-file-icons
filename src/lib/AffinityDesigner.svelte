<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'AffinityDesigner';
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
    d="m199.8418 38.447266l-37.921875 65.679688 15.826172 27.404297-78.710938 136.32812-47.566406 27.464844-51.435547 89.087891 0.009765625 0.001953125-0.04296875 0.0234375 40.068359 69.400391h13.914062l11.208984 19.675781h0.14648438l0.005859375-0.00390625 403.2207 0.04296875 43.423828-74.025391 0.01171875-0.01953125-201.67969-349.31641h-23.09375l-6.7773438-11.744141h-80.607422zm47.464844 120.59375l123.91211 214.08984-145.24414-0.125 15.417969 26.580078h-133.31055l139.22461-240.54492z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'AffinityDesigner';
-->
