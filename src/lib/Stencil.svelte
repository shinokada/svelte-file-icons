<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Stencil';
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
    d="M373.9510498,348.4335022c0,0,16.8380737-36.2610474-4.1607666-112.2711334C346.5074463,151.9015045,257.5103149,98.9529648,257.5103149,98.9529648c70.1849365,107.8624191,39.2444458,174.2849121,33.2599487,187.12146C276.2340088,286.9242859,95.3537598,132.230545,95.3537598,132.230545s83.7828369,117.2817993,120.5750122,145.5222321c2.8152466,2.142395-117.7598267-82.2247467-166.3085327-124.7358551c64.3598022,103.2589874,182.9518433,199.5774078,182.9518433,199.5774078s-12.9251099,19.8656616-74.8415527,24.9471436S46.0968018,349.3010559,8.0474854,327.6471252c78.4180298,112.5544434,171.5317383,123.585022,216.2205811,124.7358398c77.6035767,1.9830322,92.4054565-39.1647339,133.0574951-33.2687988C401.6957397,425.5413513,405,457.6848755,405,457.6848755V512H0V2h286l119,119v286.7071838C397.401886,383.5706787,387.7221069,364.1776123,373.9510498,348.4335022z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Stencil';
-->
