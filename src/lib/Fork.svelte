<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Fork';
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
    d="M297.2780457,511.7347717l-0.3943481-58.2897339c0-46.9115295,55.6741943-29.8793945,47.2282715-102.871582L328.3987732,77.9503098c-0.5171509-12.215004-15.1959534-12.4424973-14.7457886-0.2227402l-2.3899536,233.4410095c-1.2142944,19.0223694-23.7781372,15.8735657-23.0609131-4.1243896l-2.8995056-229.5781097c0-13.7004013-14.2588806-10.9332886-14.3927612,1.0123444l-3.8910217,234.1673584c-0.4552612,14.9178772-22.5220795,13.4670105-22.059845-0.7001648l-3.3061218-234.8532715c0-10.6005173-13.589386-11.6453247-13.8751068-1.261116l-3.9731293,237.1376801c-1.0592804,16.1966248-22.853363,14.0178833-21.7245789-3.473999l-2.7287598-231.73526c0.174469-13.0832443-13.2450867-12.3982391-13.8639221,0l-17.7867126,284.2504883c-0.417572,61.2171631,47.1520691,41.8705139,48.2332306,94.188324L215.8736572,512C42.274189,485.1724854-57.5365181,285.9633789,35.636261,126.6889877C135.3742828-43.808506,382.119873-41.819046,478.7123413,130.2613831C567.9307251,289.2050476,467.7977905,484.1438904,297.2780457,511.7347717z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Fork';
-->
