<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'YAML Alt2';
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
    d="M0,141.243576h68.9042587l84.7585983,84.6282196l84.6490479-84.6282196h69.1456757L77.3356934,370.7564392H8.7558489l110.6934967-110.6711121L0,141.243576z M98.0202484,370.7564392H138.24646l80.2744446-80.1856995l-0.0641479,80.1856995h29.0827789l0.0079956-120.903183h-29.2030334L98.0202484,370.7564392z M259.3765869,370.7564392h26.06427l-0.0881958-76.6776123l40.2042847,40.3406067l40.1000671-40.260437l0.0160217,76.5974426h26.0482483v-120.903183h-25.8076782l-40.3165588,40.2163544l-40.2684631-40.2163544h-25.9760437L259.3765869,370.7564392z M427.4298706,347.8139648l0.0160217-97.9607086h-22.4836121v120.903183H512l-22.2009277-22.984314L427.4298706,347.8139648z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'YAML Alt2';
-->
