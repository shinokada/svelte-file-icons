<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Nano';
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
    d="M3.526895,132.88797C-14.1914997,52.1708298,37.9793282,12.7966185,90.1501617,15.7496843c59.1713104,3.3493204,70.8735809,48.2334099,70.8735809,48.2334099C185.9443207,23.5866756,213.6627197,2.1445656,269.3028259,0c50.164917,4.4645653,104.3641968,46.264698,104.3641968,131.9036102v296.4234009c0.4486694,27.7712708,2.3066711,67.893219,8.9645691,83.6729736h-75.8406067c-11.2712402-11.2712402-15.8323364-33.8137207-15.8323364-71.9931946V135.8410339c-7.4139709-49.8481293-105.3260345-63.9824142-123.0444183-4.9210968c-0.5809937,36.0958099-3.1409302,237.5595551-3.1409302,237.5595551H91.1345139L89.165802,113.2008591c-8.8591919-48.2334137-54.3719826-56.4022865-58.0769577,14.7653275C31.0888424,127.9661865,17.307869,141.7471619,3.526895,132.88797z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Nano';
-->
