<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Alex';
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
    d="M264,512H0v-16h264V512z M264,423.5646667H0v-16h264V423.5646667z M1.1143544,224.7771606C3.6666667,69.6666641,211,187.6666718,210.1004333,90.6068954c1.4678192-29.3639259-10.7370758-67.8338852-59.6455383-72.2849121C70,11,37.2859154,48.8122559,34.6779633,101.4058914H17.6702404C21.6182613,29.0255222,72-7.5,150.9204865,1.3521686c27.9860382,3.1390734,74.2303467,19.733427,76.2833099,85.507431v178.9245605c-0.2554169,19.1893311,16.2711029,18.0827026,36.2868958,15.6560059v17.2721863c-55.2421875,0.3731689-53.0794067-7.5570679-53.0636902-55.4024963C159.5,336.5-4.8866258,318.4769897,1.1143544,224.7771606z M209.8681183,134.4889069C168,175.5,16.2114716,113.9298096,16.8532982,224.777359c0,68.3419647,79.3839722,67.7612152,113.3091888,59.0364532c42.3394012-10.8887024,78.6600647-43.6743011,79.670639-103.2542725L209.8681183,134.4889069z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Alex';
-->
