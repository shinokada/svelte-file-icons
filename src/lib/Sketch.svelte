<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Sketch';
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
      fill-rule: evenodd;
      clip-rule: evenodd;
      fill: #111418;
    }
  </style><path
    class="st0"
    d="M239.3204498,496.6680603L97.9060974,229.3578796L2.2777572,155.5922699L239.3204498,496.6680603z M510.7409973,155.5922699l-95.6283569,73.7656097L273.6982727,496.6680603L510.7409973,155.5922699z M391.236969,232.2203827h-270.473938L255.989212,497.7600098l135.247757-265.5610962V232.2203827z M102.0814667,208.9760284L0,131.2796173l62.0279961-72.5309982l88.113327,43.1311874l-48.0383377,107.0962219H102.0814667z M167.40242,108.982254l-46.6393661,104.2552338H391.236969L344.5975952,108.982254H167.40242z M409.8754883,208.9760284L512,131.2796173l-61.9849854-72.5309906l-88.1563721,43.1311836l47.9952698,107.0962143H409.8754883z M344.5975952,90.0424118H167.40242L81.5919952,47.3847046l77.8685913-33.1447296h193.0572968l77.9116211,33.1447296C430.4295044,47.3847046,344.5975952,90.0423965,344.5975952,90.0424118z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Sketch';
-->
