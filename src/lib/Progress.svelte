<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Progress';
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
    d="m120.23678 481.19554v-138.12325l-120.23678 69.55848zm128.18632-478.95972c-4.96847-2.9810945-12.91801-2.9810945-17.88647 0l-124.21154 71.545831 239.47986 138.12325v277.24017l124.21153-71.54583c4.96848-2.98109 8.94324-9.93695 8.94324-15.8991v-266.30955zm-137.12955 146.07277-111.29355 63.59631 172.90248 100.36293v199.73217l111.29354-63.5963c4.96846-2.98109 8.94323-9.93695 8.94323-15.8991v-189.79523l-163.95924-94.40078c-4.96846-2.98108-12.918-2.98108-17.88646 0z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Progress';
-->
