<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Haxe';
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
      fill: #020200;
    }
  </style><path
    class="st0"
    d="M510.5598755,371.0765381l-57.5418091-115.1441803l57.5299988-114.9936066l1.4427795-2.8840332v-3.2247162V13.6622219V0.0088889h-13.6533508H377.1641541h-3.2202759l-2.8808289,1.4390278L255.995285,58.9248619L140.9230499,1.4479166l-2.8806915-1.4390278h-3.2202759H13.6533337H0v13.6533327v121.167778v3.2247162l1.4427778,2.8840332l57.5302773,114.9951324L1.4397222,371.0773621L0,373.9588928v3.2210999v121.1577759v13.6533508h13.6533337h121.1687469h3.2259674l2.8848724-1.4437561l115.0625-57.5883484l115.0577698,57.5881958l2.8848572,1.4439087h3.2261047h121.182373h13.6533203v-13.6533508L512,377.1799927v-3.2216492L510.5598755,371.0765381z M426.4962463,244.7293091L267.2979126,85.4909744l212.2830505-53.0084763L426.4962463,244.7293091z M85.4905548,244.6567993L32.419445,32.4827766l212.3143005,53.0183372L85.4905548,244.6567993z M85.4836121,267.2445984l159.1997223,159.1966553l-212.265274,53.0138855L85.4836121,267.2445984z M426.4947205,267.2476501l53.0848694,212.2072144l-212.2724915-53.0137634L426.4947205,267.2476501z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Haxe';
-->
