<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'SmartOS';
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
    d="M465,512H47c-25.9573841,0-47-21.0426025-47-47V47C0,21.0426159,21.0426159,0,47,0h418c25.9573975,0,47,21.0426159,47,47v418C512,490.9573975,490.9573975,512,465,512z M444.4159851,238.5908661H91.1360016V85.502861H244.223999v118.7840042h23.552002V61.4388618H67.5839996v200.7039948h353.2800293v153.0880127H267.776001v-99.8399963h-23.552002v123.3919983h200.1919861V238.5908661z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'SmartOS';
-->
