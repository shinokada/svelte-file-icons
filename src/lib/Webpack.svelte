<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Webpack';
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
    d="M355.0114136,174.6519165l-124.1871338,71.7220459L106.630249,174.6556396l124.1939697-68.3209229L355.0114136,174.6519165z M241.8120117,265.434021v131.1519165l123.7680664-68.0667725V193.9533691L241.8120117,265.434021z M16.1795044,395.7438965l203.6325073,115.1856079v-89.2358398L92.489502,351.6723633L16.1795044,395.7438965z M219.8120117,396.5859375v-131.166626l-123.7680664-71.472168v134.5722656L219.8120117,396.5859375z M241.8120117,1.0708008v86.1991577l135.4661865,74.5221558l73.5410767-42.4723511L241.8120117,1.0708008z M369.1555786,351.6605225l-127.3435669,70.0331421v89.2357788l203.6576538-115.1998291L369.1555786,351.6605225z M387.5800781,181.2475586v155.6484985l74.0437622,42.7579956V138.4845581L387.5800781,181.2475586z M84.3620605,161.7963867l135.4499512-74.5130005V1.0707397L10.8051758,119.319458L84.3620605,161.7963867z M74.0439453,336.9199219v-155.677063L0,138.4848022v241.197937L74.0439453,336.9199219z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Webpack';
-->
