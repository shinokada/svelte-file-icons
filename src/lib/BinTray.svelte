<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'BinTray';
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
    d="M0,476.0701904h400.3609314V512H0V476.0701904z M286.1553955,170.6666718v35.9298401h52.6115417L218.1453705,327.2180786V69.2932358l37.213028,37.2130356l25.6641541-25.6641617L200.1804657,0L119.338356,80.8421097l25.6641617,25.6641617l37.213028-38.4962387v259.2080383L61.5939903,206.5965118h52.6115227v-35.9298401H0v114.2055206h35.9298248v-53.8947296l164.2506409,164.2506256l164.2506256-164.2506256v53.8947296h35.9298401V170.6666718H286.1553955z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'BinTray';
-->
