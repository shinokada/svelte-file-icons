<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Buck';
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
    d="M389.1035156,259.7116394l-40.2094116-40.2094269l46.1893005-45.9830933V68.7684174h-37.7350159v89.0793457l-35.0543823,35.0543671l-34.6419678-34.6419678v-89.491745H249.917038v105.1631012l85.7801056,85.7801208h-53.4063721L144.960144,122.1747818V33.3016396h-37.7350082v104.5445099l46.1892929,46.3954926H99.5956573l-61.8606606-62.0668564V33.3016396H0v104.5445099l84.1304932,84.1304932h107.2251434l37.7350006,37.7350006H121.8655014l88.6669388,88.6669312L80.4188538,478.6983643h53.4063721l130.3197937-130.3197937l-51.1381531-51.1381226h261.2581482v18.7644043l-115.8856201,69.2839355l-93.6158142,93.4095764h52.9939575l61.8606567-62.066864L512,337.6560364v-77.9444275L389.1035156,259.7116394z M288.8892822,321.7784729l26.6000671,26.6000671l26.6000671-26.6000671H288.8892822z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Buck';
-->
