<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Adobe CharacterAnimator';
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
    fill-rule="evenodd"
    clip-rule="evenodd"
    d="M0,0h512v512H0V0z M422.3441467,240.5655365v123.661972h-41.8583374v-119.437973c1.3225403-42.6277924-37.7862854-42.765976-58.7601624-24.1966553V364.227478h-41.8617859V108.0692291h41.8617859v78.7293091C352.4823303,162.8755341,423.8422241,158.5449066,422.3441467,240.5655365z M246.8363037,110.4747696v40.2666092c-59.3858795-24.7029877-116.6407928,2.8851929-116.7510529,84.4458313c1.6447754,69.5450592,38.5696106,109.9013519,114.4466095,88.1590729l0.0021667,37.5782471c-90.4340515,26.4772949-159.643219-25.1505127-158.2294464-124.5829773C86.9373245,138.2860565,155.402298,84.3326797,246.8363037,110.4747696z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Adobe CharacterAnimator';
-->
