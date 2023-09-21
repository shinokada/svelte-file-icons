<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Adobe InCopy';
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
    d="M0,0v512h512V0H0z M198.9818115,364.2181396h-41.8909302v-256h41.8909302V364.2181396z M370.9703979,214.0447998c-39.1033325-15.2937622-80.4985962-0.4327393-80.7594604,54.871582c0.0089111,51.5635376,36.0713501,70.489563,80.7594604,55.4840088v37.2696533c-56.6846924,18.289917-123.1031494-5.7803955-123.3485718-92.7536621c0.218811-74.0864868,58.0695801-110.6791992,123.3485718-93.3091431V214.0447998z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.vercel.app/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Adobe InCopy';
-->
