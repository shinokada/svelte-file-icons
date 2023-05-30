<script>
  export let size = '24';
  export let color = 'currentColor';
  export let ariaLabel = 'dotenv';
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
    d="M0,0v512h512V0H0z M74.1775513,463.2463074H32.4907494v-41.6867981h41.6868019V463.2463074z M111.9500656,462.9611206V326.3210449H212.693161l0.2080078,24.540863h-74.180191v29.0235901h68.6363068l0.1956329,23.0848999h-68.8319397v35.0075073h74.9184113l0.2117462,24.9832153H111.9500656z M344.701355,462.9611206h-28.7853394l-53.5267029-86.7573853v86.7573853h-25.7649536V326.3210449h27.8693542l53.9424438,90.0555115v-90.0555115h26.2651978V462.9611206z M437.4331055,462.9611206h-31.2703247L358.14328,326.3210449h31.3034973l33.4112549,95.7340393l31.75354-95.7340393H486.16922L437.4331055,462.9611206z"
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
