<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'DevContainer';
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
    d="M127.711113,477.5468445c-170.2814331-98.1691284-170.2814941-344.92453-0.000061-443.093689S512,59.6616783,512,256S297.9925537,575.7160034,127.711113,477.5468445z M251.4306641,289.3330078l-89.8833008-89.8837891l-28.2841797,28.2841797l61.5991211,61.5996094l-61.5991211,61.5986328l28.2841797,28.2851562L251.4306641,289.3330078z M383.3583984,284.4443359l-61.5996094-61.6000977l61.5996094-61.5991211l-28.2851562-28.2841797l-89.8828125,89.8833008l89.8828125,89.8842773L383.3583984,284.4443359z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'DevContainer';
-->
