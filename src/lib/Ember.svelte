<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Ember';
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
    d="M246.8830414,263.451416c3.2333069-129.2771301,86.5729218-185.7776489,115.4534149-157.5547791c28.8804626,28.2776489,18.1941528,89.1075134-36.3334961,127.1398315C271.4753113,271.0413818,246.8830414,263.451416,246.8830414,263.451416z M506.6292114,437.3919067L512,312.3892212c-151.2392273,109.1615906-256.8705444,97.9582825-252.3068542,34.9908752c0,0,270.4461975-94.0944519,196.7379761-279.8721008C423.2761536,19.7209568,384.8053284,4.7052927,330.2776794,5.8012991c-94.4571228,1.2203393-180.6953735,100.2590866-198.8204041,262.0067444c0,0-47.3486481,9.8094788-72.9958191-11.919342s-38.8543777,0-38.8543777,0s-44.0059662,57.0212097-0.1646347,74.3933716c43.7865295,17.3721313,112.1790009,25.4827576,112.1790009,25.4827576C171.243042,500.0575867,278.5629578,566.2762451,506.6292114,437.3919067z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Ember';
-->
