<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Floobits';
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
    d="m436.36252 327.86642c-33.51558-19.32209-33.51558-67.88961-2e-5 -87.21171 33.51558-19.3221 75.6375 4.96166 75.6375 43.60586 0 38.64419-42.12192 62.92795-75.63748 43.60585zm-411.22584-60.8487c-33.515557-19.32209-33.515576-67.8896 0-87.2117 33.515556-19.3221 75.637484 4.96165 75.637484 43.60585s-42.121908 62.92795-75.637484 43.60585zm196.7318-119.32554h97.60893l122.07256 277.39567h-97.91948zm-146.1654-60.78003h97.586428l121.91839 277.22702h-97.83947z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Floobits';
-->
