<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Zig';
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
    d="M270.2759705,194.8598022H146.4011536v-61.9049225h179.1702271L447.700592,88L242.7554169,318.6696472h124.16362v61.90979H187.7487946L65.6152878,424L270.2759705,194.8598022z M0,132.9573059l122.5645294-0.004837v61.9049225H55.1273193v123.8146973h82.6909637L82.690979,380.5769958H0.0000041L0,132.9573059z M456.8683777,194.8607635h-82.690979l55.1316223-61.9049225H512V380.575531l-122.5645447,0.0048523v-61.9049377h67.4329224V194.8607635z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Zig';
-->
