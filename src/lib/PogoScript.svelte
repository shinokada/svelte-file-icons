<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'PogoScript';
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
    d="M285.1395264,0v28.9453392h-95.3872681V18.6174393h-25.7407227v329.6552734h-42.8824997V18.6174393H95.3867569v10.3278999H0V0h95.3867569v7.8969436h94.3655014V0H285.1395264z M190.2756958,358.4435425H94.8638229v-20.368927H5.8837051v21.440979h17.1528015v20.3689575h105.0608444v99.953949h-8.3073196V512h45.5594864v-32.161499h-8.3063049v-99.953949h105.0598145v-20.3689575h17.1528015v-21.440979h-88.9801331V358.4435425z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'PogoScript';
-->
