<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'ANTLR';
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
    d="M256,0C114.6151123,0,0,114.6151123,0,256s114.6151123,256,256,256s256-114.6151123,256-256S397.3848877,0,256,0z M394.1992188,389.8251953c-5.6125488,2.5087891-14.0546265,3.6921387-19.930542,0.7542114l-160.4898071-88.9425659l113.7612305,0.2925415l-70.9551392-158.7877808L152.8549805,377.1318359C147.375,390.125,135.2155151,395.4790039,121.125,390.75c-18.25-6.125-19.5756836-21.2597656-13.9799805-33.8818359L222.2006836,97.3295898c0.0229492-0.0512695,0.0454102-0.1020508,0.0683594-0.152832c6.1655273-13.6601562,19.840332-22.3583984,34.8168945-22.1289062c14.8505859,0.215332,28.1533203,9.1328125,34.0048828,22.7568359l115.734375,258.9960938C412.4580078,369.40625,406.8056641,384.1914062,394.1992188,389.8251953z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'ANTLR';
-->
