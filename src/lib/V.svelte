<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'V';
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
    d="M0.590026,15.9556866l171.0894318,473.930542c4.163269,11.5325623,15.1087952,19.2181396,27.3698273,19.2181396H322.827301c6.7302856,0,12.73703-4.2227173,15.0153198-10.5556946L511.4134827,16.0675545c2.429718-6.753994-3.026001-13.7288761-10.1663818-12.9971828L363.5018921,17.1855373c-9.2899475,0.9519711-17.1871033,7.1998196-20.2509155,16.0215435l-86.4337158,248.8724823l-87.0220642-249.982666c-3.0901337-8.8768387-11.0720215-15.1372051-20.4294891-16.0232849L10.6779613,2.9409513C3.5599995,2.2669356-1.83771,9.2306757,0.590026,15.9556866z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'V';
-->
