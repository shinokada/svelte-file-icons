<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Codecov';
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
    d="M348.001709,512l23.643219-37.9451904c-159.9589233-2.4486694-171.7181244-227.0859985-12.552948-243.9669037c44.5465088,0.806015,57.7512512,7.0200043,108.1329956,42.5207977C483.6984253-96.9210129-22.2359467-84.9225693,0.7610698,273.0823975c13.4120626-8.1205444,32.3053589-22.4839783,40.0368652-26.7579193c38.9690323-21.5418854,93.0461044-26.8078766,143.8954773,16.615097c5.1728058-11.6952209,11.8958588-23.0825806,20.7125397-34.0541382c-47.1447601-37.7267151-104.3901749-48.2917023-162.8059845-26.667572c41.6502762-218.1493835,344.1110229-214.6498413,383.0047607-0.3175354c-92.2893372-31.6978302-167.198822,9.6236725-200.524231,71.9941711C180.4817963,357.3636475,209.1231689,487.0681458,348.001709,512z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Codecov';
-->
