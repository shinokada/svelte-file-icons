<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'DataWeave';
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
    d="M408.8358154,54.1912193L179.5384216,381.6965332L53.3178635,201.4157867l49.8463135-71.1123352l99.5397873,142.1809845L256,196.328537l-26.6589355-38.0561218l-26.6371002,38.0561218L103.1641769,54.1912193L0,201.4157867l179.5384216,256.3930054l229.2973938-327.5053101l49.846344,71.1123352L332.4615784,381.6965332l-23.1437073-33.0780029l-26.6589355,38.0779419l49.8026428,71.1123047L512,201.4157867L408.8358154,54.1912193z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'DataWeave';
-->
