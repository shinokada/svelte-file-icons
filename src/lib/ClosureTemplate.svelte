<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'ClosureTemplate';
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
    d="M113.3435593,227.3534393v-114.754509h113.9480209C219.1393738-7.4456387,91.3643646-24.972641,35.1795197,29.8501492C-23.9558468,87.5519333-15.2867308,217.1245422,113.3435593,227.3534393z M476.8204956,29.8501492C420.6356201-24.972641,292.8606262-7.4456387,284.7084351,112.5989304h113.947998v114.754509C527.2867432,217.1245422,535.9558716,87.5519333,476.8204956,29.8501492z M35.1795197,482.1498413c56.184845,54.8228149,183.9598541,37.2957764,192.1120605-82.7487793H113.3435593V284.6465454C-15.2867308,294.8754578-23.9558468,424.4480591,35.1795197,482.1498413z M398.6564331,284.6465454V399.401062h-113.947998c8.1521912,120.0445557,135.9271851,137.5715942,192.1120605,82.7487793C535.9558716,424.4480591,527.2867432,294.8754578,398.6564331,284.6465454z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'ClosureTemplate';
-->
