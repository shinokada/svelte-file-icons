<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'NumPy Old';
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
    d="M246.7727661,245.7584991l-96.8770447-10.6429596v-96.8770447l96.8770447,10.6429596V245.7584991z M265.2255554,363.1155396l96.8792725,10.643219v-96.8770447l-96.8792725-10.643219V363.1155396z M131.4429474,348.4181213v-96.8770294L25.3403683,239.884613v96.8770447L131.4429474,348.4181213z M380.5576172,145.1263428l106.1020203,11.6564178V50.6807365l-106.1020203-11.656414V145.1263428z M131.4429474,136.2112732L25.3403683,124.5547943v96.8770447l106.1025772,11.6564789V136.2112732z M380.5576172,394.238739v106.1048584L486.6596375,512V405.8951721L380.5576172,394.238739z M131.4429474,117.7584991V11.656477L25.3403683,0v106.1020203L131.4429474,117.7584991z M131.4429474,366.8709106L25.3403683,355.2144165v106.1048584l106.1025772,11.6564636V366.8709106z M486.6596375,290.5653381l-106.1020203-11.6564026v96.8770447l106.1020203,11.6564026V290.5653381z M380.5576172,163.5791168v96.8770294l106.1020203,11.6564331v-96.8770447L380.5576172,163.5791168z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'NumPy Old';
-->
