<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'ReasonStudios';
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
    d="M430.5455017,109.3818283L253.6727448,6.9818182c-16.2909088-9.3090906-34.9090881-9.3090906-51.1999969,0L25.5999985,109.3818283C9.3090878,118.690918,0,134.981842,0,153.6000061v204.8000183c0,18.6181641,9.3090935,34.9090881,25.6000042,44.2181702l176.8727264,102.3999939c16.2908936,9.309082,34.9090881,9.309082,51.1999969,0l176.8727112-102.3999939C446.8363647,393.3091125,456,377.0181885,456,358.4000244V153.6000061C456,134.981842,446.8363647,118.690918,430.5455017,109.3818283z M228.0727386,256.0000305v169.8908997L81.4545441,339.7818298V169.8909302l146.6181946-83.7818298l146.6181793,83.7817993L228.0727386,256.0000305z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'ReasonStudios';
-->
