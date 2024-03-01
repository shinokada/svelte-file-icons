<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Snowpack';
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
    d="M486.0567627,460.9002075H26.014658c-19.6137371,0-33.1243324-21.7745361-22.0020142-40.0036621l230.483551-358.0695496c8.4549561-13.5946617,30.8037262-17.5531158,43.071579,0l230.3977356,358.3965149C519.0916138,437.8883057,505.7111511,460.9002075,486.0567627,460.9002075z M155.026474,282.8839111l38.003479,38.003479l63.0057526-64.0058594h86.0078735l-86.0078735-132.2647705L155.026474,282.8839111z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Snowpack';
-->
