<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'FreeMarker';
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
      fill: #181816;
    }
  </style><path
    class="st0"
    d="M144.6763458,342.1148682L7.6788573,268.8112793c-4.8112984-2.5727844-7.753346-7.5603333-7.6771965-13.0143433c0.0761494-5.4525757,3.1537328-10.3553619,8.0316029-12.7959595l136.6430817-68.31604v32.4975739l-98.5205078,49.2537994l98.5205078,52.718811V342.1148682z M367.3246155,342.1167908v-32.9635925l98.52005-52.7168884l-98.52005-49.2533112v-32.4980621l136.6416626,68.3155518c4.880249,2.4444427,7.9568787,7.347702,8.0325623,12.7969208c0.074707,5.453537-2.8649597,10.4391632-7.6743469,13.0138702L367.3246155,342.1167908z M324.8769226,142.8736572H290.650177l-10.3187256,56.8387299h-32.163147l10.3190918-56.8387299h-34.2267609l-10.3190918,56.8387299h-33.4679413v33.6768036h27.3538971l-8.7918549,48.4249573h-33.2496948v33.6767883h27.1356354l-9.7377167,53.6354065h34.2272034l9.7373352-53.6354065h32.1647644l-9.737381,53.6354065h34.2271881l9.7369385-53.6354065h37.184082v-33.6767883h-31.0705566l8.7911987-48.4249573h32.5224915v-33.6768036h-26.4085693L324.8769226,142.8736572z M242.0542755,233.3891907h32.1636505l-8.7911987,48.4249573h-32.1639862L242.0542755,233.3891907L242.0542755,233.3891907z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'FreeMarker';
-->
