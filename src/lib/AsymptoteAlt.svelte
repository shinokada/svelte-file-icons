<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Asymptote Alt';
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
    d="m267.9051 474.84521v-165.46608l151.21083 6e-3c-96.52448 24.14779-126.96874 108.88968-151.21083 165.46008zm-12.85919-242.89022h-64.84672c35.94555-42.88106 54.01759-97.80161 64.84672-149.49455zm0 64.56495h-162.14241c38.904193-12.3661 68.650683-32.88445 91.602553-58.16097h70.54626zm12.85919 7e-3v-292.67497c-0.0904-8.69356-11.92777-7.54406-12.79515-0.89656-16.15084 115.98891-40.55642 291.2659-248.29518 293.55852-9.1154453 0.39295-8.3706456 12.7557 0.06404 12.8528h248.1607v192.98358c0.37111 7.65089 8.35867 10.40779 12.25081 2.76012 34.72239-73.29357 73.11593-179.34821 202.58849-195.7313 10.04407-1.28968 6.68342-13.47561-0.1537-12.85213z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Asymptote Alt';
-->
