<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'MDX';
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
    d="m21.412109 150.62109c-11.757433 0-21.412109 9.65468-21.412109 21.41211v172.55469c0 11.75743 9.6546757 21.41211 21.412109 21.41211h469.17578c11.75743 0 21.41207-9.65468 21.41211-21.41211v-172.55469c0-11.75743-9.65468-21.41211-21.41211-21.41211h-469.17578zm329.1543 40.76563 45.4414 45.44336 45.44336-45.44336 15.89649 15.89844-45.44141 45.44336 44.35937 44.36132-15.89453 15.89649-44.36132-44.36133-44.36329 44.36133-15.89648-15.89649 44.36133-44.36132-45.44336-45.44336 15.89844-15.89844zm-103.15821 1.39453h22.71289v84.98047l31.06055-30.21875 15.67774 16.11523-58.29297 56.71094-55.36524-56.63672 16.07813-15.7168 28.1289 28.7754v-84.00977zm-196.90039 3.00781 60.624998 59.8711 61.75196-59.35352v118.39453h-23.07813v-64.20312l-38.89258 37.38086-37.328122-36.86524v63.6875h-23.078126v-118.91211z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'MDX';
-->
