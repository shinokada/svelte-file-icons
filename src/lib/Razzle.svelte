<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Razzle';
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
    d="M0,511.7365417V0h246.7214661c48.3315125,0,65.3204346,16.9638615,88.3414001,39.0374527c36.1427612,34.6554108,39.5141602,55.1210861,40.2296143,73.1509247v81.6457443c0.2156677,51.8269348-29.1366272,78.2802582-82.4874573,115.3140717L402.2271729,512H289.2745361L187,315.6881714h-80.4301071v196.0483704H0z M250.4747925,216.1559143c7.9294128,0,21.2787781-16.0755768,21.2787781-22.7984314v-60.8526154c0-13.2312775-10.9768372-32.521843-30.2432098-32.7900238l-134.9404602,0.0000076v116.4410629H250.4747925z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Razzle';
-->
