<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Brotli Old';
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
    d="M374,250.6978302H95.622963V96.4329453H374V250.6978302z M44.1740341,469.5875549h36.0153046V344.5621033l-36.0153046-36.0153198V469.5875549z M327.3062134,48.0712509H44.1740341v160.8293762l36.0153046,37.7303009V80.9993286h247.1168823V48.0712509z M95.622963,346.3862915V512H374V346.3862915H95.622963z M28.7404118,192.7320709V32.6376266H290.848877V0H0v162.6230621L28.7404118,192.7320709z M28.7404118,293.1131592L0,264.3727417v162.8024292h28.7404118V293.1131592z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Brotli Old';
-->
