<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'PureBasic';
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
  ><polygon
    points="222.0854645,0 472.615387,15.3162394 368.6837463,142.222229 344.615387,146.5982971 295.384613,200.2051239 392.7521362,220.6267853 312.8888855,312.8888855 296.4786377,319.4530029 215.1566925,298.6666565 173.9487152,341.3333435 435.4187927,417.9145203 341.3333435,505.4358826 322.7350464,512 39.3846169,403.6923218 136.3196716,275.1905518 84.1457443,261.9523926 142.222229,178.3247833 158.6428375,175.5149994 207.8632507,183.7948761 249.4358978,126.905983 146.5982971,112.6837616 "
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.vercel.app/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'PureBasic';
-->
