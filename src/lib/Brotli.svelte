<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Brotli';
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
    d="M127.7110596,34.453125c-170.2814331,98.1691895-170.2813721,344.9245605,0.000061,443.093689S512,452.3383179,512,256S297.9924927-63.7160034,127.7110596,34.453125z M157.1137085,229.503479c-14.633606,54.6134033-37.5646973,95.9205933-51.2180176,92.262146c-13.6533813-3.6583862-12.8587036-50.8969727,1.7749023-105.510376c14.633606-54.6133423,37.5647583-95.9205322,51.2180786-92.262146C172.5419922,127.6515503,171.7473755,174.8901367,157.1137085,229.503479z M305.4431152,269.24823c-29.2672119,109.2267456-75.1293945,191.8411255-102.4360962,184.524292s-25.7173462-101.7940063,3.5498657-211.020752S281.6862793,50.9106445,308.992981,58.227478S334.7103271,160.0214844,305.4431152,269.24823z M404.3294067,295.744751c-14.633606,54.6133423-37.5647583,95.9205322-51.2180786,92.262146c-13.6533203-3.6584473-12.8587036-50.8970337,1.7749634-105.510376c14.633606-54.6134033,37.5646973-95.9205933,51.2180176-92.262146C419.7576904,193.8927612,418.9630127,241.1313477,404.3294067,295.744751z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Brotli';
-->
