<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Xtend';
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
    d="M7.0103092,97.8116837h64.0942535l126.1855698,154.2268066L53.0780563,416.2799988H0v-15.0220642l124.1826172-147.216507L7.0103092,110.8308334V97.8116837z M171.7324066,47.4059563H90.5393906v11.5759239l158.786377,190.3065186L81.2895889,452.0906677v17.0102539h76.9709702l184.2237854-219.8125153L171.7324066,47.4059563z M505.7437439,61.758667V40.7277412h-81.1192932L313.4549561,168.9223022l55.0809937,58.0854187L505.7437439,61.758667z M362.635437,273.7150879h-8.995636l-39.1971741,40.685791v11.0679932l121.9103699,145.8033752H512v-22.2947388L362.635437,273.7150879z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Xtend';
-->
