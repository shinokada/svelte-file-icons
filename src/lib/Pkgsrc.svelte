<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'pkgsrc';
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
    d="M0,143.1842041l21.8933086,257.6644592L241.6915131,512l-2.551178-272.8204346L0,143.1842041z M294.7167053,235.7888489l191.9859009-114.5164337l-20.2091675,252.6142731L291.7557068,510.0211182L294.7167053,235.7888489z M262.7148132,186.9356689L458.0657043,77.4694443L227.3477478,0L21.891264,94.3103485L262.7148132,186.9356689z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'pkgsrc';
-->
