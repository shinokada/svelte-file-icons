<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Analytica';
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
    d="M296.8787537,205.6815338v-41.2137604H351v287.6144714h-54.1212463v-46.4582825c0,0-22.6627502,52.3526001-99.1277008,53.4664917c-68.5886841,0.9991455-151.6952057-43.9163513-152.6043396-149.9104309c-0.8853416-103.2202606,77.7492065-150.576889,148.6973724-151.3955536C238.4416199,157.2698517,279.9902344,178.1660309,296.8787537,205.6815338z M297.0997009,308.7417908c0-79.0020447-82.7984009-128.6463928-148.6794128-89.1453705s-65.8809814,138.7897186,0.0000305,178.2907257S297.0997009,387.7438354,297.0997009,308.7417908z M408.16922,104.4339981V512L512,327.0950317V0H188.7975922L0,104.4339981H408.16922z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Analytica';
-->
