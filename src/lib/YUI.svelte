<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'YUI';
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
    d="M504.4458008,31.6125011c2.518219-0.5413818,5.0361633-1.0488434,7.5541992-1.5574875C410.5498962,169.3280487,347.7498474,325.9999084,318.392334,488.737915c-62.671936-6.6010132-115.0789795-24.3384705-169.4172821-54.5802612C194.9167633,296.2652893,334.2940369,124.9996567,504.4458008,31.6125011z M461.2930603,42.5077553C310.811615,86.3913574,135.7978821,205.616333,56.9972572,332.559082c30.1040382,26.0969543,59.761631,49.1558838,85.3147125,56.6572876C217.4933929,252.1313324,341.9507751,110.2987061,461.2930603,42.5077553z M490.3250122,23.7747478C290.0201721,17.1070766,138.9545746,75.241478,0,212.0028534c8.3894997,21.0387268,28.4596252,46.3064423,63.2596779,76.9071808C186.9166412,135.4559021,360.0476074,57.5059395,490.3250122,23.7747478z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'YUI';
-->
