<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Wine';
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
    d="M0,48.7390518C13.7058411,5.5656528,150.7642517-14.9931087,170.6377106,12.4185734c0,0,94.4404755,200.1340027,15.9539642,313.5033875c-7.9616089,31.1829834,13.3554535,123.0445557,34.7576599,121.657074c21.4022064-1.3875122,55.122345-7.2013245,76.6334534,6.7518311c14.6850586,9.5254517-15.9358826,35.9494934-88.2834167,49.4421082c-96.9077606,18.0730286-129.6398315,3.3526611-112.8745804-15.1405945c9.0988464-10.0366821,55.4126663-22.5272827,62.1629715-29.7597351c19.1881714-20.5587769,1.4600983-108.5446472-23.2104187-124.306366C35.7797356,295.0323486,0,48.7390518,0,48.7390518z M159.9624786,321.8763733c82.08992-52.8880005,17.727417-251.8735962,17.727417-251.8735962c-56.6847-35.7549629-35.7798157,113.9188919-147.4050598,51.1296844C30.284832,121.1324539,64.2431107,296.1905212,159.9624786,321.8763733z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Wine';
-->
