<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'NetLinx';
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
    d="M453.6758118,283.2871704L374.0943298,78.4428101H237.6788635L0,433.3889465C95.3836288,382.6817017,239.4138489,326.8780518,453.6758118,283.2871704z M289.0527649,198.7006226c4.0805664,11.5569458,27.0144348,76.6678162,30.9556885,87.819519c-9.6301575,0-74.1205139,0-86.9284821,0C234.453125,284.3518677,282.2964478,209.2887573,289.0527649,198.7006226z M372.1051331,433.5571899c0,0-24.2247009-68.468689-30.592041-86.4761963c39.5465088-8.5175476,81.9958191-16.6687317,127.513092-24.2988892L512,433.5560303L372.1051331,433.5571899z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'NetLinx';
-->
