<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'ZorinOS';
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
    d="M128.3181305,28.904211L92.5500107,91.6016006h327.1063232L384.3009338,28.904211H128.3181305z M48.2869606,169.3972626L0,254.6560822l44.9852905,79.9279938h17.3681717l245.4931335-165.1868134H48.2869606z M447.3078613,169.3972626L201.7803497,334.5840759h265.3719482L512,255.3439178l-48.3557434-85.9466553H447.3078613z M88.9388046,412.3797302l38.7946548,68.7160645h255.9827881l39.2073669-68.7160645H88.9388046z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'ZorinOS';
-->
