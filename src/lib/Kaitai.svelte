<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Kaitai';
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
    d="M300.0395203,183.8360291l152.6645203-36.7593079c-25.5581055,133.4648438-12.9069824,205.2786865-100.3486328,301.2785034l-97.1160889-32.3720703L321.0996704,512C487.4248657,426.0466919,471.2559204,299.3322144,512,96.1698608l-189.0597229,33.9702148L337,99c11.420166-28.2341919,4.4724121-57.0808105-23-70L224,0c38.8407593,44.1257935,48.3792114,94.4304504,28.8041382,142.5577698l-93.5646362,17.2398987l-95.9998169-32.9301758l63.5115356,98.2323608l106.4622192-25.4838257L192,319L2.317688,509.6702881L0,512l225.425415-143.7376709L300.0395203,183.8360291z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Kaitai';
-->
