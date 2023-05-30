<script>
  export let size = '24';
  export let color = 'currentColor';
  export let ariaLabel = 'XPages';
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
    points="297.1637268,247.4545441 484.7601318,59.8547173 392.2837219,59.8547173 249.8061676,202.334549 100.2646027,59.8547173 5.4582372,59.8547173 203.5537109,248.58815 0,452.1452942 92.4764099,452.1452942 250.9112701,293.7081299 417.2073059,452.1452942 512,452.1452942 "
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
