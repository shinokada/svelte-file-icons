<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Dyalog';
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
    d="M0.713 0v136.303h75.483v-60.877h116.99c63.329 0 115.82 19.655 151.877 56.74 31.551 32.606 48.924 76.51 48.924 123.779 0 86.979-62.817 180.559-200.802 180.559h-193.185v75.496h193.185c181.346 0 276.199-128.774 276.199-256.056 0-66.924-24.933-129.598-70.234-176.268-50.578-52.119-121.839-79.676-205.964-79.676z"
  ></path></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Dyalog';
-->
