<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Test Ruby';
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
    d="M452.03302,334.6002197l-99.9449768,99.9449463V294.6222229h59.96698L452.03302,334.6002197z M512,334.6002197L352.0880432,494.512146L192.1761017,334.6002197l79.9559784-79.9559784h159.9119568L512,334.6002197z M352.0880432,464.528656L482.01651,334.6002197l-59.96698-59.96698H282.1265869l-59.9669952,59.96698L352.0880432,464.528656z M267.5789795,225.1711426h31.9750977l-23.8644409-37.418335V61.9752808h26.0755005c19.5045166,0,19.5045166-27.5949097,0-27.5949097H111.835083c-19.5045166,0-19.5045166,27.5949097-0.0004883,27.5949097h26.0749512v125.7775269L5.7651367,406.8973999c-12.4072876,21.1151123-4.6187134,34.3093262,21.729248,34.3093262h155.9700928v-27.5949097H33.9144897l131.9580688-218.8084717V61.9752808h81.8540649v132.828064L267.5789795,225.1711426z M207.9739532,385.9086609l-50.1534576-51.7290649l84.4147034-89.7550354h-72.7205505L84.6912231,385.9066772L207.9739532,385.9086609z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Test Ruby';
-->
