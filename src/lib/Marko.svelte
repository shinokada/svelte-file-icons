<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Marko';
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
    d="M108.713 196.446l-36.146-58.963-72.567 118.507 85.368 139.502h72.258l-85.416-139.502 36.504-59.544zM243.444 137.518l-23.578 38.513 36.138 58.959 23.557-38.473-36.117-59zM85.419 116.507l85.472 139.483h72.257l-85.507-139.483h-72.223zM328.512 116.507h-72.206l85.469 139.483-85.469 139.502h72.257l85.471-139.502-85.522-139.483zM426.53 116.507h-72.26l85.472 139.483-85.472 139.502h72.259l85.471-139.502-85.47-139.483z"
  ></path></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Marko';
-->
