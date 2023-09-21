<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'VSTS';
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
    d="m68.461278 273.01837-38.625427-8.00244v-83.31877l27.711258-35.41146 104.67071-39.31819v-32.588401l82.55729 66.837281-176.31383 36.38559zm176.31383-131.80198 76.84585-13.06229 1.53623 175.13045-69.64252 59.28303-112.14493-37.53913v37.14497l-72.908464-89.15504 177.37224 24.63332zm-244.77511 240.42998 387.43989 57.93495-2.89676-439.58132 127.45687 55.76236v401.92361l-126.7327 54.31403z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.vercel.app/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'VSTS';
-->
