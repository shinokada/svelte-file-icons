<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Adobe PremiereRush';
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
    d="M0,512V0h512v512H0z M418.1682129,353.3242493c-19.5579529,7.4506531-41.2114563,15.1341553-68.6857605,15.1341553c-33.7608032,0-66.1245728-13.0386658-66.1245728-64.9604187v-119.676239h40.51297v115.0195312c0,31.8164978,22.1403503,39.9255066,54.4829407,29.5697937v-144.589325h40.2801514V327.712616C419.4110718,351.2250366,421.3855591,352.5413818,418.1682129,353.3242493z M243.3105927,188.245575c0-46.1009674-31.8981323-69.6171036-84.9840851-69.6171036c-27.4743195,0-64.960434,1.1641693-64.960434,1.1641693v245.4060974h39.8144531v-98.9541016h25.8444672l53.2577209,98.9542236l45.397583-0.0001221l-60.7034912-110.1300507C218.1645966,247.1523285,243.3105927,226.1973572,243.3105927,188.245575z M133.1805267,153.0877838v77.3005829h22.5848236c27.0086365,0,46.7994385-10.7103271,46.7994385-38.6502991C201.1557617,159.0371552,181.1273346,149.022934,133.1805267,153.0877838z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Adobe PremiereRush';
-->
