<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Stylable';
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
    d="m245.97627 416.18812c33.23942-24.57497 60.40737-54.07514 60.97452-96.33378-0.56715-42.26101-27.76953-70.32731-60.97452-95.02704-37.44083-40.31032-25.04127-97.18896 29.49984-97.89882 106.28381 12.38135 175.22609 129.03651 178.65029 192.92586-0.23663 71.14392-96.29818 165.1761-138.29567 183.11999-76.821 36.41094-121.73331-46.4538-69.85446-86.78621zm-107.0074-407.5665c-42.19793 17.95389-138.64307 110.38504-138.96887 183.22195 0.568186 75.2982 96.77094 165.27043 138.96887 183.22431 77.37899 45.93345 118.37308-63.54851 70.22406-94.28531-33.39806-24.58629-60.73188-46.65446-61.30174-88.939 0.56986-42.28217 27.90368-71.79452 61.30174-96.38318 67.04519-61.631-15.661-117.3861-70.22406-86.83877z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Stylable';
-->
