<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'draw.io';
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
    d="M511.8693237,503.1114197h-512v-512h512V503.1114197z M296.7903442,323.2269592v73.9777832c0,15.361084,12.4526367,27.8137207,27.8137207,27.8137207h95.9251099c15.361145,0,27.8137817-12.4526367,27.8137817-27.8137207v-73.9777832c0-15.361084-12.4526367-27.8137207-27.8137817-27.8137207h-53.1613159l-56.5774536-96.362915c12.2509766-2.9089355,21.3669434-13.9136353,21.3669434-27.0544434V97.0180969c0-15.361084-12.4526367-27.8137207-27.8137207-27.8137207h-95.9251556c-15.361084,0-27.8137207,12.4526367-27.8137207,27.8137207v74.9777832c0,12.8204956,8.6769409,23.6084595,20.4765625,26.8284302l-56.7103882,96.5888672h-53.161499c-15.361145,0-27.8137817,12.4526367-27.8137817,27.8137817v73.9777832c0,15.361084,12.4526367,27.8137207,27.8137817,27.8137207h95.9251099c15.361145,0,27.8137817-12.4526367,27.8137817-27.8137207v-73.9777832c0-16.796814-8.6247253-27.8137817-35.7888794-27.8137817l56.1320801-95.6035767h43.1558685l56.1313477,95.6036377C307.2176208,293.5307922,296.0712891,311.5006104,296.7903442,323.2269592z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'draw.io';
-->
