<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Lime';
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
    d="M362.0974731,165.3304596l-155.2584534,84.5106049l0.2359009-170.315918L362.0974731,165.3304596z M207.0904846,443.1411438l155.2045898-93.670105l-155.2045898-80.5766907V443.1411438z M371.7793579,340.3837585l-0.0073242-165.6475677l-155.652832,84.8906708L371.7793579,340.3837585z M194.0226898,73.0376968L37.0193863,160.0918121l156.7767944,88.1759949L194.0226898,73.0376968z M32.6175804,172.5809631v174.1737061l153.5140533-87.8330994L32.6175804,172.5809631z M194.0456848,268.6439514l-149.9663696,86.520813l149.9663696,87.2420959V268.6439514z M176.1998291,512v-45.8652649L3.4605627,366.7404785L0,147.036438L223.305191,0v50.2657318l179.3086395,101.0521545l1.7379456,204.9791107L176.1998291,512z M194.0453186,457.8166504V480.78125l190.7804565-129.8348694l0.8290405-187.2165985L207.0900879,59.5847588V34.0568008L17.9421158,159.3357239l1.611557,196.6520996L194.0453186,457.8166504z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Lime';
-->
