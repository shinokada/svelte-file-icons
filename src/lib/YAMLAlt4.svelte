<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'YAML Alt4';
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
    d="M235.793457,20.9389935l-91.8156738,137.6740112v87.2750244H87.7020035v-87.2751465L0,20.9389935h63.2502899l55.7678528,88.6458817l56.2244568-88.6458817H235.793457z M330.2944641,195.8635406H228.4328003l-20.7168121,50.0244904h-45.1060944l95.3815918-224.9490356h46.1360474l91.5108948,224.9490356h-48.1963501L330.2944641,195.8635406z M313.3734131,151.1300201l-31.2258606-82.5503616l-34.8368378,82.5503616H313.3734131z M87.7023544,270.5895996v220.471405h47.3023605V338.9823914l49.5055237,102.2188416h37.2337494l51.1964111-105.8118896v155.6254272h45.3786011V270.5895996h-61.959259l-54.977951,99.7063904l-52.3599548-99.7063904H87.7023544z M512,443.201355H395.6384277V270.5895996h-48.1963501v219.5221863L512,490.111969V443.201355z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'YAML Alt4';
-->
