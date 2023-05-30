<script>
  export let size = '24';
  export let color = 'currentColor';
  export let ariaLabel = 'Flutter';
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
    d="M415.5129089,0.0000051L79.181015,337.1142273L0,257.8892822L257.290802,0h158.2221069 M414.5414734,238.3278046H256.3193359L118.5063324,376.4613342L253.8044739,512h156.969635L276.5163879,376.6739807L414.5414734,238.3278046z"
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
