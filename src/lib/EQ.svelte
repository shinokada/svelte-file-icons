<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'EQ';
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
    d="M41.9608917,188.5983734c11.1418457-104.3042221,156.881485-96.2215347,160.7410278,0H41.9608917z M245.5094757,229.6727753c4.6950836-82.5130768-25.1683197-130.0591278-79.1311493-151.4989624C84.541832,48.7532578,0,107.9325333,0,193.4888611c0,43.5800629,32.8022308,120.7257385,122.7547379,120.7257385h122.4165726v-42.2709045H114.3005524c-27.7440186-3.0107117-49.2403641-17.6221466-61.5464516-42.2709198H245.5094757z M479.2247009,108.8060913c-63.7449036-68.7826691-177.8209534-42.5278473-204.8441467,47.1452332c-23.7797852,78.9102173,35.4064026,155.3057861,111.806488,158.276062V272.814209c-45.7182007-2.5031128-83.7677307-44.6000519-75.4876404-94.4538116c10.2198792-61.5328445,83.421814-89.1420517,131.4472351-49.5772095c31.817749,26.2124023,36.9090271,68.9985046,19.789917,101.2832489v61.3613281C518.1287231,250.668808,531.3555908,165.0569458,479.2247009,108.8060913z M443.4777527,200.8465118h-42.3591614V442.182251h42.3591614V200.8465118z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'EQ';
-->
