<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'ABAP';
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
    d="M121.636795,386.0886536l-79.1062851,97.6713257l-19.7093201,0.5470581V12.1759272L437.7657471,0v7.3051596l-56.9509583,59.5544052L121.636795,75.6765594V386.0886536z M489.1788025,73.6247253l-0.9457703,386.0238037L160.5550842,512V86.948616L489.1788025,73.6247253z M289.2519531,243.6892853c13.0050354,6.2984924,28.4841309,9.988739,45.9954834,7.3773651c20.3821411-3.0395203,34.73703-9.5676727,44.7911987-16.6652679l-43.3600464-124.2556686L289.2519531,243.6892853z M440.29245,407.0685425l-44.7619934-128.2732544c-38.1378784,17.2335815-82.6759033,23.3279114-123.360321,12.9928589l-53.0234222,149.3027039c0,0,21.6507263,38.6617432,115.9854889,18.5576782S440.29245,407.0685425,440.29245,407.0685425z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'ABAP';
-->
