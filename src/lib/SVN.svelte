<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'SVN';
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
    d="M512,200.0933685c-146.9875793,8.5526123-366.7861328,48.0585327-380.4385376,18.2526093C127.2781906,181.9617615,363.6549072,117.2095871,512,97.8423233V200.0933685z M0,299.653717v110.6071167c161.4634705-19.0578308,423.4024963-90.8175659,409.5231934-126.9024658C394.8293457,248.4908447,144.984024,294.1217651,0,299.653717z M493.867218,69.2428131H0v134.7196045C122.2290573,154.176178,329.9000244,100.0858307,493.867218,69.2428131z M26.0763874,442.7572021H512V309.1186523C372.0431213,365.0122681,153.2159271,422.120697,26.0763874,442.7572021z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'SVN';
-->
