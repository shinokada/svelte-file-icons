<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'NXC';
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
    d="M342.3522644,55.7171783H0V459.319397h342.3522644V55.7171783z M57.6566429,95.0045319h223.6811829v147.946579H57.6566429V95.0045319z M103.8093262,367.5630798L42.2704735,330.958313l61.5388527-38.1210022V367.5630798z M203.445343,433.637207h-71.0394287v-42.7921143h71.0394287V433.637207z M203.445343,367.6874695h-71.0394287v-73.6429749h71.0394287V367.6874695z M235.1851196,367.5630798v-74.725769l61.5388489,38.1210022L235.1851196,367.5630798z M251.4496765,0h73.4283142l-0.0002441,33.590992h-73.4280701V0z M19.5100002,0h212.7445679v33.590992H19.5101738L19.5100002,0z M324.8777466,480.4455261L324.8779907,512H17.4740009l0.0002613-31.5544739H324.8777466z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'NXC';
-->
