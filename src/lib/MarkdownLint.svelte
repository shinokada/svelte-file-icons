<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'MarkdownLint';
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
    d="M342.1774292,285.7508545L473.1215515,154.808136L512,190.743576L341.1293335,360.5756226L237.5744019,255.9628601l38.4361877-36.3778076L342.1774292,285.7508545z M276.4831543,185.2120361l-74.1472015,70.1766968l112.9732208,114.1272888H26.1086788C11.8056488,369.5160217,0,357.7103577,0,343.1803589V168.5926666c0-14.3030243,11.8056488-26.1086731,26.1086788-26.1086731h290.7789001c14.3029175,0,25.5173035,11.8056488,25.2902222,26.1086731l-0.0003662,82.3126221L276.4831543,185.2120361z M195.8570862,184.8557281h-46.0302429l-34.5227051,46.0302429l-34.5227127-46.0302429H34.7511864v138.0908356h46.0302391v-69.0454102l34.5227127,44.1890259l34.5227051-44.1890259v69.0454102h46.0302429V184.8557281z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'MarkdownLint';
-->
