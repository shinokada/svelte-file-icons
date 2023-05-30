<script>
  export let size = '24';
  export let color = 'currentColor';
  export let ariaLabel = 'CWL';
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
  ><polygon
    points="65.6418991,272.5973511 148.930069,189.3618774 70.382225,113.4510956 148.5671539,33.9828758 115.2491531,0 2.1846223,114.2819748 82.0886459,190.0562897 0,272.4902039 80.2605972,353.2218933 0,435.0932007 75.3656998,512 108.3487549,478.3586426 65.7311859,434.6905823 146.043808,353.4049377 "
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
