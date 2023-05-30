<script>
  export let size = '24';
  export let color = 'currentColor';
  export let ariaLabel = 'Nomad';
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
    d="M220.2799835,512L0,381.0243225V127.4052048L219.0886841,0L438,126.2139053v257.1913147L220.2799835,512 M329.134552,101.1419525l-74.0998993,43.3744202v87.5464783l-74.2436829-44.0864716l-71.3903885,41.7894745v182.9835663l74.0999069-45.4420776V268.811554l79.1440735,49.9624939l66.4899902-40.7744751V101.1419525z"
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
