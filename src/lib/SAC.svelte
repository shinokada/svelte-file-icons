<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'SAC';
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
    d="M124.8018951,0l51.1848755,15.4520397L63.9594917,405.6160278l-29.9383278-8.6917725L124.8018951,0z M61.0405579,460.8151245l-45.5885162-14.0453796L0,497.9546204L45.5885162,512L61.0405579,460.8151245z M349.6028137,396.9242554l-29.938324,8.6917725L207.6371918,15.4520397L258.8220825,0L349.6028137,396.9242554z M338.0354614,512l45.588501-14.0453796l-15.4520264-51.1848755l-45.588501,14.0453796L338.0354614,512z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'SAC';
-->
