<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Azure Pipelines';
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
    d="M0,384h42.6666679v85.3333435H128V512H0V384z M28.4439907,170.6666718h130.9245453L264.6651917,18.9583359C272.5806885,7.1249919,285.8956604,0,300.1510315,0h190.515625C502.4512024,0,512,9.5833178,512,21.333334v190.4998474c0,14.2502441-7.1167908,27.5835724-18.973877,35.5003662L341.3333435,352.6250916v130.9162598c0,15.7098389-12.734314,28.4586487-28.4441528,28.4586487h-99.5558624l-42.6666565-42.6666565L224,416l-42.6666718-42.6666565l-53.33461,53.333313L85.3320541,384l53.3346176-53.3333435L96,288l-53.3333321,53.3333435L0,298.6666565v-99.5417633C0,183.416748,12.7343788,170.6666718,28.4439907,170.6666718z M448,128c0-49.0845795-53.5018921-79.9290009-96.0722351-55.3867111s-42.570343,86.2311478,0,110.7734299S448,177.0845795,448,128z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Azure Pipelines';
-->
