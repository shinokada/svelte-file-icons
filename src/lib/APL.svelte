<script>
  export let size = '24';
  export let color = 'currentColor';
  export let ariaLabel = 'APL';
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
    d="M480.4802246,480.4648132L240.2401123,0L0,480.4648132h208.7049408V512h63.0703583v-31.5351868H480.4802246z M271.7752991,417.3944702V204.089386l106.646759,213.3050842H271.7752991z M102.0581665,417.3944702L208.7049408,204.089386v213.3050842H102.0581665z"
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
