<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'BlitzBasic';
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
  ><g
    ><path
      d="M444.050354,334.8735962c82.1834106-10.4796753,78.9370117-138.5884705-49.6408997-134.0305328c-36.526886,0-70.0711975,0.2498016-99.3139648,0.1282959c-10.3668518-16.2504272-29.2111816-29.7910461-58.0731506-36.6835022c82.1833801-10.4796753,78.9369812-138.5884705-49.6409302-134.0305328C100.7855759,30.257328,40.6914978,31.6698284,0,26.1792812v68.1875076h43.9372711v155.645401H0v65.2228241l227.860321-0.0000305v105.362915h-25.1997223v65.2228088h216.4211884C518.2756958,485.8207092,554.9152222,361.3488464,444.050354,334.8735962z M158.6999512,251.8837128h-31.4392242v-55.3289642h31.4392242C191.2424164,199.8641205,191.2424164,246.9196472,158.6999512,251.8837128z M158.6999512,146.6377869h-31.4392242V91.3088226h31.4392242C191.2424164,94.6182022,191.2424164,141.6737213,158.6999512,146.6377869z M365.7279663,422.4694519h-31.439209v-55.3289795h31.439209C398.2704468,370.4498596,398.2704468,417.5053711,365.7279663,422.4694519z M365.7279663,317.2235107h-31.439209v-55.328949h31.439209C398.2704468,265.203949,398.2704468,312.2594604,365.7279663,317.2235107z"
    /></g
  ></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'BlitzBasic';
-->
