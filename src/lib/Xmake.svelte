<script>
  export let size = '24';
  export let role = 'img';
  export let color = 'currentColor';
  export let ariaLabel = 'xmake';
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
    d="M8.1192255,288.7877808l178.6045685-110.1394043l288.4295654,177.8648376C366.6425171,538.7865601,73.654274,522.0443726,8.1192255,288.7877808z M424.671875,31.9137726L205.7734375,166.9010925l279.0447388,172.0774536C539.3922119,223.2163391,507.9644775,106.6516571,424.671875,31.9137726z M3.6640604,268.0405273l164.0100861-101.1394958L39.3852081,87.7895355C6.0940452,140.989151-7.080267,200.4083557,3.6640604,268.0405273z"
  /></svg
>
<!--
@component
[Go to Document](https://svelte-file-icons.codewithshin.com/)
## Props
@prop size = '24';
@prop role = 'img';
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
