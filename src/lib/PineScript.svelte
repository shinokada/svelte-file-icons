<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'PineScript';
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
    d="M79.9550095,273.8516541L245.4951172,42.4455605c7.5135651-8.5733719,16.9632263-8.4433098,23.724884,1.1904488l160.0743713,226.6047058c5.6431885,8.3507385,5.3898926,16.0549927-3.3256836,20.756897l-57.3395081,33.37146c-18.368042-20.9013977-46.047699-20.9013977-63.0126343-3.3411865l-63.9906616-46.4303894c6.2502747-65.478775-85.1223755-70.5384979-85.3425293-6.0172119l-56.0865631,32.6820374C82.3561707,291.1185303,74.4728928,284.1833496,79.9550095,273.8516541z M81.3320236,343.880188L1.4379206,455.1601257c-4.2660694,7.0439453,1.4881251,20.6357422,10.3178425,20.6357422l485.3364868-0.3968201c13.0957947,0,17.4685364-12.0036011,13.4927063-20.2389221l-91.2926331-127.9530029l-41.4806213,24.7277527c-3.6834412,57.425354-89.0656128,52.7619934-84.5406799-5.0726318l-68.8084717-50.0416565c-15.5212555,14.055542-34.7693176,12.4211426-57.1451263-2.381012L81.3320236,343.880188z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'PineScript';
-->
