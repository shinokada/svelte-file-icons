<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Adobe Prelude';
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
    d="M242.036377,188.5090942c-0.1741943,33.6048584-19.2854004,50.3499146-71.4472656,46.0800171v-89.8327637C223.8015137,139.5648804,241.5307617,156.1242065,242.036377,188.5090942z M512,0v512H0V0H512z M283.694519,187.8109131c0-45.3818359-28.1599731-80.7564087-92.6254272-80.7564087c-23.039978,0-47.0109253,0.4654541-61.9054565,1.1636353v256h41.192688v-92.3927002C248.9525757,278.3828125,284.0682373,239.086731,283.694519,187.8109131z M385.1641846,330.9664307c-13.7339478,3.2598267-18.5819092-0.421814-18.6187134-11.4318848V108.2181396H324.654541v214.807251c-0.0625,37.8108521,19.6776123,51.7252808,60.5096436,40.9754028V330.9664307z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Adobe Prelude';
-->
