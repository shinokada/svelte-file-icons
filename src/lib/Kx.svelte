<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Kx';
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
    d="M512,435.3502808L408.4644775,292.0704346l89.842041-125.2445984h-95.5198669l-42.6340637,70.5331421l-43.5342407-70.5331421H156.9731293l-74.8127289,96.3623352V76.6496048H0v358.7006836h82.1604004V306.7951965l76.1487732,128.5550842h147.955719l53.9652405-83.506897l54.9141541,83.506897H512z M230.4500732,404.9576111l-78.1526337-119.9007874l82.8284454-97.8578796L310.9406433,292.40448L230.4500732,404.9576111z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Kx';
-->
