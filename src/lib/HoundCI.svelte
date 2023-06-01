<script>
  export let size = '24';
  export let role = 'img';
  export let color = 'currentColor';
  export let ariaLabel = 'HoundCI';
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
    d="M0,0h512v224.9207306C490,114,348,36,358.3614502,75.6137466c9.9326477,23.5884705,9.9326477,85.033165,9.9326477,85.033165L268.283844,198.7927094l-15.0007172,55.4827423l-122.397583,32.2702637c0,0,8.7222748,62.4294434,43.9036102,73.3403931c22.5662689,6.9985962,170.4819641,23.31604,170.4819641,23.31604l-28.0803833,123.7782593H0V0z"
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
