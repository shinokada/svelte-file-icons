<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Adobe Illustrator';
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
    d="M172.0485687,108.0081253h53.3347931l76.6930847,256.9412842h-46.327301l-19.075943-73.1893311h-74.7465668l-19.4652405,73.1893311h-40.8770218l70.4641953-244.8728333V108.0081253z M226.161972,253.9974976l-26.4727478-108.6160889l-27.2513428,108.6160889H226.161972z M381.4946594,173.9983673H339.449707v190.9506683h42.0449524V173.9983673z M359.931366,99.8106613c-13.62146,0-24.6638489,10.9156494-24.6638489,24.3807983s11.0423889,24.3807907,24.6638489,24.3807907s24.6638184-10.9156494,24.6638184-24.3807907S373.5528259,99.8106613,359.931366,99.8106613z M512,512H0V0h512V512z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Adobe Illustrator';
-->
