<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Glade';
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
      fill: #181816;
    }
  </style><path
    class="st0"
    d="M396.5218811,381.8900146H174.0741272l222.4477539-135.0803223V381.8900146z M64.7104187,94.3350143C82.6800461,75.7494507,124.7225266,45.238945,169.6464386,45.238945c-34.2792053,7.5792351-54.2272415,23.959404-54.2272415,101.0472183c0,2.1835327-1.7125244,4.1199951-3.8114319,3.9419556c-36.2279129-3.0738831-83.505249,11.3762665-97.6975937,56.0864716C15.0349798,158.0806885,46.7409401,112.920723,64.7104187,94.3350143z M0,456.3410034v27.9555969h512V27.7031994l-348.2717896,0.0002003c-37.320015,0-84.2485123,17.0151062-115.7546844,50.5877304C11.2383575,117.4356766,0,163.3368073,0,201.936264c0,0,0,188.142746,0,188.1430206l475.7816772-288.8664856v355.1280823L0,456.3410034z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Glade';
-->
