<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Puppet';
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
    d="M334.7442932,332.8193359v-154.063858H213.7462158l-60.674057-61.6928177V0H0v153.0721588h120.0060425l60.6744537,61.6921844v82.4704285l-60.6733246,61.6930542H0V512h153.0721588V394.9373474l61.0922241-62.1180115H334.7442932z M103.2373581,102.8040466h-52.082962v-52.535923h52.082962V102.8040466z M102.8040466,461.7318726H51.5877075v-51.2163391h51.2163391V461.7318726z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Puppet';
-->
