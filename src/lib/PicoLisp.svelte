<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'PicoLisp';
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
    d="M196.1356506,19.3082409l88.5965271,149.3199768l-68.6871948,118.4605255h-88.5965195l68.6871872-118.4605255l-45.7914581-77.6463928L196.1356506,19.3082409z M87.9532776,492.6917725l42.3570862-70.9228516h136.9334106l-44.2982635-77.2229919H87.0075684L0,492.6917725H87.9532776z M463.0460205,345.122345h-69.0927124l-68.4667053-116.5970154l-44.2982788,75.7314148l67.9689941,117.5121765H512L463.0460205,345.122345z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'PicoLisp';
-->
