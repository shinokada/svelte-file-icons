<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'AdonisJS';
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
    d="M0,256c0,206.4664612,49.5335579,256,256,256s256-49.5335388,256-256s-49.5335388-256-256-256S0,49.5335579,0,256z M173.6260529,416.5818176c-58.9904938,0.2783203-91.979187-54.3060913-70.3928299-107.4136963l80.305275-182.4754028c19.7302399-56.1012955,111.5418549-71.3578262,144.9373627,0l80.2909241,182.4754028c21.715271,52.4779053-11.1589355,108.0552673-70.3927917,107.4136963c-19.5915222,1.3680725-58.4139709-17.5663757-82.4339142-16.0679626C223.4291534,400.1506042,201.2708588,417.4050293,173.6260529,416.5818176z M334.2078552,337.856781L256,158.498764l-79.2565765,179.358017C224.2752686,316.8712463,284.7437744,315.6049805,334.2078552,337.856781z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'AdonisJS';
-->
