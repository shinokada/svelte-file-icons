<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'CoNLL';
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
    d="M509.9327393,266.3900757h-131.60495c-5.9674683-61.3923035-22.3638611-107.1105042-72.7527466-123.4450226v203.9967194c-36.7072449,13.427002-72.8560944,13.300415-108.3335876-3.1188049l-0.5064392-337.469574C433.0349731-3.8220108,499.6425171,125.9203033,509.9327393,266.3900757z M512,158.6903381V6.3534417H364.7123413C437.1415405,32.7981873,484.4305115,85.4616241,512,158.6903381z M509.9327393,289.4350891H378.1771545c-29.9971008,132.2294922-250.8034058,114.954071-249.9266663-23.5747986V6.3534417H0l1.0019569,269.5263977C35.7364655,577.4688721,457.9256592,583.8146362,509.9327393,289.4350891z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'CoNLL';
-->
