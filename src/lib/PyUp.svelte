<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'PyUp';
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
    d="M0.0002805,128.0825043L0,381.8591309l89.6285324,52.5713501l0.0045547-255.1468964l132.2466736-75.7585144l63.9895935,38.2214508V36.6955566L221.7051239,0L0.0002805,128.0825043z M354.2109375,331.9945068L221.878006,405.3878479l-63.3305817-33.0310364v102.4975586L221.878006,512L443,381.8582764V126.5652237l-88.7890625-50.7358704V331.9945068z M221.8631439,328.8824463l64.0062103-36.6292725v-74.5800171l-64.345047-35.6493225l-63.6412201,36.2316742v74.1902618L221.8631439,328.8824463z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'PyUp';
-->
