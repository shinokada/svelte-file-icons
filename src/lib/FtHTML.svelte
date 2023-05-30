<script>
  export let size = '24';
  export let color = 'currentColor';
  export let ariaLabel = 'ftHTML';
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
    d="M85.4397964,261.5096436v232.5240479h94.8621445V261.5096436h142.4528809v189.0854797l77.7741699,43.4385681h91.5084534v-76.496582h-74.7398682V261.5096436H512v-78.8920593h-94.7024231V61.5645676l-94.5427551,52.5414886v68.511528H180.3019409V94.7822876h76.8159485V17.9663143h-92.3069153L85.4397964,61.5645676v121.0530167H0v78.8920593H85.4397964z"
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
