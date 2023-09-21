<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Stata';
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
  ><style type="text/css">
    .st0 {
      fill-rule: evenodd;
      clip-rule: evenodd;
    }
  </style><path
    class="st0"
    d="M149.2752075,512H0V362.7247925h149.2752075V512z M149.2752075,181.3623962H0v149.2752075h149.2752075V181.3623962z M330.6376038,362.7247925H181.3623962V512h149.2752075V362.7247925z M330.6376038,181.3623962H181.3623962v149.2752075h149.2752075V181.3623962z M330.6376038,0H181.3623962v149.2752075h149.2752075V0z M512,0H362.7247925v149.2752075H512V0z M512,181.3623962H362.7247925v149.2752075H512V181.3623962z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.vercel.app/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Stata';
-->
