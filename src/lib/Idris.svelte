<script>
  export let size = '24';
  export let color = 'currentColor';
  export let ariaLabel = 'Idris';
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
    d="M90.9045486,76.1595078c65.5904465,19.8498535,82.3692856,36.2028046,105.4295578,95.4681473C191.8613586,99.3631668,162.9399109,69.2378616,90.9045486,76.1595078z M0,189.8201141c42.5803757,13.1125641,92.0234756,23.5907288,110.2935867,104.9417267C117.8361893,193.272995,69.7851028,188.1026154,0,189.8201141z M28.7707138,125.1052475c63.9822083,13.2225723,104.7684097,30.5947342,128.6062927,113.1624985C162.8459473,131.7509003,104.3822861,121.055481,28.7707138,125.1052475z M112.67202,0c349.1522217,227.6651764-77.556366,231.6875305,15.2575836,496.0000916L182.8717041,512C31.5120621,306.8072205,519.7553711,201.3293915,112.67202,0z"
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
