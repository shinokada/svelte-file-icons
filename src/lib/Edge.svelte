<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Edge';
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
    d="M41,0h430c22.6436768,0,41,18.3563232,41,41v430c0,22.6436768-18.3563232,41-41,41H41c-22.6436768,0-41-18.3563232-41-41V41C0,18.3563232,18.3563232,0,41,0z M333.0846252,174.6738586c-0.9084473-15.9739838-0.9715576-32.9874268-0.3688049-50.1603317l-161.9146423,0.0000076c12.0299377,21.7817841,10.8443298,24.801712,12.1672974,62.2738647l0.0000153,129.395401c-0.6912994,48.1025696-2.9300385,56.0940857-12.1673126,71.3036804h165.6029053c0.9147034-19.3880615,2.5233459-40.3373413,4.7947388-62.7004395c-13.6465759,19.916626-19.5477905,30.6125488-65.2822266,30.6125488h-39.4643707v-83.7234802h34.3007965c39.3824463-0.676178,45.529541,11.0032959,53.8486328,16.9660034c-1.5389709-21.7702026-1.5925293-43.5312805,0-65.2822113c-16.2548218,14.6798401-26.6840515,15.8444977-53.8486328,16.597168h-34.3007965v-83.3546753h43.1526337C305.1159668,156.9011841,319.730896,161.0737915,333.0846252,174.6738586z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Edge';
-->
