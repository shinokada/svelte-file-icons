<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Tilt';
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
    d="M157.1739655,14.947897v127.9085617c0,8.0835724-6.5489197,14.6327362-14.6327209,14.6327362H14.6327238C6.5489097,157.4891968,0,150.940033,0,142.8564606V89.8256302c0-5.0910187,2.6604676-9.8233719,7.0093546-12.4841232L129.6736603,2.4640307C142.4738922-3.6804657,157.1739655,2.1054225,157.1739655,14.947897z M470,141.6285553V14.9479237c0-8.0582333-6.5489197-14.6071482-14.6327209-14.6071482H202.5946045c-8.0838013,0-14.6327209,6.5489154-14.6327209,14.6327286v482.3937683c0,8.0837708,6.5489197,14.6327209,14.6327209,14.6327209h141.2876587c8.0838318,0,14.6327209-6.5489502,14.6327209-14.6327209V170.8940125c0-8.0838318,6.5489502-14.6327362,14.6327515-14.6327362h82.2195435C463.4510803,156.2612762,470,149.7123566,470,141.6285553z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Tilt';
-->
