<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Nextflow';
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
    d="M512.000061,129.9600372V34.2549477C417.630249,54.7068138,346.3874512,97.8304825,257.5635376,183.141922C125.9597855,29.3031654,15.2641125,20.5713539,0,20.1199589v97.2617569c6.3763809,0.7873459,86.8484421,12.9810028,189.6638336,136.717041C132.6321411,307.1972961,67.7304611,347.638092,0,372.6486816v101.4573059c96.3398056-28.4666443,180.0973663-79.5985718,249.3567047-142.2271729c67.6676788,87.4675598,168.7005768,141.3909607,262.6433716,160.0012207V391.5838623c-57.1178589-14.526886-130.7965088-49.2848816-194.3545532-130.5957947C389.3026733,181.8498993,443.7009583,145.9455109,512.000061,129.9600372z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Nextflow';
-->
