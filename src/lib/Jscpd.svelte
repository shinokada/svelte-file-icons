<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'jscpd';
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
    d="M68.228653,200.9017487h190.1714325v19.5047607H68.228653V200.9017487z M126.7429352,249.6636658h287.6952515v19.5047607H126.7429352V249.6636658z M141.3715057,308.1779785h224.3047638v19.5047607H141.3715057V308.1779785z M87.7334137,366.6922913h224.3047638v19.5047607H87.7334137V366.6922913z M77.9810333,425.206604h312.0761719v19.5047607H77.9810333V425.206604z M125.1729202,122.8825378L183.3279724,20.847084L162.1458282,8.7744608l-53.8357086,94.4574738L49.444046,9.8726759L28.8202381,22.8765488l63.0571442,100.0059891H0v380.3429871h512V122.8825378H125.1729202z M482.7428589,473.9683838H29.257143V152.1396942h453.4857178V473.9683838z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'jscpd';
-->
