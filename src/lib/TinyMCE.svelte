<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'TinyMCE';
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
    d="M512,221.7675476l-16.7779236-16.9755707l-34.7937012,34.3885651L259.2507324,38.9562531L0,295.2468872l16.7797775,16.9737244l39.8134003-39.3587952l201.1686707,200.1819153L512,221.7675476z M259.1947937,72.573616l184.2581482,183.3847351L257.8196411,439.4301147L73.5667038,256.0820923L259.1947937,72.573616z M320.6072388,193.0266571H196.0986176v-21.0031586h124.5086212V193.0266571z M359.1210938,244.5607452H157.5847473v-21.0031586h201.5363464V244.5607452z M359.1210938,295.3457336H157.5847473v-21.0031738h201.5363464V295.3457336z M320.0552979,346.1307068H196.6505585v-21.0031433h123.4047394V346.1307068z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'TinyMCE';
-->
