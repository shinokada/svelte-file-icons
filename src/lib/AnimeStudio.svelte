<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'AnimeStudio';
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
    fill-rule="evenodd"
    clip-rule="evenodd"
    d="M368.2557678,214.5733185L265.6288147,401.9238892c40.5541992,71.8433533,73.6471558,97.0682983,138.6643677,94.5018005c63.6698608-2.5133362,136.9735413-89.1266785,95.6938171-163.2424316l-102.782074-182.2437592C393.5289307,163.2050781,372.0454712,206.6868439,368.2557678,214.5733185z M216.3929291,440.6246338C104.0771179,583.6759644-57.957058,425.7925415,20.8495884,302.891571c0,0,83.8956604-147.023407,116.5215836-204.3021851c25.3006744-44.4180565,53.6435394-72.3709183,90.4965973-81.3305893c44.9396973-10.9257898,97.5647888,12.8342228,125.6207581,56.1669464c19.4969482,30.1131897,36.7513123,57.6765366,6.3420715,109.7378922C356.2180176,189.3484955,223.5054321,431.5657959,216.3929291,440.6246338z M224.4067993,176.029892c-30.695343-17.6962128-30.6953583-62.1769409-0.0000153-79.8731537s69.2728729,4.5441513,69.2728729,39.9365692S255.1021423,193.7261047,224.4067993,176.029892z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'AnimeStudio';
-->
