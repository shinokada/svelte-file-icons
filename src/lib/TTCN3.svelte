<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'TTCN 3';
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
    d="m141.69194 4.5692898e-6c153.09547 1.68713 257.66615 130.6151 258.30806 248.92029 0.73483 135.42665-101.15168 266.95678-263.08923 262.99229 252.40281-13.93026 310.65565-458.97032-0.91077-511.91258m103.54489 169.09985c3.22147-14.2144 15.10132-39.44567-6.14721-40.53417h-174.37996c-15.36739 0-25.377353 9.86403-26.529231 24.40691-1.347454 17.01188 12.898965 29.26057 24.079277 29.26057l108.88549-0.31169c15.39369-0.29126 25.76543 13.96355 25.51208 23.65562-0.35222 13.47548-12.32231 21.70386-27.93252 22.94579h-87.413524c-41.901488 7.26733-30.856531 51.65531-5.464179 55.32488h79.587133c18.9645 0.1403 23.34205 14.53972 23.37356 23.63471 0.043 12.42866-10.43891 23.94955-25.25 23.49391h-127.50724c-30.808662 0.30153-22.393752 52.51941-2.796252 53.95885h159.82748c14.03838 0.93342 26.15192-1.34125 29.37-18.44164l10.24535-36.20024c16.64629-1.7571 39.14739 4.53617 42.34742-15.70953l19.80771-111.3328c1.43662-9.46666 10.16732-33.67525-12.29443-34.15117z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'TTCN 3';
-->
