<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Nuclide';
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
    d="M375.5454712,285.4915161l30.6863403-30.416748V0L254.2548981,150.057373l-8.3574829-6.7918701l29.6655121-29.3928223V0l-97.8824921,96.6461792C25.4281597,11.8402491-51.8704567,67.4410095,38.7414093,233.8303223L16.3602448,255.928833V512l119.8510132-118.8546143V251.9432373l91.7105713-90.8674316l8.3486328,6.7388916l-89.241333,88.1141357V512l81.7730103-81.0545044C408.255249,543.0166626,486.4805298,465.1925659,375.5454712,285.4915161z M159.0931549,114.9987183L57.4244537,215.3833008C-11.7484102,76.5376434,35.2567902,53.0350418,159.0931549,114.9987183z M247.1997833,412.7094727l110.0851288-109.1179199C446.4293823,452.5246582,401.5344543,501.8410339,247.1997833,412.7094727z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Nuclide';
-->
