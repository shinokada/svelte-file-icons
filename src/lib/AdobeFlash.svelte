<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Adobe Flash';
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
    d="M0,0v512h512V0H0z M263.6459656,217.2435913v42.637085h-88.5538788v102.7662354H123.708931V105.7313004h145.4033203l5.4662781,43.7303085h-99.4864349v67.7819824H263.6459656z M390.4790955,360.6589966c-38.3331299,15.1530457-68.0290527,3.0374451-68.8752747-40.6927795V105.7313004h51.3830872v209.963623c-0.7228088,12.1758118,3.2235718,14.0593567,17.4921875,12.5088806V360.6589966z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Adobe Flash';
-->
