<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'OpenVPN';
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
    d="M284.0309448,339.661438L315.4615479,512H194.3598022l31.836853-171.976593c-45.5335693-17.043457-66.8038635-73.7594604-37.5342102-118.3743744c34.2177582-52.1570129,112.0698853-49.0016174,139.7975464,5.6661377C350.9381409,271.6328735,326.9294128,323.0986328,284.0309448,339.661438z M476.3900757,130.7795715C376.6859741-42.6178131,129.9395142-43.8329163,33.3124237,128.5976257c-72.23349,128.9002075-20.4396305,283.2172546,92.3303528,353.3242493l17.2288513-109.7336121c-42.8870544-47.5073547-56.0652313-120.7338104-19.2859955-183.606781c60.0104675-102.5861282,208.3931274-101.3418732,266.4477539,2.2343597c35.506073,63.3470306,21.0786133,136.1710358-22.4892883,182.963028l15.6077576,113.7259827C499.7333984,420.7658691,552.5061646,263.1545715,476.3900757,130.7795715z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'OpenVPN';
-->
