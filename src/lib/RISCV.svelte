<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'RISC V';
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
    d="M152.7466278,318.0548096l123.4940948,146.5792542L512,133.0466309V0.0000048L152.7466278,0C332.8632812,12.7710838,331.9365845,297.4132996,152.7466278,318.0548096z M512,259.3549805V512H331.6290894L512,259.3549805z M116.7847595,72.1479263L0,72.147934V512h217.9047241L31.4701366,286.4492798v-36.1164703l85.314621-0.0000916C243.3624878,250.3327179,243.3624878,72.1479263,116.7847595,72.1479263z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'RISC V';
-->
