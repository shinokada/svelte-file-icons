<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'KitchenCI';
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
    d="M357.2203674,0l117.9273376,0l-0.0003662,131.0222473c-4.612915,60.7189178-53.4425659,109.0577393-114.1960144,113.1907806l-129.540863-0.0002899l0.1097412-125.7733078C235.7007294,47.0051231,288.4603271,1.7468828,357.2203674,0z M231.6670074,268.2993469l129.2477264,0.2560425c61.1678772,4.088562,110.1636658,52.8077087,114.232605,113.9769287L475.1477051,512H342.7537537c-60.2350159-5.1985779-107.5336151-54.2443237-111.0872498-114.5987549L231.6670074,268.2993469z M207.03125,346.3749695C199.4441376,492.8363037,2.3686259,476.7278748,0,350.2522278l0.0365927-188.3033295C1.9081703,39.0036659,184.9414978,20.333601,206.1758423,151.4300995C208.2644348,168.0634918,207.03125,346.3749695,207.03125,346.3749695z M159.2158051,164.815567c0-42.9568253-46.8226624-69.9506073-84.0785141-48.4721909s-37.2558327,75.4659805,0.0000153,96.9443893S159.2158051,207.7723999,159.2158051,164.815567z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'KitchenCI';
-->
