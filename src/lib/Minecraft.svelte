<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Minecraft';
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
  ><rect width={size} height={size} /><rect x="340.7752991" width={size} height={size} /><polygon
    points="340.7752991,172.5020294 169.8474426,172.5020294 169.8474426,258.4169006 84.78479,258.4169006 84.78479,512 169.8474426,512 169.8474426,425.3323364 340.7752991,425.3323364 340.7752991,512 426.6405334,512 426.6405334,258.4169006 340.7752991,258.4169006 "
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Minecraft';
-->
