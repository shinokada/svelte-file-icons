<script>
  export let size = '24';
  export let color = 'currentColor';
  export let ariaLabel = 'Doclets';
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
    d="M284.5910339,3.0859876H0v462.3031921c28.4193192-178.657196,121.8003235-234.5325623,262.4673462-244.0832062c16.4673157,187.5440216-106.08255,269.6950684-236.0550385,287.6080322h258.1787109C583.2608032,476.7339783,592.3114014,41.2996254,284.5910339,3.0859876z"
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
