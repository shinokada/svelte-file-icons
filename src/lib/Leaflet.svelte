<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Leaflet';
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
    d="M156.4829712,498.5690918c-28.1542206,26.4686279-77.2916718,11.4086609-108.5622101-24.1750488C6.4017744,427.1483154-8.6309614,337.6677551,4.7536683,257.8728027L156.4829712,498.5690918z M189.2150421,468.0584106c-18.2281799-7.7469482-91.4576569-45.5538025-62.4625854-179.7611389C80.301506,257.7653503,13.6443195,234.8005981,9.377574,229.8195343c0,0,0.1739359,8.0732727-1.9611459,23.9019775L165.0528717,489.072052C168.9690857,481.3536377,179.3526306,475.1939087,189.2150421,468.0584106z M139.4286194,388.4790649c15.5429382,51.181488,43.0429688,57.2320251,63.3149414,69.8901978L408.585022,17.9921646h2.4346619L219.9126434,472.9949036c19.3815613,18.2740479,45.2353973,36.6472473,84.0380707,27.9019775C463.9076843,472.323822,500.4275818,214.2499847,413.9022217,0C312.1472778,69.7935562,235.9975281,107.4278717,186.3201752,181.3138885C147.6822205,238.7807922,117.7081223,319.7099915,139.4286194,388.4790649z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Leaflet';
-->
