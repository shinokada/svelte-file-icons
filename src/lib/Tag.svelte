<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Tag';
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
    d="M219.4285736,0H73.1428604L0,73.1428604v146.2857056L292.5714417,512L512,292.5714417L219.4285736,0z M36.5714302,201.1428528V91.4285736l54.8571434-54.8571434h109.7142792l256,256L292.5714417,457.1428528L36.5714302,201.1428528z M256,146.2857208L146.2857208,256l146.2857208,146.2857056l109.7142639-109.7142639L256,146.2857208z M201.1428528,256L256,201.1428528l91.4285583,91.4285889l-54.8571167,54.8571167L201.1428528,256z M118.8366165,143.824585c-12.1628189-7.0119934-12.1628189-24.6371765-0.0000076-31.6491699c12.1628265-7.0120087,27.4488983,1.8005829,27.4488983,15.824585S130.9994354,150.8365936,118.8366165,143.824585z M182.8569946,128c0-42.0723877-45.8586273-68.5103912-82.3474121-47.4741974s-36.4887772,73.9122162,0.0000153,94.9483948S182.8569946,170.0723877,182.8569946,128z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Tag';
-->
