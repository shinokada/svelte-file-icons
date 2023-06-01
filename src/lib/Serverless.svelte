<script>
  export let size = '24';
  export let role = 'img';
  export let color = 'currentColor';
  export let ariaLabel = 'Serverless';
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
    d="m0-0.001953125v106.61718h169.30469l28.07617-106.61718h-197.38086zm286.69922 0-28.07617 106.61718h253.37695v-106.61718h-225.30078zm-286.69922 202.69531v106.61133h115.92578l28.07617-106.61133h-144.00195zm233.32227 0-28.07618 106.61133h306.75391v-106.61133h-278.67773zm-233.32227 202.69336v106.61133h62.544922l28.080078-106.61133h-90.625zm179.94141 0-28.07618 106.61133h360.13282v-106.61133h-332.05664z"
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
