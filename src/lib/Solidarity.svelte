<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Solidarity';
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
    d="m0.79737006 154.56931c1.436897-9.75412 18.945202-146.50804 168.94941-154.3314 79.86181-4.1651635 135.092 47.102657 159.14197 95.509285 16.31708 32.842317 15.33927 73.502087 15.33927 73.502087 2.21226 49.24086-71.39152 73.63738-91.71157 10.1663-7.08797-26.49494 1.0584-68.85056-75.66372-84.218344-19.95539-3.997142-68.9254 20.677184-73.68014 50.386724l210.9482 151.38533c35.25205 21.85642 33.56749 47.09865 28.16518 78.43513-6.50004 37.70404-62.00875 147.83397-188.13342 135.66139-126.12466-12.17255-158.503-132.78011-152.73684-174.16233 20.847437-68.6118 99.488648-36.91353 95.118476 7.80471 0.677557 85.10302 122.16601 100.43791 149.22467 24.0073l-219.1514-157.85253c-30.03699-17.98864-27.24699-46.53949-25.810093-56.29365z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Solidarity';
-->
