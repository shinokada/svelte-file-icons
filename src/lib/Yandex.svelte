<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Yandex';
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
    d="M200.0102997,319.4423828V512H256V0h-83.6307526C90.1872635,0,21.0913162,55.5112686,21.0913162,163.6766815c0,77.1685486,30.5520782,119.0008392,76.3734512,142.0731964L0,512h64.7294235l88.7317429-192.5576172H200.0102997zM199.8350983,274.5239563h-29.8108521c-48.7323685,0-88.7452393-26.6842041-88.7452393-109.6208801c0-85.8072815,43.6381073-116.4402008,88.7452087-116.4402008h29.8108521C199.8350677,48.4628792,199.8350677,274.5239563,199.8350983,274.5239563z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Yandex';
-->
