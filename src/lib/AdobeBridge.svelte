<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Adobe Bridge';
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
    d="M240.8727417,292.0726929c-0.21875,25.6407471-18.3078003,43.4885864-75.6363525,39.7963867v-78.4290771C220.0993042,250.8902588,240.1558228,261.7189331,240.8727417,292.0726929z M512,0v512H0V0H512z M248.3200073,232.2617798c41.9657593-34.6270142,31.9192505-119.743103-58.4145508-116.3635864c-22.807251,0-53.7600098,0.6981812-64.2327271,1.1636353c0,0,0,249.4835815,0,249.7163086c11.8690796,0.2327271,36.7709351,0.6981812,61.4400024,0.6981812C293.6281738,371.1748047,308.1078491,262.0947266,248.3200073,232.2617798z M404.7127075,178.522583c-35.9335327,0-69.6239014,10.0357056-87.1691284,16.9163208c1.2930908,13.9163208,1.2927856,21.3572388,1.2927856,24.2556152l-0.000061,148.0145264h41.6582031V220.8581543c7.7944336-3.2094727,29.9872437-5.074585,44.2182007-4.4623413V178.522583z M217.6000366,219.2290649c7.9127197-6.7490845,14.1963501-16.7563477,14.1963501-33.0472412c-1.6503296-26.4024658-15.4886475-38.4130859-66.5599976-34.2109375v66.7927246C165.2363892,218.7636108,209.6280518,217.9664917,217.6000366,219.2290649z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Adobe Bridge';
-->
