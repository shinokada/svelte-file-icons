<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Ansible Alt';
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
    d="M242.2801361,99.7152863L367.7326355,396.881134L178.7697449,254.1788025L242.2801361,99.7152863z M464.9584351,465.8799133L272.0751038,19.7394505c-10.9573669-26.1266441-49.0272217-26.5111885-60.3739777,0L0,508.2203369h72.1351776l83.896347-201.5082092l250.1209106,194.4512939C434.5034485,527.9057007,480.6419373,500.9562683,464.9584351,465.8799133z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Ansible Alt';
-->
