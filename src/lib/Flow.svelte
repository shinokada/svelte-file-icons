<script>
  export let size = '24';
  export let role = 'img';
  export let color = 'currentColor';
  export let ariaLabel = 'Flow';
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
  ><polygon
    points="342.0658569,440.933075 342.0658569,411.3126831 356.7983398,426.1644592 356.7983398,283.0133057 327.1159973,283.0133057 327.1159973,211.8473969 380.4424133,265.6057739 380.4424133,122.4546204 259.8787537,122.4546204 138.4082642,0 138.4082642,52.3329277 29.3909264,52.3329277 57.8890114,81.061554 0,81.061554 141.8037567,224.6438904 29.7513371,224.6438904 142.2398682,338.0437012 0,338.0437012 171.7141876,511.2290344 171.7141876,143.1511536 258.9718323,143.1511536 294.9031372,179.3736267 214.7923584,179.370163 214.7923584,322.5213318 253.9880371,322.5213318 299.9467468,368.8522949 210.7737579,368.8522949 210.7702942,512 412.5617065,512 "
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.vercel.app/)
## Props
@prop export let size = '24';
@prop export let role = 'img';
@prop export let color = 'currentColor';
@prop export let ariaLabel = 'Flow';
-->
