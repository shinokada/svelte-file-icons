<script>
  export let size = '24';
  export let color = 'currentColor';
  export let ariaLabel = 'KRL';
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
    d="M0,0v512h512V0H0z M11.1516304,494.2956543l170.5500031-252.6467438L20.6728268,16.9635181h96.0189514l159.9886475,223.2419128L105.1557083,494.2956543H11.1516304z M405.4979553,494.2956543l-139.5053711-206.658844l33.3161011-47.7302856l-33.4935303-43.954422L393.9616089,16.9635181h96.0184326L328.952179,241.6494598l170.5483704,252.6461945H405.4979553z"
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
