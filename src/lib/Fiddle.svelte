<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Fiddle';
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
    d="M127.711113,477.5468445c-170.2814331-98.1691284-170.2814941-344.92453-0.000061-443.093689S512,59.6616783,512,256S297.9925537,575.7160034,127.711113,477.5468445z M221.2038879,307.5879822v-61.5297241h61.7808533c17.0086975-0.0000153,17.0086975-29.8252563,0-29.8252411h-61.7808533v-74.5631104h134.2135925c19.7897644,0,19.7897644-29.8252487,0-29.8252487H206.2912598c-8.2360077,0-14.9126129,6.6766129-14.9126129,14.9126205v180.8307037C123,328,137,423,206.2912598,425.0097046C275,425,290,327,221.2038879,307.5879822z M191.3450165,391.1705017c-19.838623-11.4371948-19.838623-40.1853943,0-51.6225891s44.7715302,2.9369202,44.7715302,25.8112793C236.1165466,388.2335815,211.1836395,402.607666,191.3450165,391.1705017z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Fiddle';
-->
