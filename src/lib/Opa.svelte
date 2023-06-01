<script>
  export let size = '24';
  export let role = 'img';
  export let color = 'currentColor';
  export let ariaLabel = 'Opa';
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
    d="M59.3853531,242.4671326c2.6719437-50.603302,44.7509308-77.7847443,94.4229355-54.0366821C197.8271027,53.0682106,417.0513,54.4601021,429.4044189,238.0168915c106.3359375,15.4591522,113.8359375,156.3756256,0.0545654,181.1209259H78.1237335C-18.6132927,398.9552917-26.2687416,277.1640625,59.3853531,242.4671326z"
  /></svg
>
<!--
@component
[Go to Document](https://svelte-file-icons.codewithshin.com/)
## Props
@prop size = '24';
@prop role = 'img';
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
