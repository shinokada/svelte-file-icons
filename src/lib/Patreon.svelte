<script>
  export let size = '24';
  export let role = 'img';
  export let color = 'currentColor';
  export let ariaLabel = 'Patreon';
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
    d="M0,501.5053711h90.0101624V10.4998932H0V501.5053711z M235.6962891,353.8507996c-122.4323578-70.5835876-122.4324036-248.0007324-0.0000458-318.5843506S512,53.3913765,512,194.5586243S358.1286316,424.4344482,235.6962891,353.8507996z"
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
