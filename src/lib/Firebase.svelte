<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Firebase';
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
    d="M323.6689453,114.5549011c-1.5154724-9.3351746-11.1121216-13.1981049-17.7937317-6.5044708l-62.2253418,62.1646729L195.781662,79.1765213c-4.4728699-8.514183-15.3392029-9.4062424-19.764679-0.8674698l-27.1287689,51.6599731L83.5214462,6.3320699C78.1267319-3.7996905,64.427269-1.2169248,62.6568794,10.1247387L0,410.8255615l143.0379944-269.6221008l46.368454,85.665863L0.053931,413.5736084l168.1032104,93.9602051c10.6602173,5.9521484,23.6433258,5.954895,34.3063202,0.0083313l169.6525726-94.6167908L323.6689453,114.5549011z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Firebase';
-->
