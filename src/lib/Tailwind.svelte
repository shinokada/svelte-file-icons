<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Tailwind';
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
    d="M128,204.6666718C145.0624084,136.2265015,187.7375946,102,256,102c102.3999939,0,115.2000122,77,166.3999939,89.8333282c34.1376038,8.5598297,64-4.2734985,89.6000061-38.5C494.9375916,221.7734985,452.2623901,256,384,256c-102.3999939,0-115.2000122-77-166.3999939-89.8333282C183.4624023,157.606842,153.6000061,170.4401703,128,204.6666718z M0,358.6666565C17.0623989,290.2265015,59.7375984,256,128,256c102.3999939,0,115.1999969,77,166.3999939,89.8333435c34.1376038,8.5598145,64-4.2734985,89.6000061-38.5C366.9375916,375.7734985,324.2623901,410,256,410c-102.3999939,0-115.1999969-77-166.3999939-89.8333435C55.4624023,311.606842,25.6000004,324.440155,0,358.6666565z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Tailwind';
-->
