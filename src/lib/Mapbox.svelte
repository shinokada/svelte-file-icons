<script>
  export let size = '24';
  export let color = 'currentColor';
  export let ariaLabel = 'Mapbox';
</script>

<svg
  version="1.1"
  xmlns="http://www.w3.org/2000/svg"
  width={size}
  height={size}
  viewBox="0 0 512 512"
  fill={color}
  class={$$props.class}
  {...$$restProps}
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
    d="M30.1180458,0.0009028V512h75.2939911V90.3536835L256,346.353241L406.5879822,90.3536835V512h75.2939758V0.0009028h-60.235199c-30.1175842-0.0965072-53.7714844,7.5293984-67.0586853,30.1175938L256,197.6476135L157.4119415,30.1184959C144.1247406,7.5303011,120.4708252-0.0956044,90.3532333,0.0009028H30.1180458z"
  /></svg
>
<!--
@component
[Go to Document](https://svelte-ant-design-icons.codewithshin.com/)
## Props
@prop size = '24';
@prop ariaLabel = 'icon file name';
@prop color = 'currentColor';
## Event
- on:click
- on:keydown
- on:keyup
- on:focus
- on:blur
- on:mouseenter
- on:mouseleave
- on:mouseover
- on:mouseout
-->
