<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Adobe Lightroom';
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
    d="M0,0v512h512V0H0z M261.5592041,363.9854126H128V107.0545044h41.8909302v218.2982178h98.4698486L261.5592041,363.9854126z M392.8436279,209.4545288c-14.6618042-0.6981812-39.0981445,1.1636353-47.2436523,4.654541v149.6436768h-42.1235962l0.2327271-150.807312c0.0405273-7.7401733-0.1672363-10.7467651-1.295166-24.7544556c16.7855225-6.6620483,51.557373-16.9037476,90.4296875-16.9037476V209.4545288z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Adobe Lightroom';
-->
