<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Fancy';
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
    d="M242.2748413,0L66.0381165,98.2427216L0,341.5119019L101.9018402,512l173.1153107-95.180603l65.7870483-245.0799713L242.2748413,0z M177.9246826,164.1259003l-63.7584381-50.9958954l91.6190948-51.0737267L177.9246826,164.1259003z M241.0783691,71.1351318l49.4759521,86.2351837l-77.2027893,15.3433228L241.0783691,71.1351318z M91.9179535,141.9930267l75.55336,60.4293365l-27.1729431,99.5503845l-95.7743835,14.6087036L91.9179535,141.9930267z M102.213562,441.4989319l-53.0555115-88.7647705l80.6425934-12.3022156L102.213562,441.4989319z M164.8649902,350.3463745l62.2423401,51.2349548l-89.6869812,49.3092957L164.8649902,350.3463745z M249.1744995,372.5541382l-73.7913818-60.7415771l27.2463074-99.8178711l94.6955566-18.8210754L249.1744995,372.5541382z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Fancy';
-->
