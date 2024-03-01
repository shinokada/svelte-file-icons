<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'PNPM';
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
    d="M502,10v140H362V10H502 M326,10v140H186V10H326 M150,10v140H10V10H150 M502,186v140H362V186H502 M512,0H352v160h160V0L512,0z M336,0H176v160h160V0L336,0z M160,0H0v160h160V0L160,0z M512,176H352v160h160V176L512,176z M336,336H176V176h160V336z M336,352H176v160h160V352z M512,352H352v160h160V352z M160,352H0v160h160V352z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'PNPM';
-->
