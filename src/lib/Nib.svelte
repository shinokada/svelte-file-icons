<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Nib';
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
    d="M374.8808899,0l135.3553162,135.3553467l-37.0083008,37.0083008L337.8725586,37.0083046L374.8808899,0z M0,492.7574463l224.5461884-224.5460815c-12.1176453-22.3448639-2.2072754-52.4089355,24.0615082-61.3469238c31.3722534-10.6744537,62.7386475,16.7241821,56.3242188,49.1992188c-5.6690369,28.7012329-37.1195984,42.4955444-61.5826263,30.2688599L17.6817017,512c178.7567596-95.7687378,314.0171204-121.6820984,376.4031677-114.301178c5.2608643-43.7807312,10.4483948-180.8328247,52.3094482-222.571228L335.1085205,63.8419685c-41.7384033,41.8608513-178.790451,47.0484352-222.5712585,52.3093605C119.826767,177.7639008,87.7829895,337.0223389,0,492.7574463z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Nib';
-->
