<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Precision';
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
    d="M372.3959045,256.0000916c0,64.2837219-52.1122437,116.3959961-116.3959961,116.3959961s-116.3959961-52.1122742-116.3959961-116.3959961s52.1122742-116.3960114,116.3959961-116.3960114S372.3959045,191.7163544,372.3959045,256.0000916z M286.6302185,61.8252029c83.9060364,13.1853333,150.3594666,79.6383133,163.5448914,163.544281h61.8248291C497.9994812,107.6377335,404.361969,14.0008268,286.6302185,0.0003739V61.8252029z M61.8249054,225.3694763c13.1853333-83.9059601,79.6383209-150.3589478,163.5442657-163.544281V0.0003739C107.6374283,14.0008268,14.0005283,107.6377335,0.0000748,225.3694763H61.8249054z M450.1751709,286.6299133c-13.1851807,83.9065552-79.6387024,150.3597107-163.5449524,163.5448914V512C404.3622742,497.9995422,497.9998474,404.3623352,512,286.6299133H450.1751709z M225.3691711,450.1748047c-83.9061737-13.1851807-150.359314-79.6383362-163.544342-163.5448914H0C14.0000048,404.3623352,107.637207,497.9995422,225.3691711,512V450.1748047z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Precision';
-->
