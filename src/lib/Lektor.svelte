<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Lektor';
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
    d="m0 0v512h29.525391c41.139166-27.294338 84.641001-54.706083 144.09375-77.650391 0 0-94.818847-31.518842-79.318359-145.91406 14.161143-104.51071 124.50438-224.641 217.33789-214.95508 81.833946 8.5382657 95.909712 118.12861 77.771484 203.75977-19.552851 92.309638-75.78125 137.1582-75.78125 137.1582 27.489365 5.2705098 53.8389 14.091658 73.349609 44.21875-1.9163056 10.352224-7.5131182 14.587993-10.587891 19.4375-56.957544-72.675846-201.62345-21.273551-291.5 33.945312h427.10938v-512z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Lektor';
-->
