<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Karma';
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
    d="M208.4599152,452.6582947l-91.9375687-108.5139465l-57.5040398,54.1716614L0,180.6650391l91.9507523,108.5168152l57.4908524-54.1964569L208.4599152,452.6582947z M512,452.6582947l-139.1955872-205.660675L500.1618347,59.3417091h-124.157196l-76.0414124,112.3509064V59.3417091H186.0753937v116.5242615l74.8745575,276.7923279h39.0131531v-98.3319092l11.0513-16.2835693l76.8283997,114.6154785H512z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Karma';
-->
