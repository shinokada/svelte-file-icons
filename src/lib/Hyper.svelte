<script>
  export let size = '24';
  export let role = 'img';
  export let color = 'currentColor';
  export let ariaLabel = 'Hyper';
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
    d="M289.381012,382H512v42H289.381012V382z M221.0805511,273.4808655L25.1055088,444.2320557l60.9970627-149.4495544L0,238.502243L195.9919586,67.7679443l-66.339386,158.9676819L221.0805511,273.4808655z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.vercel.app/)
## Props
@prop export let size = '24';
@prop export let role = 'img';
@prop export let color = 'currentColor';
@prop export let ariaLabel = 'Hyper';
-->
