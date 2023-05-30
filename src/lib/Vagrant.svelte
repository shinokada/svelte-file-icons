<script>
  export let size = '24';
  export let color = 'currentColor';
  export let ariaLabel = 'Vagrant';
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
    d="M506.9 36.7l-63.1-36.7-126.1 73.4v34.5l-64 166.8-63.6-165v-36.2l-126.7-73.5-63.3 36.6-0.1 37.3 158.6 383.6 95.1 54.4 94.9-54.7 158.7-384-0.4-36.5z"
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
