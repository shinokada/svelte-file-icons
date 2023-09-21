<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'NSRI';
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
    d="M290.3961182,166.1473236l33.3509521,33.2597046L177.2174377,345.9177246l-75.5073547-75.6353149l33.3687592-33.3498535l42.2665863,42.266571L290.3961182,166.1473236z M357.9536438,255.9135284c0-111.3873444-121.4114685-181.3823853-218.0161285-125.6887207s-96.6046143,195.6837921,0.0000305,251.3774261S357.9536438,367.3008423,357.9536438,255.9135284z M212.6659851,512C119.5366821,466.8252869,4.5896273,395.3093567,0.0000735,304.6360779L0,79.2966385L212.666214,0l212.7719574,79.2966385v224.0440063C424.8136902,381.2536011,339.3380737,449.0762329,212.6659851,512z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.vercel.app/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'NSRI';
-->
