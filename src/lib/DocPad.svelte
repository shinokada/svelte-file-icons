<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'DocPad';
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
    d="m62.675789 231.30374c10.728011-6.18483 10.728011-21.73083 0-27.91566-10.728026-6.18482-24.210858 1.58818-24.210858 13.95783s13.482832 20.14265 24.210858 13.95783zm324.27559-87.07926v53.87952h18.84759v38.48667h-300.27358c-13.643968 36.37261-61.335268 47.60545-89.61281 19.32789-29.583062-29.58305-15.927243-80.41834 24.521239-91.28378 28.706953-7.71133 55.745264 8.78699 65.152441 33.46922h188.99893v-53.87952h30.66621v30.85788h30.85788v-30.85788zm62.37283 136.47178c-10.728 6.18482-10.728 21.73082 0 27.91565 10.72802 6.18482 24.21086-1.58818 24.21086-13.95783s-13.48284-20.14265-24.21086-13.95782zm-324.27558 87.07926v-53.87953h-18.84759v-38.48667h300.27358c13.64398-36.37261 61.33527-47.60545 89.61282-19.32789 29.58306 29.58305 15.92724 80.41834-24.52124 91.28377-28.70695 7.71135-55.74527-8.78697-65.15244-33.46921h-188.99893v53.87953h-30.66622v-30.85788h-30.85787v30.85788z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'DocPad';
-->
