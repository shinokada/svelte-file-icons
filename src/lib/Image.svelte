<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Image';
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
    d="M329.1428528,0H0v512h438.8571472V109.7142868L329.1428528,0z M402.2857056,475.4285583H36.5714302V36.5714302h256l109.7142639,109.7142944V475.4285583z M219.4290009,329.1430054c40.357132,0,73.1424408,32.785553,73.1424408,73.1427002h73.1428528V182.8571472l-73.1428528-73.1428604H73.1428604v292.5714111h73.1428604C146.2857208,361.9285583,179.0541382,329.1430054,219.4290009,329.1430054c-56.0967865-0.0000305-91.347641-51.1452026-63.2992249-99.7970886s98.5501099-48.6518555,126.598465,0.0000763S275.5257874,329.1430359,219.4290009,329.1430054z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Image';
-->
