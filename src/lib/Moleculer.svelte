<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Moleculer';
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
    d="M177.2494049,263.4219971l-60.2089996,22.0276184c-21.8172226-34.9677277-73.4488678-40.6597595-101.8991547-7.3166809c-31.5608063,36.9886475-11.1207304,94.5075684,36.703949,103.2855225c45.1600037,8.2888794,83.0350037-32.7007141,73.4224396-75.828949l57.7795258-25.364563c19.9478302,41.1204224,74.5525055,55.9733276,112.6977386,26.6079407l48.4717102,46.1405334c-36.165802,52.3244934-8.3927612,127.5389404,56.3424683,141.5109558c68.9119568,14.8734741,128.4867554-50.7094727,106.9773865-117.7660522c-20.0609436-62.540863-96.7427673-83.0016174-145.436676-43.1401367l-51.5568237-41.7801819c24.9373779-33.7103577,16.4196777-82.42836-17.9443054-105.947876l25.6650696-61.6500244c36.8445435,7.7111359,71.9315796-24.2548828,65.387207-63.0148659c-7.0238342-41.599411-56.7806702-60.0842628-89.3474121-33.1929398c-30.6661682,25.3221111-24.6180725,73.1459274,9.2471313,90.9231415l-30.2838745,57.4536743C218.8892059,159.4778595,165.7509766,204.2189331,177.2494049,263.4219971z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Moleculer';
-->
