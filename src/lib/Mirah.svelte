<script>
  export let size = '24';
  export let color = 'currentColor';
  export let ariaLabel = 'Mirah';
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
    d="M0,329.1577148c0,0,62.2013016-125.9619904,62.2013016-329.1200867c0,0,47.7444153-1.1948946,44.6908112,42.7941437c-20.3158112,325.0529785,160.2903748,236.310257,158.4672852-0.1269722c0,0,0.1680298-44.2482452,44.6947937-42.6632042V512c-21.4660034,0-30.2155762-47.9694214-35.90979-109.8998108c-7.7385559-84.1647644-7.9044189-194.9558563-8.7532654-253.9833221c-44.0678406,236.2069855-154.7890015,246.8727875-197.1188965-22.3017654C68.2722397,125.8151016,79.9591141,331.1641541,0,329.1577148z"
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
