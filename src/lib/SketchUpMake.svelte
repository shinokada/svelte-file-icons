<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'SketchUp Make';
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
    d="M313.7752991,0l160.9862061,125.1442261l-34.2261963,292.7048035L109.8429337,512l-63.310955-197.9152222L0,40.2996559L313.7752991,0z M52.9093475,108.8120575l196.4107208-28.3532562l70.5799255,72.6692352l115.3336487-20.451828L305.1574097,31.5526047L34.9396935,66.3291855L52.9093475,108.8120575z M66.2499847,191.593399l18.2763672,48.0430908l99.7048492-19.1069946l25.9850922,44.5458221l108.6692352-23.2527771l-67.2267914-82.7911377L66.2499847,191.593399z M98.2359695,329.7226562l17.9650497,51.9004211l100.1265106-25.0856934l-24.5450592-48.2250671L98.2359695,329.7226562z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'SketchUp Make';
-->
