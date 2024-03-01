<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Elm';
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
    d="M256,241.6326599l110.3673401-110.3673553H144.979599L256,241.6326599z M13.7142859,0l111.6734695,111.0204086h242.2857056L256,0H13.7142859z M391.1836853,134.5306091l120.1632385,120.81633l-120.8163147,120.81633L269.7142944,256L391.1836853,134.5306091z M512,227.2653046V0H284.0816345L512,227.2653046z M241.6326599,256L0,13.7142859v483.9183655L241.6326599,256z M404.2449036,390.5306091L512,497.6326599V282.7755127L404.2449036,390.5306091z M256,269.7142944L13.7142859,512h483.9183655L256,269.7142944z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Elm';
-->
