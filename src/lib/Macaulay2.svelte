<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Macaulay2';
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
    d="M77.0280304,206.4742279c34.4649734,57.8705902,93.6657715,138.3953705,135.7024384,184.6650238C124.4566727,392.2886047,38.6877556,304.2877808,77.0280304,206.4742279z M170.3810425,131.2865448C-8.8047295-75.6217651-60.6287804-25.4251041,82.5952759,194.1239166c33.4075775,57.6424561,99.9001617,148.8634186,144.3948517,196.1430817c201.2131195,217.1824036,194.3870697,111.8300781,84.6003571-67.1939087C347.2705383,217.6387787,262.0665894,120.0092545,170.3810425,131.2865448z M267.2359314,376.6057739c9.6824341-5.6552429,18.2391052-13.0509644,25.6625671-21.7206726c36.5872192,82.3918152,37.0329895,110.0794678-35.661499,26.9910889c-3.3096008-4.1063843-122.0066833-151.6378937-150.4718323-219.0406494c-50.7977905-93.3760223-35.9732208-94.1034088,30.8514099-21.3344727c-8.1752167,4.0898132-15.5682068,8.630127-22.0293732,13.7055664C145.1889648,219.0530701,213.1576538,310.6553345,267.2359314,376.6057739z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Macaulay2';
-->
