<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Adobe XD';
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
    d="M0,0v512h512.0001831V0H0z M217.5379028,367.5270386l-47.336853-97.5570679l-45.6730957,97.3242798H80.0134277l65.5073242-124.7985229l-63.336853-126.1956787l46.2019043,0.000061l44.8421021,95.9272461l44.4664307-96.1600952h43.3689575L197.675354,238.5375366l67.1321411,128.989502H217.5379028z M420.4967041,357.2824097c-19.5579834,9.3133545-40.0473022,13.5043335-59.6052856,13.5043335c-50.5247803,0.2327881-86.6138916-30.9668579-86.6138916-94.2974243c1.6445923-64.8764648,44.8722534-101.0769653,105.4733887-96.1600952v-64.0291138h41.4442749v215.6034546C421.2805176,357.6171265,424.1189575,355.1435547,420.4967041,357.2824097z M379.7509155,216.8840332v115.2523804c-40.9071045,10.6143188-63.5245972-14.2808838-63.3305664-57.5097656C316.5747681,230.2919312,345.7028198,207.2831421,379.7509155,216.8840332z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Adobe XD';
-->
