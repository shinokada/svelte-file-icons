<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Adobe Premiere';
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
    d="M0,0v512h512V0H0z M264.0953979,237.798111c-18.4618835,26.6161346-55.4204865,40.048111-106.4229736,37.6388397v97.1322327h-43.5428772V103.4999313l65.8720551-1.1167984c54.756073-2.060463,96.7329865,26.941803,97.1338043,84.8514557C276.6628418,207.627121,273.2263489,224.6342316,264.0953979,237.798111z M406.6463318,208.448349c-0.0529785,1.7313538-0.9386902,2.2740021-2.2331238,2.2331238c-16.2471008-1.4738617-32.9920959,0.9992828-46.8914795,4.4651337v157.4225769l-43.5433655,0.0003662l0.0004883-158.5395508c0.1739807-9.3945618-0.3418884-16.2161255-1.1166077-23.445694c-0.1638489-0.8277435-0.1901245-2.5627899,2.2332153-3.3497162c21.7662354-7.8951263,54.6452942-17.4235687,89.317749-16.7462769c1.3707275-0.0077515,2.2214661,0.608963,2.2331238,2.2331238V208.448349z M232.4759216,188.351181c0.0511475,13.4279327-2.1696777,23.0260315-7.2939911,29.9068604c-13.1988831,17.723114-39.2106628,17.4191589-47.412323,18.1023254h-20.0971832v-94.9003143l23.4457092-0.000351C219.2071686,141.7271729,231.8956146,160.9984436,232.4759216,188.351181z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Adobe Premiere';
-->
