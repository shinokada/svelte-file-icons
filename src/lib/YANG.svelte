<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'YANG';
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
    d="M256,0C114.6151276,0,0,114.6151276,0,256s114.6151276,256,256,256s256-114.6151123,256-256S397.3848877,0,256,0z M23.7894344,256c0-124.8869019,101.2408676-226.1277771,226.1277771-226.1277771c62.4434509,0,113.0639343,50.6204033,113.0639343,113.063858S312.3606567,256,249.9172058,256v0.1492004c-66.3367157,3.1731873-119.146637,57.9576111-119.146637,125.0802307c0,32.0433044,12.0409241,61.2701721,31.8372498,83.4180908C81.0715637,430.4877625,23.7894344,349.936554,23.7894344,256z M256,97.5238113c18.3616638,0,33.2467651,14.8850784,33.2467651,33.2467575S274.3616638,164.0173187,256,164.0173187s-33.2467499-14.8850861-33.2467499-33.2467499S237.6383209,97.5238113,256,97.5238113z M256,347.9826965c18.3616638,0,33.2467651,14.8850708,33.2467651,33.2467346c0,18.3616943-14.8851013,33.2467651-33.2467651,33.2467651s-33.2467499-14.8850708-33.2467499-33.2467651C222.7532501,362.8677673,237.6383209,347.9826965,256,347.9826965z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'YANG';
-->
