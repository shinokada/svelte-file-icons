<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'VirtualBox Alt';
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
    d="M0,0v512h511.3082886V0H0z M471.1773376,40.1309395v252.6877594h-58.5138245L338.2658081,69.6661148l-54.0709534,147.9116516L233.2741547,70.41465l-65.7006989,239.9587402l-41.128334-131.311264H40.1309395V40.1309395H471.1773376z M40.1309395,471.8690491V219.1930542h56.8299599l73.1978226,233.7000122l67.5844421-246.8366241l45.4144592,131.2459564l53.3655396-145.9815369l47.217865,141.6287842h87.4363098v138.9194031H40.1309395z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'VirtualBox Alt';
-->
