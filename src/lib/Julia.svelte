<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Julia';
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
    d="M198.1847992,235.3032074c-76.7397232-44.2413025-76.7397385-155.4450989-0.0000153-199.6864014s173.1852112,11.3605728,173.1852112,99.8432007S274.92453,279.5444946,198.1847992,235.3032074z M230.7400055,376.5400085c0-88.4826355-96.4454956-144.0845184-173.1852264-99.8432007s-76.7397003,155.4450989,0.0000267,199.6864014S230.7400055,465.022644,230.7400055,376.5400085z M512,376.5400085c0-88.4826355-96.4454956-144.0845184-173.1852112-99.8432007s-76.7397156,155.4450989,0.0000305,199.6864014S512,465.022644,512,376.5400085z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Julia';
-->
