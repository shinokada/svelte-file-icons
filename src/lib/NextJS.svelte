<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'NextJS';
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
    d="M386.3985596,35.5079727C217.0600281-64.0607605,1.8845311,57.5499001,0.012267,253.8817902c-1.8282685,191.716507,201.0625916,315.5454712,370.0206604,231.1632233L185.5603943,213.6362915l0.0000305,167.9969177c0,18.6138916-35.6191101,18.6138916-35.6191101,0V156.4207916c0-14.7758484,27.4472504-15.9884033,35.2252045-3.1443481l210.2631683,317.2959595C553.3806763,368.835144,551.2467041,132.4364166,386.3985596,35.5079727z M362.6429443,353.4465332l-35.7316284-54.5765381V149.4583282c0-13.9324646,35.7316284-13.9324646,35.7316284,0V353.4465332z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'NextJS';
-->
