<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Conan';
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
    d="m222.69278 207.67676c-46.78805-2.90061-151.01306-62.96715-49.59934-121.07182 83.42593-47.798619 160.80205-14.282173 208.40806 36.791742 0 0-27.36983 16.85254-59.205 32.04036 22.49413-50.28595-61.30079-78.373784-109.35514-52.23971-48.05434 26.13407-52.77369 79.74171 65.47378 76.61825zm257.82516 146.70428v-235.02427l-245.13672-119.35677-235.38122 113.29896v226.71131l242.72663 171.98973zm-245.24171-342.4019 230.49298 115.78718-230.14651 131.23093-223.08712-137.94597zm230.49093 129.88283v202.59354l-91.86305 59.74085v-208.60726zm-106.96351 63.48107v209.26657l-116.10896 73.25124v-216.52125z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Conan';
-->
