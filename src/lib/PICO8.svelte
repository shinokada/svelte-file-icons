<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'PICO 8';
</script>

<svg
  version="1.1"
  width={size}
  height={size}
  xmlns="http://www.w3.org/2000/svg"
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
    d="m204.2871094 0v101.8828125l-102.1425781 0.26171875-0.26171875 102.1425781h-101.8828125v103.4257812h101.8886719v102.3984375h102.3984375v101.8886719h103.4257812v-101.8886719h102.3984375v-102.3984375h101.8886719v-103.4257812h-101.8886719v-102.3984375h-102.3984375v-101.8886719h-103.4257812zm1.025390625 102.9121094h101.375v102.4003906h102.4003906v101.3710938l-102.1445312 0.259765625-0.259765625 102.1445312h-101.3710938v-102.4003906h-102.4003906v-101.375h102.4003906v-102.4003906z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'PICO 8';
-->
