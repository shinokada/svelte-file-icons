<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'ESLint';
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
    d="M362,315.7700195L256.9989014,376.390625L152,315.7700195V194.5268402l104.9989014-60.6207275L362,194.5267181V315.7700195z M508.8313904,269.1393433L392.6442871,469.9437256c-4.2184753,7.3105774-12.0168762,10.9347229-20.45578,10.9347229H139.8122559c-8.440918,0-16.2393341-3.7366028-20.4597931-11.0451355L3.1653447,269.3561707c-4.2204595-7.3105469-4.2204595-16.5365906,0-23.8471527L119.3524628,43.821167c4.220459-7.308548,12.0188751-12.6996059,20.4597931-12.6996059h232.3782654c8.4389038,0,16.2352905,5.391058,20.4557495,12.6996059l116.1871338,202.1335907C513.0558472,253.2633057,513.0558472,261.8327942,508.8313904,269.1393433z M412.6241455,347.8442383l0.0001221-180.1447906L255.9272461,77.3683853L99.40271,167.6795502V347.840332l156.6745605,90.3242188L412.6241455,347.8442383z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'ESLint';
-->
