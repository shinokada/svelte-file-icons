<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'LiveScript';
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
    d="M512 397.539h-370.934l35.59-35.591h289.033v-31.454h-257.579l34.966-34.966h222.613v-31.454h-191.16l29.728-29.728h161.431v-31.454h-129.977l29.774-29.774h100.202v-31.454h-68.749l29.831-29.831h38.918v-31.454h-31.454v-31.454h-31.454v42.419l-29.826 29.826v-72.246h-31.454v103.699l-29.774 29.774v-133.474h-31.454v164.928l-29.728 29.728v-194.656h-31.454v226.11l-34.971 34.971v-261.081h-31.454v292.535l-31.219 31.219v-372.68h-62.907v397.539h-58.541v62.908h58.541v51.553h62.907v-51.553h390.551z"
  ></path></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'LiveScript';
-->
