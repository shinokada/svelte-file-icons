<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Storybook';
</script>

<svg
  width={size}
  height={size}
  version="1.1"
  xmlns="http://www.w3.org/2000/svg"
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
    d="m53.97026 494.86989-24.840148-464.22305-29.130112 2.00016 19.130112 462.22289zm188.83829-386.74721c64.40922 0 101.41086 35.17368 99.58365 106.43494l-73.54647 1.82714c1.37041-38.37145-15.07399-42.02602-24.21005-42.02602-8.67925 0-23.29739 2.74126-23.29739 23.29739 0 50.70513 125.16543 47.96424 125.16543 150.28811 0 57.55717-44.76766 84.05018-101.86804 84.05018-58.92758 0-110.54624-20.09911-104.6078-108.26207h77.19888c-0.9136 35.63062 6.85376 48.42192 26.49629 48.42192 15.0745 0 21.92565-8.67969 21.92565-23.29739 0-52.07554-123.33643-53.90179-123.33643-149.37361 0-54.81636 36.08706-91.36059 100.49628-91.36059zm177.19145-108.12268-39.9777 3.26208v77.354145l-32.49442-32.34759-30.99256 36.34759v-78.149685l-259.88848 20.1803 26.840149 468.22305 336.51301 17.13011z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Storybook';
-->
