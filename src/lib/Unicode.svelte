<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Unicode';
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
    d="M456.7077637,133.7792358c-24.5004272-14.1247559-24.5004272-49.6284103,0-63.7531815S512,73.6531067,512,101.9026489S481.2081909,147.904007,456.7077637,133.7792358z M446.5042419,355.6297302l-0.000061-178.8508911h58.026123v265.0574951l-78.2944031,0.0159912L281.8922424,171.8039551v154.5942078c-4.7910461,66.4599609-47.9965363,122.4780884-145.7291565,120.4811707C49.4947357,446.4729004,7.6573582,399.8953247,0,327.2168579V87.2323761h64.6781235l-0.0000076,208.0743561c0,65.3507385,23.3429031,94.7866211,75.9737091,94.7866211c54.0651398,0,75.5810852-26.2045898,75.5810852-94.7866211V87.2323761h84.643158L446.5042419,355.6297302z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Unicode';
-->
