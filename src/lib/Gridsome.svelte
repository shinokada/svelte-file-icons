<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Gridsome';
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
    d="M258.8266296,509.3565674C129.2450256,512.5282593,0.1749497,412.6851196,0.1749497,257.1334839C-4.978981,128.8989258,102.7613144,5.0595765,254.3143005,2.5700135c58.9636841,0.0925293,63.2028198,83.1536255,3.7130127,88.699707C151.6959534,95.6605911,86.7239609,177.0215454,89.8785629,255.7160645c0,102.3198853,83.7461624,166.9230957,166.6140747,164.8939209c81.4849243-2.2474365,139.6471558-58.5155029,157.9997559-117.517395h-16.9251709c-25.4627686,0-46.1083374-20.347168-46.1083374-45.4432983c0-25.1004028,20.6456299-45.4432983,46.1126099-45.4432983h67.1972656c24.407959,0,45.0185852,18.6867676,46.6864929,42.3384399C520.6675415,372.7822876,412.5920715,505.1191406,258.8266296,509.3565674z M302.0423889,257.7129517c0-35.1173401-38.2776489-57.1848297-68.7344208-39.6261597s-30.4567566,61.6936646,0,79.2523193S302.0423889,292.8302917,302.0423889,257.7129517z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Gridsome';
-->
