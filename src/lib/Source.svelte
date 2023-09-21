<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Source';
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
    d="M334.6499329,484.493988c27.2902527-25.6569519,49.663147-57.3729248,64.7986755-94.2299805c1.0431824-2.5168152,105.5820923-257.1504822,105.8495178-257.8302612c24.4059753-62.0011978-20.8365479-118.7600098-87.296051-116.9751511l-255.151062,0.000164c-52.6529465-2.6768589-104.532608,11.6441088-149.3954315,37.4707985c-33.2236748,21.2446938,1.9860668,67.5693512,31.166996,40.3286858C277.276062-22.1183891,481.4319763,265.7079773,299.6764832,448.1720886l0.1968079,0.2771606C265.1615601,474.5794373,308.3857422,518.4124146,334.6499329,484.493988z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.vercel.app/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Source';
-->
