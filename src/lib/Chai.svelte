<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Chai';
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
    d="M35.1381798,363.9184875l186.5649872,107.7161865l186.5745697-107.7161865V148.4909668L221.7031708,40.7780075L35.1381798,148.4909668V363.9184875z M221.7028198,512.2020264L0,384.2002869V128.2071991L221.7028198,0.202l221.7131958,128.0052032v255.9930878L221.7028198,512.2020264z M300.7592468,133.9240875c35.2896423,28.6616364,5.6690369,103.7275696-51.7827148,122.1116486l-3.8561401-6.4269104c39.4729919-21.9160309,39.8807678-65.2945099,26.0457153-87.8052673C258.8996887,141.845108,212.25,126.5,176.860672,179.8156891c-11.063385,16.667511-20.4669647,46.8334656-20.7991486,75.1182861c-0.8260345,74.0853424,70.1735382,149.2127838,140.6579285,74.919632l6.0596619,5.8760681C225.3333282,427,125.3333359,397.6666565,115.8473053,281.1925659C120,178,241.5778961,87.2546539,300.7592468,133.9240875z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Chai';
-->
