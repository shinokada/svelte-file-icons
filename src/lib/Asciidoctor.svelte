<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Asciidoctor';
</script>

<svg
  xmlns="http://www.w3.org/2000/svg"
  version="1.1"
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
    d="m21.771484 336.50781c-23.150014-0.46401-23.150014 34.49951 0 34.03516h95.832036l-48.816411 117.44922c-9.028732 21.08424 22.850662 34.3407 31.431641 13.07031l54.01172-130.51953h64.09375c23.15001 0.46401 23.15001-34.49947 0-34.03516zm260.31641-336.49804c-6.29516 0.22488188-12.3448 4.0236494-14.98633 10.677734l-101.9414 245.01758h-147.79297c-23.155053-0.46938-23.155053 34.50082 0 34.03125h236.91601c23.15506 0.46934 23.15506-34.50086 0-34.03125h-52.19726l80.60547-193.88672 180.11328 439.17383c8.36655 21.57256 40.68296 8.31098 31.48828-12.92188l-195.74219-477.30078c-3.62546-7.636195-10.16773-10.984685-16.46289-10.759765z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Asciidoctor';
-->
