<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Telegram';
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
    d="M470.4354553,45.4225006L16.8273029,221.2490387c-18.253809,8.1874695-24.4278889,24.5854034-4.4127407,33.4840851l116.3710175,37.1726685l281.3674316-174.789505c15.3625488-10.9733887,31.0910339-8.0470886,17.5573425,4.023468L186.0532227,341.074646l-7.5913849,93.0762329c7.0313721,14.3716125,19.9055786,14.4378967,28.1172485,7.2952881l66.8582916-63.5891418l114.5050659,86.1867065c26.5942688,15.8265076,41.0652466,5.6130371,46.7870789-23.3935242L509.835083,83.1804428C517.6329956,47.474514,504.3345032,31.7425518,470.4354553,45.4225006z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Telegram';
-->
