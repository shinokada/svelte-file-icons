<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Adobe Dreamweaver';
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
    d="M186.1818237,232.7272949c0.6412354,52.7476807-22.9976807,103.6418457-94.8363647,94.9526978V144.9891357C159.6582031,137.4953613,185.4953003,172.3790283,186.1818237,232.7272949z M512,0v512H0V0H512z M229.4691162,231.7963257c0-73.7745361-38.8654785-124.0436401-116.8291016-124.0436401c-26.0654907,0-54.2254639,0.6981812-63.0690918,1.1636353c0,0-0.2327271,255.5346069,0,255.7672729c10.4727173,0.2327881,41.192749,0.6981812,60.7418213,0.6981812C162.2109375,365.3817749,229.4691162,334.4290771,229.4691162,231.7963257z M474.2937622,175.0109253h-40.3396606c-16.5981445,85.7510376-22.4663696,119.8430176-26.3322754,145.4545288c-2.4188843-20.0770264-11.9741211-68.7128906-25.6897583-145.4545288H337.456543c-17.3963623,80.7183228-26.2984009,123.4296265-29.2092896,144.2908936c-2.4332886-17.7630615-9.4190063-61.2244873-24.0385132-144.2908936h-44.015564l42.4996338,189.2072754h44.3537598c15.4000854-66.5058594,25.1047974-114.7496338,30.1898193-144.2909546c4.3875732,33.1506348,14.4807129,79.538147,26.2194824,144.2909546h43.8358154L474.2937622,175.0109253z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Adobe Dreamweaver';
-->
