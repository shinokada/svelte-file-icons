<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Gatsby';
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
    d="M127.7110596,34.453125c-170.2814331,98.1691895-170.2813721,344.9245605,0.000061,443.093689S512,452.3383179,512,256S297.9924927-63.7160034,127.7110596,34.453125z M54.8571167,259.6571045l199.3143311,197.4857178C148.6409912,454.9742432,57.5689087,374.6345825,54.8571167,259.6571045z M299.8856812,451.6571045L60.3428345,212.1142578c31.0595703-150.8513184,240.9196167-226.013916,358.4000244-74.9714355L391.31427,160.9143066C309.6345215,53.6350708,150.006958,74.472229,100.5714111,201.1428223l210.2857056,210.2857056c53.0285645-18.2857056,93.2572021-64,106.0571289-118.8571167h-87.7713623V256h128C457.1428833,351.0856934,389.4857178,431.5428467,299.8856812,451.6571045z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.vercel.app/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Gatsby';
-->
