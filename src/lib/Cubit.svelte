<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Cubit';
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
    d="M212.8150787,340.9492188l-65.4441528-39.4627686v-78.3090515l65.4441528,37.8841248V340.9492188z M84.1689453,171.3764801l135.459259-81.6816559l135.234375,81.5463715l75.8917542-43.9321518L219.6282043,0L8.2771864,127.4443359L84.1689453,171.3764801z M286.2614136,210.9529724l-66.6332703-40.1798553l-66.8578339,40.3152771l66.6285858,38.56987L286.2614136,210.9529724z M362.4447632,182.066803l0.0010071,157.9501343l-136.4630585,82.2871704V512L440,383.3947144V137.6026001L362.4447632,182.066803z M212.8150787,422.0275574L76.8111801,340.0169373V182.331955L0,137.8677673v245.5269165l212.8150787,128.3287048V422.0275574z M291.8853455,222.9119873l-65.9026337,38.1495361v80.1642151l65.9026337-39.7392883V222.9119873z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Cubit';
-->
