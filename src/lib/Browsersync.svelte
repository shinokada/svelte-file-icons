<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Browsersync';
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
    d="M159.2691345,0.7931548L4.2638984,78.2957764C1.7557229,79.5498657,0,82.0580368,0,85.0678558v341.8643188c0,2.7590027,1.5049053,5.5179749,4.2638984,6.7720642l155.0052338,77.502594c5.0163574,2.5081787,10.7851715-1.2540894,10.7851715-6.7720642V7.5652285C170.054306,2.0472424,164.2854919-1.7150207,159.2691345,0.7931548z M200.7308655,511.2068481l155.005249-77.502594C358.2442932,432.4501648,360,429.9419861,360,426.9321899V260.6401367c0-2.7589722-1.5049133-5.5179596-4.2638855-6.772049l-155.005249-77.5026398c-5.0163574-2.5081787-10.7851715,1.2540741-10.7851715,6.7720642v321.2972717C189.945694,509.9527588,195.7145081,513.7150269,200.7308655,511.2068481z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Browsersync';
-->
