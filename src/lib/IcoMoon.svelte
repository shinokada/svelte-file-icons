<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'IcoMoon';
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
    d="M127.7110596,34.453186c-170.2814331,98.1691284-170.2813721,344.9245605,0.000061,443.093689S512,452.3383179,512,256S297.9924927-63.7160034,127.7110596,34.453186z M189.697998,479.6409912C10.992981,371.1390991,25.4916382,128.7219238,189.6950073,32.3589478C350.8410645,126.9820557,372.8789673,367.6594849,189.697998,479.6409912z M248.2180176,256c0,45.4208984-49.5084839,73.9630737-88.9013672,51.2526245s-39.3928833-79.7947998,0-102.505249S248.2180176,210.5791016,248.2180176,256z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'IcoMoon';
-->
