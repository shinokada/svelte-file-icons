<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'San';
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
    d="m159.59385 373.60989-159.59351 32.33161v106.0585l424.34366-85.96625v-0.52984zm-159.59351-77.66238v1.1178l2.8036453-0.56804zm156.78952-137.327-156.78986 31.76357 266.08055 52.15475 155.45946-31.49449v-0.52983zm267.55457 30.61441-424.34443-83.17626v-106.05866l424.34443 83.176246zm-424.34443 25.69941 424.34443 83.17625v106.05866l-424.34443-83.17709z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'San';
-->
