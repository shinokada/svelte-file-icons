<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'SilverStripe';
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
    d="M57.3865852,124.1276855L238.6399231,0c27.4260254,40.0732536,17.1945496,94.7831726-22.8787079,122.209198l-108.7093887,74.4624481C60.6923599,229.75,105.4423599,300,156.6461029,269.2866516l72.4729004-49.594162c27.4260406,40.0732574,17.216629,94.8154755-22.8787231,122.2092133C44.4810333,436.7769775-76.3238297,219.3282166,57.3865852,124.1276855z M301.5918884,170.0983124c-40.051178,27.458252-50.3047333,82.1359406-22.8786926,122.2092133l72.4728699-49.5941925c50.0844727-30.8254242,95.7718811,36.8454742,49.7362976,72.615036L292.0709534,389.790802C251.9977112,417.2168274,241.7662354,471.9268494,269.1922607,512l181.182251-124.0566101C587.5569458,288.2476501,456.2756958,75.6666641,301.5918884,170.0983124z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'SilverStripe';
-->
