<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Adobe Dimension';
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
    d="M212.8094482,231.3197021c-1.7296143,64.543396-28.5776367,102.6958618-95.2287598,95.694397V143.0759277C184.925354,135.6611938,213.1524048,170.8118286,212.8094482,231.3197021z M512,0v512H0V0H512z M256.116394,230.3883667c0-74.2738037-39.1159668-125.0313721-117.5806885-125.0313721H74.972229v259.6088867h61.2351074C188.3619995,364.9658813,256.116394,333.7662354,256.116394,230.3883667z M437.260498,239.7016602c0-56.5784302-36.7875977-69.3842163-69.6170654-69.3842163c-26.7758179,0-53.3187256,7.9163208-73.1095581,15.3669434c-4.2505493,1.9510498-0.6871338,0.9165039-0.6984863,26.7758179l-0.000061,151.8071289h42.6084595V211.9945068c37.0501709-10.5390015,58.6879272-1.8722534,58.208313,30.7340088l-0.000061,121.5388794h42.6084595V239.7016602z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Adobe Dimension';
-->
