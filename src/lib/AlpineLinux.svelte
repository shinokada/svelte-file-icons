<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Alpine Linux';
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
    d="M384.0214844,34.2768898H127.978508L0,255.9999084L127.978508,477.723114h256.0429688L512,255.9999084L384.0214844,34.2768898z M147.1620636,295.4020996l38.8415833-38.8828735v53.9402161C172.375,310.1666565,159.3208008,303.9169312,147.1620636,295.4020996z M299.767334,305.9755859c-23.7467957-24.4812622-54.3271942-55.1417084-87.5346832-88.1777344l-88.9374542,87.9747314C109.2761688,315.6438599,85.875,308.75,67.474205,295.3641663L212.593811,151.8847504c45.9142151,48.2947998,93.569458,96.1930847,143.0358276,143.6788788C331.7724915,312.664978,310.25,313.875,299.767334,305.9755859z M384.5819397,305.9755859l-71.3183899-71.0779419l-7.1147766,7.1147919l-33.2984924-32.9348145l40.4304199-40.4402924c43.1062317,43.4316711,85.4614258,86.1768494,127.1635132,126.9263C419.875,310.3125,397.0625,315.375,384.5819397,305.9755859z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Alpine Linux';
-->
