<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'HIE';
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
    d="M0,386.7279358L87.1529541,256L0,125.2720718h65.3639603L152.516922,256L65.3639603,386.7279358H0z M87.1529541,386.7279358L174.3059082,256L87.1529541,125.2720718h65.3639679l174.3029022,261.4558716h-65.3639832l-54.4679565-81.7034607l-54.4709625,81.7034607H87.1529541z M482.9480286,255.9884949L512,212.4135284l-145.2539062-0.0030823v43.578064L482.9480286,255.9884949z M424.8470154,321.3524475l29.0489807-43.5749512l-87.1499023-0.0030823v43.5779724L424.8470154,321.3524475z M453.8959961,386.7163391l29.0519714-43.5749817l-116.2019043-0.0030518v43.5779724L453.8959961,386.7163391z M305.0321045,321.3644714l43.5749817,65.3634644l0.0030518-174.3178711l-43.5778503-0.0007629L305.0321045,321.3644714z M348.610321,194.2717285l0.0007019-43.5749817l-43.5788269-0.003067v43.5779724L348.610321,194.2717285z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'HIE';
-->
