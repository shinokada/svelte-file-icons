<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Stylus S';
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
    d="M306.5072327,119.6867371l-10.3660889-7.211235c51.8303528-59.0414085-10.3659973-101.8578568-39.6614075-57.6893997c-27.4926605,41.4642639,9.9153137,92.8439484,32.4502563,159.5472565c35.6051331,105.4634857,30.1968384,162.2514496-15.7744751,217.2366791c-115.8294678,137.9137268-332.615387,85.1820374-257.7994995-57.6894226c25.689888-49.1261597,70.3090134-84.2806091,146.4769897-75.7172852c7.2112274,9.013916-0.4506683,12.6195068-5.8590546,15.3237c-61.7456818,30.647522-97.3508148,153.6881409-43.7176971,150.9839478c25.6898041-0.9013367,63.999115-26.591217,83.8298798-70.3089294c22.9855957-50.9289246-5.4083862-114.9280396-25.6898041-175.3217316C123.0729294,76.4196167,230.3391724-46.6210022,352.9291992,17.3781185C399.3511047,41.7159119,368.7036743,126.8978806,306.5072327,119.6867371z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Stylus S';
-->
