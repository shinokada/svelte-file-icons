<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Cuneiform';
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
    d="M395.0526733,27.2746429c-93.2790527-0.2792797-121.3332825,42.597908-141.9999237,135.3184052C132.0725098,187.7523804-7.6801133,265.0194702,0.3289795,380.5968933c3.0246768,43.648407,48.4294662,124.9583435,209.0106049,75.2386475l-16.1252899-65.1730957C-6.336338,459.8668823,40.6957932,280.4728699,245.621521,234.7845154v249.9421997h63.8293152V223.3467865c63.3967285-7.3284607,129.8173828-9.0051727,198.8787537-2L512,153.9386139c-64.3235168-5.1535187-128.3792725-4.2923889-190.4395142,0.2037201c18.0842896-56.879715,26.6109009-54.7026901,80.6108398-62.4698792L395.0526733,27.2746429z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Cuneiform';
-->
