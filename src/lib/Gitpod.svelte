<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Gitpod';
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
    d="M221.9950256,0L444,128.0707092V384.043396L221.9950256,512L0,384.0186157V128.0310059L221.9950256,0z M399.8241577,358.7349548V205.1969757l-134.0107422,76.2727509v51.3860779l89.3487549-50.84021v50.8153992l-133.1671448,76.223114L88.9767914,332.8558044V179.3178406l133.0430603-76.7689667l133.0182648,76.6697388l44.7860413-25.7922974L221.9950256,50.9890938L44.3148079,153.5131531v205.2218018l177.6802216,101.7796936L399.8241577,358.7349548z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Gitpod';
-->
