<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'MetaPost';
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
    d="M0.0012387,479.331604V31.9249763C-0.2240519,12.4753151,30.333952-3.2920563,50.1287346,21.450573l205.7471924,357.8754272L461.8724976,21.450573C474.8565063,0.719696,510.0669861,6.4058599,512,32.6731491V479.331604c0,31.8339233-52.6213989,31.8339233-52.6213989,0V130.4342346L279.8174133,442.9205933c-17.1860046,19.223999-38.1710205,15.0771179-47.6335907,0L52.3732491,130.4342346V479.331604C52.3732491,511.2131348,0.0012387,511.2131348,0.0012387,479.331604z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'MetaPost';
-->
