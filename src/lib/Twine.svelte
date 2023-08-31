<script>
  export let size = '24';
  export let role = 'img';
  export let color = 'currentColor';
  export let ariaLabel = 'Twine';
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
    d="M0.0000754,281.0731506V-0.0000305h191.9999695v94.6494446C106.0091095,132.1404572,30.9520683,197.9311829,0.0000754,281.0731506z M0,416.0000305v95.999939h192.0000458v-95.999939C192.0000458,256,448,256,448,256V64.0000381C448,64.0000381,0,64.0000381,0,416.0000305z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.vercel.app/)
## Props
@prop export let size = '24';
@prop export let role = 'img';
@prop export let color = 'currentColor';
@prop export let ariaLabel = 'Twine';
-->
