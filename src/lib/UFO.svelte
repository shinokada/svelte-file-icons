<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'UFO';
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
    d="M512,101.1338196v-9.9582672h-53.7655945V38.77145h-9.958252v52.4041023H56.5841751V38.77145h-9.958271v52.4041023H0v9.9582672h46.6259041v96.2632751H0v9.9582825h46.6259041v209.1236877H0v9.958252h46.6259041v46.7912292h9.958271v-46.7912292H193.740036c37.6626129,13.5913391,81.531723,13.5913391,119.1943512,0h135.3417664v46.7912292h9.958252v-46.7912292H512v-9.958252h-53.7655945V207.3553772H512v-9.9582825h-53.7655945v-96.2632751H512z M216.3797455,312.9705505V207.3553772h77.620285v105.6151733C294.0000305,371.021759,216.3797455,371.021759,216.3797455,312.9705505z M216.3797455,197.3970947v-96.2632751h77.620285v96.2632751H216.3797455z M56.5841751,101.1338196h49.0582428v96.2632751H56.5841751V101.1338196z M56.5841751,416.4790649V207.3553772h49.0582428v95.5025024c0,54.569519,27.6489334,92.4403076,66.0257034,113.6211853H56.5841751z M448.2761536,416.4790649H335.0062866c38.3768005-21.1808777,66.0257263-59.0516663,66.0257263-113.6211853v-95.5025024h47.2441406V416.4790649z M448.2761536,197.3970947h-47.2442627v-96.2632751h47.2442627V197.3970947z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'UFO';
-->
