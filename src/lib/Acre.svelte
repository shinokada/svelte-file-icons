<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Acre';
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
    fill-rule="evenodd"
    clip-rule="evenodd"
    d="M221.7024994,512L0,384V128L221.7024994,0L444,128v256L221.7024994,512z M360.2485962,306.2721558l18.8882446,3.5755005c4.8817749,52.4662476-11.7792358,86.5969543-43.9667664,90.9980164c-31.3322144,3.7034607-50.8291016-24.7927856-62.406311-63.546875c-57.1787872,90.1828308-154.3312378,79.9512939-194.0273132,5.9785461c-36.9153023-68.2136841-5.8848648-189.2323914,77.2734375-212.4511719c48.7754822-12.382019,97.1066437,2.3746796,115.4550781,56.5195312l16.3671875-42.3945312c3.8867188-10.1640625,11.8476562-11.7265625,16.3164062-11.7265625l47.7734375,0.078125l20.6464844,3.7128906l-72.960907,154.2207031C317.2202759,330.9666748,341.3535461,341.256073,360.2485962,306.2721558z M234.369278,277.7363281c30.1928253-58.4589386-33.1330261-124.9042206-74.4414062-73.8437347c-29.3343201,38.5480194-40.537468,97.9733429-20.4824219,143.5702667C162.9099121,380.6321411,199.3048401,344.1163635,234.369278,277.7363281z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Acre';
-->
