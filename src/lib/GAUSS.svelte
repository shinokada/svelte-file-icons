<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'GAUSS';
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
    d="M127.6986313,242.4235535c-8.4704437,6.9320831-10.4076614,14.4865112,0.2175903,23.2376709L315.1486206,416.2612l-62.8456573,54.2687988L5.4140558,264.1203613c-7.2329607-6.1028137-7.2161808-17.2522736,0.0351171-23.3332825L250.7218933,41.4699974l64.1067505,50.4274864L127.6986313,242.4235535z M312.7679138,185.4653931l67.0684204,57.4588776c6.685791,5.8161011,6.6713257,16.2050323-0.0307007,22.0024872l-92.6369019,79.25354l57.5981445,47.9984741l160.6714783-128.3562317c8.8525391-7.4494934,8.7288208-17.0489502-0.2570496-24.3370361L375.4859009,136.8269501L312.7679138,185.4653931z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'GAUSS';
-->
