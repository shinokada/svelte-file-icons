<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Apollo';
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
    d="M252.1716766,187.2693481l-30.1033478,84.5343933h46.2051392l12.7763977,36.7540894h-70.1828003l-12.0763245,33.2536926h-46.5551453l74.3832245-196.5468292h51.4557343l74.208252,196.7218475h-46.5551453L252.1716766,187.2693481z M444.8663025,419.6935425c10.0368347-12.6801453-6.7891541-25.954834-16.1339722-13.8540649C284.4270935,587.6938477-22.5081558,458.7810059,27.5050182,201.3772736C67.0100098,32.3645744,266.9595642-33.6902847,396.5697327,73.1152496c-4.0494385,11.3765335-0.2776489,25.1802368,11.3399353,32.0136795c17.2296448,10.1343918,38.883606-2.6024399,38.883606-22.8712234c0-18.9257622-18.8786316-31.277935-35.4072571-24.5821724C270.034668-60.5227699,50.5629196,11.4086866,7.3191705,196.4168701C-51.5274887,443.7132874,258.1980591,632.3389282,444.8663025,419.6935425z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Apollo';
-->
