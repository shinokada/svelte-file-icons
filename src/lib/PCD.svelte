<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'PCD';
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
    d="m236.45378 308.43014c-27.62129-15.92397-27.62129-55.95006-2e-5 -71.87403 27.62128-15.92398 62.33534 4.08906 62.33534 35.93701 0 31.84796-34.71405 51.861-62.33532 35.93702zm-54.74843-136.37042c40.52632-65.06207 131.19629-49.27531 145.48378 1.48598 78.66804-27.58034 131.5178 36.62606 104.41893 89.02074 83.50274 21.11969 61.57538 124.06292-30.79637 127.51622h-300.74574c-92.271966-12.89219-94.570833-102.06256-21.317807-128.41811-28.312505-67.12196 43.865077-112.10466 102.95721-89.60483zm-134.10815 77.22428c-18.730859-70.83938 57.349059-125.79346 123.24547-107.51072 53.79914-65.416546 146.097-46.022536 169.7002 3.81403 68.37184-20.54702 136.86021 30.9094 123.76086 104.17788 78.41574 34.82821 60.17646 159.39578-54.97954 162.20585h-318.87022c-112.38602-16.65631-112.02796-128.44139-42.856752-162.68704z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'PCD';
-->
