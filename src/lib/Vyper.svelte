<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Vyper';
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
    d="M313,134l-25-45h-64l-25.65,45L256,234L313,134z M384,256l-64-111l-57,100l64,110L384,256z M192,145l-64,111l57.65,99.85L249,245L192,145z M256,256l-64,111l64,111l64-111L256,256z M128,34H0l64,111L128,34z M448,145.15L512,34H384L448,145.15z M70,156l52,90l64-112l-52-90L70,156z M378,44l-52,90l63.77,112l52.45-90.85L378,44z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Vyper';
-->
