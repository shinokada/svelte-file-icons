<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'HashiCorp';
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
  ><g
    ><polygon
      points="305.777771,379.7333374 382.5777588,337.0666809 382.5777588,45.5111122 305.777771,0 305.777771,217.6000061 207.644455,217.6000061 207.644455,132.2666626 129.422226,174.9333344 129.422226,466.4888916 207.644455,512 207.644455,294.4000244 305.777771,294.4000244 "
    /><polygon
      points="419.555542,65.4222183 419.555542,361.2444458 305.777771,423.8222046 305.777771,512 490.6666565,405.3333435 490.6666565,106.6666641 "
    /><polygon
      points="207.644455,0 21.333334,106.6666641 21.333334,405.3333435 93.8666687,446.5777588 93.8666687,150.7555542 207.644455,88.1777725 "
    /></g
  ></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'HashiCorp';
-->
