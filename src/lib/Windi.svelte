<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Windi';
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
    d="M72.646759,76.6433105h51.4982452c2.2159424-31.1361389,47.3488617-33.1036491,63.0417175-10.6371994c17.231308,24.6689301,7.8761597,62.6742477-46.9725952,62.1359787H0v51.4982452h140.2141266c66.1551361,0,106.2397461-40.4260101,106.2397461-90.1219406C243.8975067-23.3599319,78.3110733-31.5269585,72.646759,76.6433105z M254.4627991,383.2538452l-155.5922546,0.0000305v-51.4982605h155.5922546C399.8953552,333.2835083,387.0756531,507.8495483,270.5801086,512c-52.3737946,0-83.6851807-39.2655029-83.6851807-77.247406h51.4987793c0,10.6857605,9.9906464,25.7511902,32.1864014,25.7511902C320.1611938,457.7727356,329.4421997,383.2538452,254.4627991,383.2538452z M277.3290405,178.848877h45.6115112c-2.2817993-60.9089661,99.7302246-69.0917435,97.3947754,0c0,28.2347412-19.9730835,51.4982605-74.3275757,51.4982605H0v51.4987488h353.6968079c80.4942322,0,117.8989563-51.7366028,117.8989563-102.9970093C471.5957642,45.8636093,277.3290405,45.9768791,277.3290405,178.848877z M67.5104752,331.7556152H0v51.9308777h67.5104752V331.7556152z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Windi';
-->
