<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Max';
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
    d="M256,0C114.6151123,0,0,114.6151123,0,256s114.6151123,256,256,256s256-114.6151123,256-256S397.3848877,0,256,0z M342.8681641,156.7749023l-74.7978516,52.0126953l-21.6948242-31.1982422l74.7973633-52.0126953L342.8681641,156.7749023z M80.8198242,180.0927734l74.7973633-52.012207l21.6943359,31.1982422l-74.7973633,52.012207L80.8198242,180.0927734z M164.0673828,179.4667969l74.7973633-52.012207l21.6948242,31.1982422l-74.7978516,52.012207L164.0673828,179.4667969z M264.0703125,449.7880859l-21.6948242-31.1992188l74.7973633-52.0126953l21.6953125,31.1992188L264.0703125,449.7880859z M292.7373047,369.7880859l-21.6953125-31.1992188l74.796875-52.0126953l21.6953125,31.1992188L292.7373047,369.7880859z M321.7373047,289.4541016l-21.6953125-31.1992188l74.796875-52.0117188l21.6953125,31.1982422L321.7373047,289.4541016z M351.7373047,208.7875977l-21.6953125-31.1982422l74.796875-52.0126953l21.6953125,31.1982422L351.7373047,208.7875977z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Max';
-->
