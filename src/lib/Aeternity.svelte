<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Aeternity';
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
    d="M390.9197083,134.6256561c-49.3862305,0-83.2434998,30.982254-112.4981995,69.3538361l17.3384705,25.4276428c26.7957764-36.7764435,55.2875977-65.7789612,95.1597595-65.7789612c45.0220337-0.0865021,83.4938354,32.420166,90.9228821,76.8251343H368.1401367v29.0025024h143.1210938C519.0031738,195.905365,465.0100708,135.4411011,390.9197083,134.6256561z M388.2779846,377.3640747c50.5515747,0.1470337,96.0812378-30.5499878,114.9003906-77.4682312h-32.621521c-16.6288757,29.824646-48.1318054,48.2773743-82.2788696,48.1946106c-110.564209,0.1062012-127.0394897-206.6584778-265.3036194-213.464798c-164.3379974,7.2819061-163.5932007,234.8174591,0,242.7384186c50.1175919,0,84.4855576-31.1335449,114.2005539-69.7510376l-17.4960785-25.8059387c-27.2371521,37.1043091-56.189209,66.2896729-96.7107849,66.2896729c-123.740242-6.2111511-123.740242-177.5145111,0.0063095-184.2037964C232.8186493,163.2617035,259.5909729,379.0877991,388.2779846,377.3640747z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Aeternity';
-->
