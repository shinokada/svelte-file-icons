<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Workbox';
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
    d="M148.1016083,368.3325806l-23.3533325-7.094696l-1.182457-282.6051025l-53.801384,25.7182465l-2.9561157,240.33255l-19.2147827-5.9122314l-1.4780617-223.1870728L0,137.755188v236.489624l211.9538116,101.986145V35.7690506l-61.4872894,29.561203L148.1016083,368.3325806z M238.5588837,44.0461845v197.4688416L512,246.244812V128.2956085L238.5588837,44.0461845z M299.7505798,141.5981445l167.61203,32.2217102v18.9191742l-167.6119995-20.6928406C299.7506104,172.0461884,299.7506104,141.5981445,299.7505798,141.5981445z M238.5588837,270.4849854v197.7644348L512,383.7044067V265.7552185L238.5588837,270.4849854z M299.7505798,338.475769l167.61203-19.5104065v18.9191895l-167.6119995,31.0392456C299.7506104,368.9237976,299.7506104,338.475769,299.7505798,338.475769z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Workbox';
-->
