<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Adobe Animate';
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
    fill-rule="evenodd"
    clip-rule="evenodd"
    d="M169.6582336,137.076416l27.9272766,109.3818207h-55.1563873L169.6582336,137.076416z M512,0v512H0V0H512z M271.3251343,356.5380554L195.4998627,100.538208h-52.5197449c-0.5314026,13.0491486-1.3264313,15.9639206-2.6455994,20.7126465L73.0083771,356.538208h40.4676208l19.1785431-71.6801147c0,0,74.7053986,0,74.7053986,0.0001526l19.765625,71.6799622L271.3251343,356.5380554z M433.5708923,232.4945984c0-73.4539795-63.0508728-83.0336609-142.5365295-52.738205c1.1636353,13.4981537,1.5038452,23.6472931,1.5038452,25.9745789V356.770874h43.0545349V205.2654877c34.8215942-9.685379,57.9172058-4.355835,57.2508545,30.4872131V356.538208h40.7272949V232.4945984z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Adobe Animate';
-->
