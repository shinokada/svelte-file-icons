<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Adobe Fuse';
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
    fill-rule="evenodd"
    clip-rule="evenodd"
    d="M0,0h512v512H0V0z M121.2110291,363.6683655V107.6376266h133.2614746l4.5238037,38.0018692h-95.9452972v72.9319611h85.5992737v37.6178741h-85.5992737v107.4790344H121.2110291z M283.7909241,356.1983643v-40.7115784c34.3621216,22.453064,76.6339111,20.0118103,75.6202393-2.486908c-1.0374451-30.9920654-75.2649231-27.5978394-75.6195068-86.7512817c1.1931152-47.2038574,50.5903931-67.0870361,107.8633118-47.62117v39.7812653c-22.2347717-13.22789-67.1233826-19.943924-68.3263245,5.1528931c-0.4597168,28.9250793,78.4681091,28.4503326,76.770752,86.3670349C401.0263367,361.0672607,341.4089661,381.881958,283.7909241,356.1983643z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Adobe Fuse';
-->
