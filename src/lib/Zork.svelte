<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Zork';
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
    d="M0.7588534,165.5107727L62.4197273,0h395.1688538v15.4152184L288.0211792,237.7189178c69.901123,28.1874847,114.1939392,1.2206573,154.0352478-44.8339691c5.5787048-1.7076416,12.5361328,1.0178375,18.6990662,9.0378876c-51.7479858,76.8191681-116.8774719,126.8765717-208.3802338,85.3394928L112.774498,472.1924744l214.0715942-0.8115234c78.3468628-0.9732666,113.2622986-56.1773071,124.2518616-132.2986145h18.660553c-1.6916504,50.3412781-7.9119873,109.5737-16.226532,172.9176636H0v-16.226532l177.3301392-230.7221375c-43.5321045-14.0349731-95.4857864-18.8066559-145.6883545,52.1776428c-7.5692635,2.1328125-14.0436687-0.9187622-19.4718628-8.9246216C67.94133,224.758194,124.3960266,188.5260773,213.3790894,217.4356995L347.9544678,38.9437218H150.9068756C97.8538895,45.7041206,50.0013504,96.1165314,26.7737923,165.5107574L0.7588534,165.5107727z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Zork';
-->
