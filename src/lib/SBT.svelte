<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'SBT';
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
    d="M162.8179321,317.7835083h341.7998657c2.949646-12.0095215,5.0310974-24.4336243,6.221344-37.2056274H224.2586212c-39.1430054,0-39.1430054-59.3927612,0-59.3927612h285.4353027c-1.7260437-12.9264069-4.4123535-25.4534149-7.9500732-37.5470886H285.6993103c-40.2363892,0-40.2363892-59.3927536,0-59.3927536h189.8917236C407.2690125,11.6708832,255.2333374-39.0648956,127.712532,34.4521828c-170.283371,98.1702728-170.283371,344.9284668,0,443.0987244c131.4454346,75.7796021,288.918457,19.5275269,353.9256592-100.3746643H162.8179321C123.4853516,377.176239,123.4853516,317.7835083,162.8179321,317.7835083z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'SBT';
-->
