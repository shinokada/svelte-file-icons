<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Red Old';
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
    d="M89.5877533,211.4285736l73.1979218-24.7243347v24.6597443l91.1453705,41.0799408l95.2832184-42.6489258v-23.0520477l72.1815796,24.6856842v95.6773834L255.532547,379.5562134L89.5877533,308.0354309V211.4285736z M429.5774536,288.5397644V312.34375l-174.024826,75.9320679L81.5326767,313.2995911v-25.8396301L6.214251,314.2857056v92.5714417L255.9999695,512l249.7857666-105.1427917v-92.5714111L429.5774536,288.5397644z M291.9285278,95.7777634v32.7276077c-24.1673279,9.8699036-48.8226013,11.6404877-74.2857056,0V96.6897354l-46.8571472,17.5959778v91.9088974l83.1567383,37.4794312l87.2718506-39.0630646v-90.3251953L291.9285278,95.7777634z M283.9285278,12c0-6.3118024-13.047699-12-29.1428528-12s-29.1428528,5.6881976-29.1428528,12v111.3325882c6.7935944,3.0569916,17.3180847,5.2388382,29.1428528,5.2388382s22.3492737-2.1818466,29.1428528-5.2388382V12z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Red Old';
-->
