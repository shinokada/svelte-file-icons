<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'CircleCI';
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
    d="M126.6717911,198.9485779c21.2114182-46.0800018,68.0228653-77.5314331,121.4171371-77.5314331c73.8742676,0,133.8514404,59.9771423,133.8514404,133.8514404s-59.9771729,133.8514099-133.8514404,133.8514099c-54.1257019,0-100.2057037-32.1828613-121.4171448-77.5314331c-1.5213394-3.9629211-4.762619-8.0761719-10.9714279-8.0457153H12.568924c-9.420433,0.2774658-14.2671013,8.6994019-11.702857,15.3600159C29.3917809,430.0799866,129.5975037,512,248.8203583,512c141.1656952,0,255.9999847-114.8342896,255.9999847-256S389.9860535,0,248.8203583,0C129.5975037,0,29.0260658,83.3828506,0.5003524,193.0971527C-1.990362,200.75,5.2546382,206.9942932,12.568924,206.9942932h103.1314392C120.8203659,206.9942932,124.2528839,204.0659027,126.6717911,198.9485779z M218.3973846,308.5381775c-40.3809814-23.2800598-40.3809967-81.7962799-0.0000153-105.0763702S309.5286255,209.4398193,309.5286255,256S258.7783508,331.8182678,218.3973846,308.5381775z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'CircleCI';
-->
