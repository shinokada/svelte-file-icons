<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Galen';
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
    d="m168.98525 0c-3.87912 0-7.52614 1.6482668-10.27325 4.3953783l-154.45871 154.48239c-2.742375 2.74237-4.2532863 6.3894-4.2532863 10.26851v165.92553c10.476915-20.3523 36.98654-48.11234 67.455795-78.71421l256.22972-256.3576zm-94.699567 262.49597c-43.546453 41.46244-69.544548 74.32358-69.752949 88.28174-0.033155 2.19769 0.6583594 3.14497 1.1793633 3.66598l150.93009 151.02955c5.02532 5.09637 45.39838-22.79155 92.70554-67.91996zm94.325387 249.48982 174.24265 0.01421c3.87911 3.3e-4 7.53087-1.51091 10.27325-4.25802l154.61501-154.61501c3.27285-3.5523 4.25802-5.88735 4.25802-10.26852l-0.30313-159.71137c-18.84613 27.48059-60.72537 66.81638-71.02704 76.33654l-181.3804 181.42303c-25.80864 24.84715-65.91173 60.96693-90.67836 71.07914zm264.98258-425.0634c-1.32146 0-2.56239 0.516268-3.49546 1.449338l-73.06369 73.286307c-1.91825 1.92297-1.91825 5.04426-5e-3 6.96724l80.59457 80.964c29.31831-27.54216 71.01756-70.94178 73.93992-85.79986 0.12315-0.62047-0.33155-1.16042-0.53048-1.35935l-73.9444-74.063073c-0.92833-0.933071-2.16927-1.444602-3.49546-1.444602z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Galen';
-->
