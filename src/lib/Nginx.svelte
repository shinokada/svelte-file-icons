<script>
  export let size = '24';
  export let role = 'img';
  export let color = 'currentColor';
  export let ariaLabel = 'nginx';
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
    d="M512,236.32901L390.0952454,482.9090881h-262.649353L0,259.0476074L126.891777,29.09091h273.7315979l72.5887451,170.1125488h-94.7532654l-37.1255188-75.3593063H182.8571472l-74.2510834,134.649353l73.6969604,130.2164612H331.359314l28.2597351-57.6277161H243.3928375c-24.1303253,0-47.7458649-18.6795654-47.7458649-46.8225403c0-26.1653748,26.0871124-47.9306946,47.7458649-47.9306946H512z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.vercel.app/)
## Props
@prop export let size = '24';
@prop export let role = 'img';
@prop export let color = 'currentColor';
@prop export let ariaLabel = 'nginx';
-->
