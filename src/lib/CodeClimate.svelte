<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Code Climate';
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
    d="M342.7659912,113.3599243l-97.7796478,97.2423859l58.0230865,58.0230865l39.7565613-39.7565613l111.7481384,112.2854309L512,283.1311646L342.7659912,113.3599243z M169.7712402,170.8457489L0,340.6170044l58.0230827,58.0230713l111.7481537-111.7481689l111.7481689,111.7481689l58.0230713-58.0230713L169.7712402,170.8457489z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Code Climate';
-->
