<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'VCL';
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
    d="M278.5473633,160.8342743c22.6579895,62.0027924,91.5752563,93.7904816,153.5513611,71.2248383c62.0746155-22.7499847,93.9303284-91.4926147,71.1994324-153.5449829C480.5259399,16.4808159,411.805542-15.3971491,349.730896,7.3337784C287.7134705,30.1759567,255.9088135,98.8847733,278.5473633,160.8342743z M127.2668839,383.5334473c-23.3766632,41.5991516-8.3635864,94.3292236,33.4178391,117.5305176c41.6542969,23.201355,94.3943634,8.2635193,117.6179199-33.2446289c23.2839661-41.6765442,8.409668-94.3212585-33.2668762-117.6210632C203.2575226,327.0255737,150.693222,341.8459473,127.2668839,383.5334473z M2.3151288,216.3616791c-5.3398352,27.015152,12.3952198,53.3344269,39.4104424,58.737442c27.1105652,5.4030457,53.4202194-12.2966919,58.7406235-39.4040833c5.3617325-27.1105652-12.2744446-53.4392853-39.4040794-58.7819519C33.9642563,171.6085968,7.717813,189.0285645,2.3151288,216.3616791z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'VCL';
-->
