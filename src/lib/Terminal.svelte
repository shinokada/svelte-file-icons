<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Terminal';
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
    d="M475.4285583,36.5714302H36.5714302C16.3714294,36.5714302,0,52.942852,0,73.1428604v365.7142944c0,20.1999817,16.3714275,36.5714111,36.5714302,36.5714111h438.8571167C495.6285706,475.4285583,512,459.0571289,512,438.8571472V73.1428604C512,52.942852,495.6285706,36.5714302,475.4285583,36.5714302z M73.1428604,292.5714417l73.1428604-73.142868l-73.1428604-73.1428528l36.5714264-36.571434l109.7142868,109.7142868L109.7142868,329.1428528L73.1428604,292.5714417z M365.7142944,329.1428528H219.4285736v-36.5714111h146.2857208V329.1428528z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Terminal';
-->
