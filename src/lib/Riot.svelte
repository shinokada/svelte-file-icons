<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Riot';
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
    d="M0,16.02742c0-4.1958494,3.4013913-7.597249,7.59725-7.597249h339.8312073C438.3190308,8.430171,512,82.360199,512,173.5579987v29.0977478c0,4.196106-3.3995056,7.5974426-7.5969849,7.5974426h-94.5202637c-4.1956482,0-7.5969543-3.4017944-7.5969543-7.5974426v-29.0977478c0-30.3994141-24.5603333-55.0427551-54.8573303-55.0427551H117.3116531c-4.1960907,0-7.597435,3.4013443-7.597435,7.597435v370.105896c0,4.1928711-3.4124069,7.6246338-7.5983582,7.3340759C45.0668869,499.6365051,0,451.9637756,0,393.7281799V16.02742z M208.740097,228.6007843c-4.1956329,0-7.6241913,3.4123993-7.3400574,7.5983582c3.8902893,57.2540436,51.4089661,102.4866791,109.4572906,102.4866791H384c10.0988464,0,18.2857971,8.2146606,18.2857971,18.3476257v139.1851196c0,4.1928711,3.4124146,7.6246338,7.5983582,7.3340759C466.9347839,499.6365051,512,451.9637756,512,393.7281799v-36.6947327c0-70.9318542-57.3075867-128.432663-128-128.432663H208.740097z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Riot';
-->
