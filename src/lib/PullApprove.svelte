<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'PullApprove';
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
    d="M483.0149841,97.422081c-57.4418335-45.4897537-138.5602722,1.6443634-122.2199707,78.7122879L192.0784149,345.183136c-13.7045746,13.5649719-41.7032166,15.8180237-55.7960968,2.6569519l-28.1698685-28.3134766l54.807579-54.8075867H0l0.5123273,162.4077148l53.6711655-53.6711731c6.7848358,7.8432617,28.5118408,31.757843,51.5009003,44.3121338c39.4787216,21.5593262,87.9171829,19.5993958,129.3029785-7.8893127l180.2751923-179.9407043C503.274231,251.1933289,543.7355347,145.5083618,483.0149841,97.422081z M447.2493896,200.6778564c-34.163208,9.2840576-65.7752991-22.0254974-56.7650757-56.2219849c9.0101318-34.1964645,51.9459839-45.8645477,77.0991211-20.9521332C492.7365112,148.4160919,481.4126587,191.3937988,447.2493896,200.6778564z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'PullApprove';
-->
