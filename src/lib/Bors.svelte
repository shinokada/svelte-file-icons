<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Bors';
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
    d="M416.8676758,312.4821167H284.0777283c42.48703-32.0568237,35.2312317-87.4985657-1.9818115-112.9704742h134.771759C490.3536072,203.6092682,491.8284302,308.5311584,416.8676758,312.4821167z M63.4221344,199.5116425h144.0222168c-37.3805389,25.3323364-43.4914703,82.7314606-1.3209991,112.9704742H63.4221344C-12.412528,309.1796875-10.3579712,202.4508667,63.4221344,199.5116425z M279.4544983,229.2422028c0,17.4803925-19.0535278,28.4649506-34.2140198,19.724762c-15.1605072-8.7401886-15.1605072-30.7093353,0-39.4495239C260.4009705,200.7772369,279.4544983,211.761795,279.4544983,229.2422028z M479.6289978,256c0-196.3383179-200.4769592-319.7160034-359.9924316-221.5468445s-159.5154114,344.9245605,0.000061,443.093689S479.6289978,452.3383179,479.6289978,256z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Bors';
-->
