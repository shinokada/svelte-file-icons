<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Figma';
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
    d="M83.2986298,0h82.9648285v165.9301453H83.2986298C-26.1098289,161.6531982-27.214653,4.4919472,83.2986298,0z M83.2986298,338.9571228h82.9648285V173.0269623H83.2986298C-27.214653,177.5189056-26.1098289,334.6801758,83.2986298,338.9571228z M256.325592,0h-82.9653168v165.9301453h82.9653168C367.2076111,159.9959717,365.8265991,3.3871226,256.325592,0z M166.2634583,429.0197449v-82.9658203H83.2986298c-67.7013397,0-110.5132828,79.3760681-63.4286613,136.3884583C64.7619705,538.9506836,166.2634583,510.7776794,166.2634583,429.0197449z M339.4597168,255.9922791c0-63.7594299-69.4973755-103.8254242-124.7950287-71.9457092s-55.2976227,112.0117188,0.0000305,143.891449S339.4597168,319.751709,339.4597168,255.9922791z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Figma';
-->
