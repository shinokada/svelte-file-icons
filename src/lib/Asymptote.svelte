<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Asymptote';
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
    d="m376.59493 345.73585c37.21562-40.70716 63.48446-88.78223 84.13449-138.70358v138.70358zm86.58654-332.77362c-23.37256 97.455867-51.86726 237.00754-151.62975 326.09192-106.69589 95.27564-287.55505 118.34529-299.89558 124.79418-23.450343 17.97567-8.276824 50.99319 16.893493 47.95575 142.27714-29.12024 229.65118-65.35172 292.85258-115.32516h139.32721v91.26265c-0.70005 14.40648 12.40556 22.58696 24.70444 23.42264 12.77824 0.86825 25.96908-7.94217 26.56614-21.84937v-465.60757c-0.53824-24.86766-34.75846-32.92564-48.81853-10.74504z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Asymptote';
-->
