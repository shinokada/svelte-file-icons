<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Fantom';
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
    d="M512,421.8270874l-160.3018494-5.5801392l-106.5297241,56.3085632l-40.7545776-24.8196411L73.7390213,470.866272C-7.4264803,203.0201263-32.4970398,78.2722015,54.6140404,51.2377319c79.053421-24.5338211,164.1755981-10.888485,210.8457642,41.8690872C306.2749634,139.245697,477.7237244,359.1385803,512,421.8270874z M165.9116364,252.1629333c0,0,27.8186798-95.9542847,22.677948-130.500412l-84.6926193,86.783783l-77.3735046-9.4102783l50.2265549,57.4163666l29.8957443-27.2701111L165.9116364,252.1629333z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Fantom';
-->
