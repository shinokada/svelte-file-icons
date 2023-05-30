<script>
  export let size = '24';
  export let color = 'currentColor';
  export let ariaLabel = 'Yasm';
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
    d="M460.0460815,461.8877563l-39.8195801-63.3086853c-0.6036682-0.9599609-1.3707581-1.7533569-2.239563-2.3742676L406.9464722,28.9768276C399.5555115-95.9108887-95.6213455,219.9573059,16.522707,275.0841064l330.2804565,164.7429504l41.9424744,66.9060364C399.6802979,527.0631714,473.9299927,483.4784241,460.0460815,461.8877563z"
  /></svg
>
<!--
@component
[Go to Document](https://svelte-file-icons.codewithshin.com/)
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
