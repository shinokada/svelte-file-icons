<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Thor';
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
  ><polygon
    points="205.6878662,188.670517 0,185.7109833 308.5317993,281.8959656 276.7167664,210.1271667 335.1676331,212.346817 312.2312012,435.7919006 480.9248657,435.7919006 490.5433655,347.7456665 435.7919006,347.7456665 449.1098328,217.5260162 503.8612671,217.5260162 512,129.4797668 457.2485657,129.4797668 462.4277344,76.2080917 347.7456665,76.2080917 341.8265991,131.6994171 183.491333,131.6994171 "
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Thor';
-->
