<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Audacity';
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
    d="M512,341.3069458c0,70.6560059-40.1978149,128-92,128v-264.25c0-33.1523438-17.1593628-63.6638184-46.625-86.625c-66.8639526-51.1365356-171.5027466-49.1187134-234.75,0C109.1593628,141.3931274,92,171.9046021,92,205.0569458v264.25c-51.8021851,0-92-57.3439941-92-128c0-55.1999512,24.5648193-102.2960815,60-120.25v-16c0-44.2694702,23.1846313-84.0631714,58.875-111.875c70.125-55.4624634,192.4287109-63.0533447,274.25,0c35.6903687,27.8118286,58.875,67.6055298,58.875,111.875v16C487.4351807,239.0108643,512,286.1069946,512,341.3069458z M388,343.9736328l-8,21.333313l-4-68l-8,52l-8-16l-4-56l-20,76l-4-16l-12-120l-12,104l-8,32l-16-108l-16,92l-8,24l-4-165.21875l-24,185.21875l-24-168l-12,144l-8-16l-8-96l-4,96l-12,28l-8-96l-8,76l-12-20v56l-12-45v-115c-4-4-12-8-20-8v252c8,0,16-4,20-12v-56l4,4l12,40l4-48l12,60v-76l8,20l12,56v-76l8,8l12,68l12-92l26.4627075,103.678833L236,405.3069458l8-24l8,100l24-100l8,84l20-88l20,96l4-72l12-24l4,92l20-88l12,40l4-36l8,16v56c4,8,12,12,20,12v-252c-8,0-16,4-20,8V343.9736328z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Audacity';
-->
