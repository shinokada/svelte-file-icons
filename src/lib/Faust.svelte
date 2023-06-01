<script>
  export let size = '24';
  export let role = 'img';
  export let color = 'currentColor';
  export let ariaLabel = 'Faust';
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
    d="M156.300766,0h129.1401825l113.9929504,315.824646H283.3262024l-66.6020355-202.5960846L149.4469299,315.824646H40.4478722L156.300766,0z M124.7705383,449.6147156c0-47.8461609-52.1520157-77.9123535-93.6483154-53.9892883c-41.4963036,23.9230957-41.4962883,84.0555115,0.0000134,107.9786072C72.6185379,527.5270996,124.7705383,497.460907,124.7705383,449.6147156z M441.9837646,449.6147156c0-47.8461609-52.1520081-77.9123535-93.6483154-53.9892883c-41.4963074,23.9230957-41.4962769,84.0555115,0.0000305,107.9786072C389.8317871,527.5270996,441.9837646,497.460907,441.9837646,449.6147156z"
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
