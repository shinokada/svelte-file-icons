<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'E';
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
    d="M53.9617081,65.5902481v370.9287109c0,62.742218-40.939743,76.3560486-40.939743,76.3560486h392.4346619V387.9825439c0,25.7961121-36.2249146,60.728363-68.0693359,60.728363c-21.3086548,0-76.9479675,0-151.5283203,0c-30.3806763,0-33.1468353-27.581543-33.1468353-27.581543V288.5420837h118.381485c36.2471313,0,37.8820801,30.7791748,37.8820801,30.7791748V211.594101c0,0-8.6374207,13.0219727-36.1463013,13.0219727H152.7121429V65.5902481h149.1606903c71.8822021,0,71.0289001,56.7855377,71.0289001,56.7855377V0.8750273H0C0,0.8750273,53.9617081,5.2156825,53.9617081,65.5902481z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'E';
-->
