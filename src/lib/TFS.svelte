<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'TFS';
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
    d="m44.529612 42.12578c-77.210506 74.21659-49.379694 203.31092 47.762106 241.27287l-21.228696 82.21758c-42.472764-0.14076-74.825877 37.23497-69.539556 83.02718 6.4059294 55.49117 71.833087 82.49001 117.1622 48.06562 43.19742-32.80549 37.45733-98.06651-7.94347-122.37348l23.40575-84.25984c50.35311 5.63164 73.21286-5.18856 103.11658-29.71486l102.94492 105.55898c-26.79176 45.49276 2.62823 106.35591 56.29587 112.03521 55.54963 5.8785 96.20396-52.0644 72.52017-103.8219-19.19214-41.94171-69.07379-54.54383-104.26037-33.40985l-103.09664-105.72763c21.75232-28.70536 33.28853-65.46887 28.50209-104.63142l84.0727-23.52689c18.78346 38.10149 61.39611 60.91332 103.36347 30.25611 46.83152-30.44867 41.86849-104.38152-9.14097-129.63635-48.61058-24.06709-100.06525 13.44972-101.60935 64.924774l-85.10157 23.830411c-38.50793-103.56266-162.23063-124.1414-237.22524-54.086515zm67.323478 169.60471c-48.066315-28.45943-48.066315-99.99436 0-128.45388 48.06641-28.45944 109.14094 7.30811 109.14094 64.22698 0 56.91897-61.07453 92.68634-109.14094 64.2269z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'TFS';
-->
