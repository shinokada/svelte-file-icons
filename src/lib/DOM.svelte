<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'DOM';
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
    d="M362.7000122,347l-29.9000244-44.8500061L302.8999939,347l-42.6000061-28.3999939l37-55.5L256,235.5675049l-41.3000031,27.5325012l37,55.5L209.1000061,347l-29.9000092-44.8500061L149.3000031,347l-42.6000061-28.3999939l54.0400085-81.0600128l69.6599884-46.4399872V128h51.2000122v63.1000061l69.6600037,46.4399872l54.039978,81.0600128L362.7000122,347z M460.7999878,256c0-157.0706482-171.2059937-255.7728119-307.4311523-177.2374725S17.1437302,354.702179,153.3688812,433.2374878S460.7999878,413.0706787,460.7999878,256z M127.7111053,477.5468445c-170.2814331-98.1691284-170.2814941-344.92453-0.0000534-443.093689S512,59.6616783,512,256S297.9925537,575.7160034,127.7111053,477.5468445z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'DOM';
-->
