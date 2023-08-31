<script>
  export let size = '24';
  export let role = 'img';
  export let color = 'currentColor';
  export let ariaLabel = 'PM2';
</script>

<svg
  version="1.1"
  xmlns="http://www.w3.org/2000/svg"
  width={size}
  height={size}
  viewBox="0 0 512 512"
  fill={color}
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
    d="M485.3173828,146.6230621H26.6821861c-35.5762482,0-35.5762482-59.3741379,0-59.3741379c0,0,458.6351929,0,458.6356812,0C520.894104,87.2489243,520.894104,146.6230621,485.3173828,146.6230621z M485.3173828,285.6865234L26.6821861,285.686554c-35.5762482,0-35.5762482-59.3741608,0-59.3741608c0,0,458.6351929,0,458.6356812,0C520.894104,226.3123932,520.894104,285.686554,485.3173828,285.6865234z M485.3173828,424.7510681H26.6821861c-35.5762482,0-35.5762482-59.3741455,0-59.3741455c0,0,458.6351929,0,458.6356812,0C520.894104,365.3769226,520.894104,424.7510681,485.3173828,424.7510681z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.vercel.app/)
## Props
@prop export let size = '24';
@prop export let role = 'img';
@prop export let color = 'currentColor';
@prop export let ariaLabel = 'PM2';
-->
