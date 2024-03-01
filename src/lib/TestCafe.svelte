<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'TestCafe';
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
    d="M317.8369141,313.0705261l-17.6682739,17.5464172h70.6111145l70.6101379,61.500824H70.6101151l70.6700211-61.500824h52.9428558l-17.6672516-17.5464172h-52.9428635L0,418.4668274h512L388.447052,313.0705261C388.447052,313.0705261,317.8369141,313.0705261,317.8369141,313.0705261z M477.5621338,137.4286652l-44.1392212-43.8954926l-185.4193268,184.444519l-70.6111298-70.3044739l-44.1391907,43.8954926l114.7503357,114.1999664L477.5621338,137.4286652z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'TestCafe';
-->
