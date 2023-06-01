<script>
  export let size = '24';
  export let role = 'img';
  export let color = 'currentColor';
  export let ariaLabel = 'Spacengine';
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
    d="M312.5479126,375.7917175L0,261.1716919v-40.98703l312.5479126-115.9498901v46.5962067L64.4699783,238.0519562l248.0779419,89.9580231V375.7917175z M429.4932861,0v512H474V0H429.4932861z"
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
