<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Red';
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
    d="M256,142.4808044l71.3696899-36.9777756L256,0l-71.3696899,105.5030289L256,142.4808044z M256,512l256-133.1717224l-71.3697205-105.5030212L256,369.519165L71.3696976,273.3252563L0,378.8282776L256,512z M256,327.3696899l163.684845-85.3333282L348.315155,136.5333252L256,184.6303101l-92.3151398-48.0969849L92.315155,242.0363617L256,327.3696899z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Red';
-->
