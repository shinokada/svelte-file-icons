<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'RAML';
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
    d="M277.512 2.33h-277.512l27.671 44.416h248.273c30.323 0 58.874 12.168 80.394 34.261 21.434 22.005 33.239 51.025 33.239 81.714 0 30.155-11.294 57.31-32.658 78.529-20.346 20.209-48.704 33.495-79.894 37.446h-30.387l-83.803-0.67 24.189 41.887h36.739l1.993 3.199h0.292l108.698 183.519 0.697 0.697c4.716 4.71 10.623 7.002 18.062 7.002 12.729 0 23.483-11.114 23.483-24.267 0-5.218-1.702-7.581-3.759-9.923-0.837-0.952-1.877-2.137-3.45-4.816l-89.44-152.235c41.586-0.721 80.474-17.293 109.769-46.848 29.944-30.209 46.435-70.525 46.435-113.519 0-88.441-71.341-160.391-159.031-160.391z"
  ></path></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'RAML';
-->
