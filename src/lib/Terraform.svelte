<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Terraform';
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
  ><g
    ><path
      d="M158.6916809,271.2892761l141.528717,80.8660583V512l-141.528717-80.8667297V271.2892761z M158.6916809,253.9532318l141.528717,80.866745V171.5395813l-141.528717-80.8664246V253.9532318z M314.2690735,171.2910461v164.8621521l142.9368591-82.1428833V89.7128601L314.2690735,171.2910461z M144.6430206,82.6460876L0,0v165.3662872l144.6430206,82.6460876V82.6460876z"
    /></g
  ></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Terraform';
-->
