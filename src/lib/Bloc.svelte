<script>
  export let size = '24';
  export let role = 'img';
  export let color = 'currentColor';
  export let ariaLabel = 'Bloc';
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
    d="M213.8590546,0L0,132.5080566v245.8555603L213.8590546,512L428,378.3636169V132.5080566L213.8590546,0z M369.8815002,155.3607941L213.8590546,245.925705L57.8361092,155.3607941L213.8590546,58.688015L369.8815002,155.3607941z M49.8879547,173.8201294l153.9934998,89.387146v183.7310791l-153.9934998-96.227478V173.8201294z M223.8366394,446.9382935v-183.730957l153.9930115-89.3866577v176.8901978L223.8366394,446.9382935z"
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
