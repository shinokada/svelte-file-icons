<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Adobe InDesign';
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
    d="M265.3009644,269.3344727c-1.2391968-39.9379425,26.8214722-71.5475616,67.561615-60.9161377v122.9390869C292.2644043,341.1659546,263.5885925,317.0328369,265.3009644,269.3344727z M0,0v512h512V0H0z M177.804184,369.013855h-43.1942749v-266.920105h43.1942749V369.013855z M312.9261475,372.3360291c-49.2962341,1.4241028-92.8896484-29.8414307-91.927063-100.7867737c0.7735748-57.0149536,36.3030701-108.2121277,111.8634949-103.0026703v-66.4528275l44.3026428-0.0002747l-0.0002136,239.7855835c0,4.066925,0.369751,9.8865051,1.3634644,14.7131348C361.5177307,366.0103149,339.4805298,372.1659851,312.9261475,372.3360291z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Adobe InDesign';
-->
