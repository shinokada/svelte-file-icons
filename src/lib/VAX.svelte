<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'VAX';
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
    d="M0,134.7015228h51.2866096l90.3112946,154.7289581l90.3112793-152.4659119h51.2866211L141.5979004,377.2984619L0,134.7015228z M218.1465302,369.0843201l23.235672-40.0505981h102.4947815l-25.3145142,42.3136597h51.4710693l46.2871094-76.5487366l45.7871399,77.6802368H512l-70.2858887-120.7570038l67.4439392-111.2837982h-52.1026306l-40.4189758,64.9966888l-38.8401489-67.2597351h-50.8395081l63.470459,111.1522369l-10.7362976,19.2621765l-74.522522-130.7301941l-137.545639,231.2250671H218.1465302z M269.5324402,285.3642273l34.5722351-59.3334351l33.6378784,59.3334351H269.5324402z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'VAX';
-->
