<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'VSCode';
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
    d="M383.9980469,439.7380981V0L512,53.2470016v405.5039978L384,512L0,382.7071533L383.9980469,439.7380981z M61.1800957,299.7474365l-29.1800652-9.7457275l72.036438-71.2074127l-72.0344696-71.2073822l29.1780968-9.7437592l70.8096008,53.3208618L249.5921631,74.9144058l70.4058838,29.9284134v227.8951569l-70.4098511,29.9283447L131.985733,246.4226379L61.1800957,299.7474365z M168.682373,218.7923584l80.90979,60.928009V157.8643341L168.682373,218.7923584z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'VSCode';
-->
