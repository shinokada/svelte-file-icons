<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Noon';
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
    d="M127.7110443,34.4531364c-170.2814331,98.1691895-170.2813721,344.9245605,0.000061,443.093689S512,452.3383179,512,256S297.9924927-63.715992,127.7110443,34.4531364z M286.6621094,254.249588c0,45.2265472-62.6964264,45.2265472-62.6964264,0c0-21.9658203,0-165.0958862,0-188.6513672c0-43.3306885,62.6964264-43.3306885,62.6964264,0C286.6621094,89.5749664,286.6621094,221.5410919,286.6621094,254.249588z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Noon';
-->
