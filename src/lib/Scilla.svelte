<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Scilla';
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
    d="m72.633296 93.24691-72.633296 131.9907 111.61818 193.45349l81.3626-0.1027-33.86299-58.50532 155.88668-1.09156s37.97211-67.68973 38.06127-67.90945c0.12738-0.31845-234.12079-0.39806-234.12079-0.39806l-38.319378-66.19897 73.059338-130.73123z"
  /><path
    d="m432.61275 289.14873c-0.72606 1.62885-74.61907 129.12598-74.61907 129.4906 0 0.21336 81.3637 0.0611 81.3637 0.0611l72.64263-131.2443-111.46269-194.20917h-81.50561l34.42897 58.275143s-155.10271 0.93862-156.24116 1.066l-38.31635 68.19619 235.2932 0.0218z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Scilla';
-->
