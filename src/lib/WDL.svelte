<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'WDL';
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
    d="M83.7724609,192.0275421l-82.934761-48.3787842V47.6349945L84.6335373,0l82.934761,48.3787766v68.3380737l66.2089539,41.3098679l-35.1800995,22.6158295l-45.1496277-28.4277954L83.7724609,192.0275421z M0,367.6078491v96.0137634L82.934761,512l83.795845-47.6349792v-96.0133972l-82.9347687-48.3787537L0,367.6078491z M272.2613831,162.4993134l-83.6852875,47.6349945v71.4637756l-61.1772232,36.414856l34.3427963,23.4535522l41.8416443-26.5l67.8173828,39.5603638l83.7954407-47.635376v-96.013382L272.2613831,162.4993134z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'WDL';
-->
