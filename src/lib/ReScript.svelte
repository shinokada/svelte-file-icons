<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'ReScript';
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
    d="M350.7831726,0.2647597H153.8602753C0.0537442-1.9128857,0,42.7150879,0,164.2109375v183.838501C0,478.6287231,6.6335311,512,143.865448,512h243.8985901C505.4656677,512,512,462.7759705,512,358.0442505v-193.833313C512,33.7894669,507.3484192-3.5864582,350.7831726,0.2647597z M236.992981,358.3263245c0,32.4497681,0.0945587,42.7553406-33.4827881,42.7553406h-35.9813843c-34.2092285,0-33.8114929-14.1252441-33.8114929-42.7553406V177.5651855c0-31.8852386,1.4842224-54.8908539,50.0838318-53.1690903h53.1918335V358.3263245z M316.3285217,239.752243c-40.410553-23.2971497-40.410553-81.8562012,0-105.1533661s91.1980591,5.9823914,91.1980591,52.5766907C407.5265808,233.7698059,356.7390747,263.0493469,316.3285217,239.752243z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'ReScript';
-->
