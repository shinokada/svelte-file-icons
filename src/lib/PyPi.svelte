<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'PyPi';
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
    d="M454,305.8294373l-91.1191101,33.691803v106.4807434L181.94487,512V298.2970276l179.8842926-66.8633728V58.8240128L454,92.4968643V305.8294373z M276.8390503,363.3849487c-15.7174377,5.7245483-28.4572144,23.9239502-28.4515686,40.6481018c0.0061646,16.7174377,12.7523499,25.6329346,28.4636841,19.919281c15.7173462-5.7247009,28.4602051-23.9217834,28.4544983-40.6459656C305.303009,366.5810547,292.5565491,357.6635437,276.8390503,363.3849487z M334.6160889,212.4997864l-180.3925323,66.8782959l0.2966461,135.7604065l-64.2104874,22.9912415L0,405.2594604V191.9265442l90.704361-33.6917877V51.7543259L232.9717102,0l101.6443787,32.4636765V212.4997864z M215.2144775,94.8330383c-15.7174835,5.7222672-28.4621582,23.9249802-28.458725,40.6499329c0.0025787,16.725235,12.750824,25.6462555,28.4683228,19.9248505c15.7174988-5.7219086,28.4623871-23.9248047,28.4592285-40.6498184C243.6806641,98.0326996,230.9319763,89.1116333,215.2144775,94.8330383z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'PyPi';
-->
