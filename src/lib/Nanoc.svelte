<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Nanoc';
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
    d="M128.6759033,356.9210205V153.8795013h90.3294373l81.536438,113.1117096V153.8795013h78.3388062v203.0415192h-89.1304321L206.742981,245.0857391l-1.3259735,111.8352814H128.6759033z M127.7110672,34.4531784c-170.2814636,98.169136-170.2814026,344.92453,0.0000687,443.0936584S512,452.3383484,512,256S297.9925232-63.7160263,127.7110672,34.4531784z M154.1500244,431.8884888c-135.1882935-77.9375-135.1882935-273.8393555-0.000061-351.776947C289.3383484,2.1739759,459.2412109,100.1248703,459.2412109,256S289.3383484,509.8260498,154.1500244,431.8884888z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Nanoc';
-->
