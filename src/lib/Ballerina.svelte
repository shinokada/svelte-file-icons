<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Ballerina';
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
    d="M 162.00687,250.66559 V 320.2507 L 220.49929,512 H 282.3309 V 296.68005 Z m 120.32403,-61.97634 -82.36288,31.4999 82.36288,31.48956 z m 0,-44.99099 V 0 H 162.00687 V 189.72305 Z M 120.31369,250.66559 V 320.2507 L 61.810928,512 H 0 V 296.68005 Z M 0,188.68925 82.342204,220.18915 0,251.67871 Z M 0,143.69826 V 0 h 120.31369 v 189.72305 z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Ballerina';
-->
