<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Dhall';
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
    d="M18.928566,506.8935547c-25.2380829-14.5500183-25.2380905-51.1226196-0.0000095-65.6726379c25.2380848-14.5500488,56.9569778,3.7362366,56.9569778,32.8363037C75.8855362,503.1573181,44.1666489,521.4436035,18.928566,506.8935547z M80.9205093,26.8772354l12.7458267,3.4135723c-7.129982,17.6853085-47.4400406,115.8137589-81.7173386,160.2216797c21.0910034,74.6148987,34.0452843,234.9663696,34.0452843,234.9663696l48.8669243-182.374939c-12.8000946-6.8487091-16.3882065-24.7191162-5.6165695-35.9238434c12.1615753-12.6505432,33.5792999-7.390274,38.4594574,9.4458466c4.410408,15.2153168-7.6492462,29.6615143-22.5905991,29.2130432L56.2428322,428.2238464c0,0,93.0985718-139.9368286,146.9645996-186.4605408c-5.0495453-58.3139191,7.0866852-160.9374237,9.3952026-179.6019592l12.6947021,3.3978233c17.4647369,4.6786652,24.5160828-21.6428261,7.0513458-26.3214874L87.9757767,0.5557501C70.5035095-4.1275401,63.448246,22.1939449,80.9205093,26.8772354z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Dhall';
-->
