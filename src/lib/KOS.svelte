<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'kOS';
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
    d="m149.30275 277.61924h-97.004208c-37.029961-1.47488-52.827054-19.77781-52.285082-29.61529 0.52288551-9.49103 18.528129-24.27356 58.281704-28.56756h165.78866l3.7e-4 31.02168h-74.78144zm74.78144-27.16117h73.90771v-31.02168h25.44154l70.90353-71.5109h105.25806l-85.86915 102.96083 98.27412 113.23972-106.25576-4e-5 -84.30623-84.80504h-96.77755zm-76.16766-44.23217v-58.30041h149.78735l0.28802 71.62696h-73.90808v-13.32655zm145.93531 87.75136v70.14874h-144.26107l-0.28802-86.50676h75.7364v16.35801z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'kOS';
-->
