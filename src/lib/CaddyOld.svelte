<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Caddy Old';
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
    d="M0.0205517,438.8406677C-1.509719,343.198761,82.6551743,231.5423584,172.9411621,132.8398895l62.6877136,3.404541C166.5173645,202.890152,114.3357391,272.2756653,83.6575623,341.7218628c74.9185028-111.3748627,196.2107239-201.4940643,367.7928772-268.562561L512,81.6672592c-122.6836548,35.6786423-256.1451416,120.00103-332.1726379,208.7905273c69.5575867-60.4588928,148.3435669-106.6047668,234.2130432-139.7009735l59.0177002,7.33255c-101.478363,38.8072968-197.8369446,90.6424408-255.3068085,157.2161713c-30.7481079,35.6189575-54.6268311,85.1980286-55.0475311,123.5351257H0.0205517z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Caddy Old';
-->
