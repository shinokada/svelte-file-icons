<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'P4';
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
    d="M472.666687,417.3493347v-95.2472534h38.9524536v-54.666687H472.666687V61.1020203H406L244.6668091,268.1017761v54.0003052H410v95.2472534H92V278.1020813c121.350647,3.1983643,167.8237915-45.821228,170.7879028-114.5863647c3.5088501-81.4011841-42.0686646-102.4138184-106.7889404-102.4138184H18.9998169v356.2474365H0v33.5487671h512v-33.5487671H472.666687z M303.5282593,267.4353943L410,133.1021423v134.333252H303.5282593z M92,111.1019592c0,0,95.6127319-11.6251221,95.6127319,45.6479492C187.6127319,238.1092224,92,228.3576355,92,228.3576355V111.1019592z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'P4';
-->
