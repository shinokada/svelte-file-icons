<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Alacritty Alt';
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
    d="M475.4285889,36.5714417H36.5714111C16.37146,36.5714417,0,52.9429016,0,73.1429138v365.7142334c0,20.2000122,16.3713989,36.5714111,36.5714111,36.5714111h438.8571777C495.6286011,475.4285583,512,459.0571594,512,438.8571472V73.1429138C512,52.9429016,495.6286011,36.5714417,475.4285889,36.5714417z M288.2272949,324.6959229L256,444.9072571l-32.7523804-120.2113342L256,245.9757538L288.2272949,324.6959229z M353.9147949,386.2397156L256,156.0911865l-97.9147949,230.1485291H107.169487L228.5839081,84.9072647h54.8322601l121.4143372,301.3324585H353.9147949z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Alacritty Alt';
-->
