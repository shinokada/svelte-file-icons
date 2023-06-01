<script>
  export let size = '24';
  export let role = 'img';
  export let color = 'currentColor';
  export let ariaLabel = 'Hack';
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
    d="M0,327.6181335V164.1326904L165.0671997,0v161.7559662L0,327.6181335z M178.9753876,166.9897614v161.5811005l160.4861298-161.259079L178.9753876,166.9897614z M165.0671997,333.0887756V180.3822479L13.092617,333.0887756H165.0671997z M0,348.2492371v163.0111084l163.1258698-163.0111084H0z M178.9753876,347.1971436V512L349.910675,340.9975586l-0.0001831-165.5587463L178.9753876,347.1971436z"
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
