<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Vala';
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
    d="M19.2691288,512C8.6270828,512,0,503.3728943,0,492.7308655V19.2691288C0,8.6270828,8.6270828,0,19.2691288,0h473.461731C503.3728943,0,512,8.6270828,512,19.2691288v473.461731C512,503.3728943,503.3728943,512,492.7308655,512H19.2691288z M267.5903625,102.6948166c-39.7624817-3.6016312-83.1676788,4.4826889-131.5079498,41.9707108c-51.749733,40.1320648-56.7729797,116.457489,7.4051819,113.0686951c-13.7596588-26.053009-9.4805908-101.9598236,59.0791168-126.6752319l7.0332184,298.3535461l62.9040985,0.009613l121.337677-325.4555969h-30.4934082L271.4345398,371.402771L267.5903625,102.6948166z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Vala';
-->
