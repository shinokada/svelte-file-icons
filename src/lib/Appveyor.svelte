<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Appveyor';
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
  ><style type="text/css">
    .st0 {
      fill-rule: evenodd;
      clip-rule: evenodd;
    }
  </style><path
    class="st0"
    d="M255.171524,0C397.6698914,0,512,114.3300934,512,255.171524C512,397.6698914,397.6698914,512,255.171524,512C114.3300934,512,0,397.6698914,0,255.171524C0,114.3300934,114.3300934,0,255.171524,0z M318.1359253,304.880249c-28.1682739,36.4530945-79.5339813,43.0809021-114.3300934,14.9126282c-34.7961273-26.511322-39.7669983-77.8770142-11.5987091-114.3300934c29.8252411-34.7961121,81.1909485-41.4239502,115.9870605-14.9126282C342.9902954,218.7184448,347.9611511,270.084137,318.1359253,304.880249z M182.2653656,472.2330017l97.7605133-94.4465942c-36.453064,8.28479-74.5630951,1.6569519-104.3883362-23.1974182c-34.7961121-26.511322-49.7087402-71.249176-44.7378693-112.6731262l-87.8187714,96.1035461c0,0-11.5987053-21.5404358-14.9126205-61.3074341l154.0970764-120.9579315c46.3948212-33.1391602,109.3592377-34.7961121,154.0970917,0c49.7087402,39.7669983,59.6504822,112.6731415,23.1974182,167.3527374L246.886734,483.8317261C230.3171539,483.8317261,197.1779938,478.8608398,182.2653656,472.2330017z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Appveyor';
-->
