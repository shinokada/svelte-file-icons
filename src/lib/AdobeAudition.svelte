<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Adobe Audition';
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
    d="M167.7963867,154.2981567c5.5854492,26.5308838,20.9454346,81.2218018,27.2290649,106.3563843h-53.5272827C150.807251,225.5126953,163.1417847,180.8290405,167.7963867,154.2981567z M512,0v512H0V0H512z M266.6732178,367.7090454L192.7050781,118.690918h-51.2069092c-0.0675049,8.0930786-0.6244507,15.5253906-2.3272705,21.4108887L73.7692261,367.7090454h39.1572266l18.7971802-69.8181763h72.8436279l19.3939209,69.8181763H266.6732178z M429.4436035,356.2472534c-0.7443237-13.6315308-1.6908569-22.1363525-1.6908569-25.076355V183.8545532H388.421814v147.7818604c-30.8536987,10.6239014-57.0956421,2.2410278-55.8544922-29.7891235V183.8545532h-41.6582031v122.8800049C289.8806763,380.8157959,359.8425293,384.6430054,429.4436035,356.2472534z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Adobe Audition';
-->
