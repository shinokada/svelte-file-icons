<script>
  export let size = '24';
  export let color = 'currentColor';
  export let ariaLabel = 'NPM Old';
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
    d="M261 269h-27v-58h27v58zM320.5 298h58.5v-87h28.5v87l29 1v-88h30.5v87h29v-116h-175.5v116zM174.5 327h59.5v-28.5h57v-58l1-58.5h-117.5v145zM28.5 298.5h60v-87.5h28v87h30v-116h-118v116.5zM524 327h-260.5v30.5h-117v-30h-146.5v-174.5h524v174z"
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
