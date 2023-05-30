<script>
  export let size = '24';
  export let color = 'currentColor';
  export let ariaLabel = 'Rebol';
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
    d="M508.0012512,256c0,141.3848877-112.8247986,256-252.0012512,256S3.9987483,397.3848877,3.9987483,256S116.823555,0,256,0S508.0012512,114.6151047,508.0012512,256z M248.9745178,117.0918961c-75.7006989,0-137.0682373,60.5548935-137.0682373,135.2531433s61.3675385,135.2531586,137.0682373,135.2531586s137.0682373-60.5549011,137.0682373-135.2531586S324.6752319,117.0918961,248.9745178,117.0918961z M248.9745331,197.0477905c-30.9496918,0-56.0393677,24.7574158-56.0393677,55.2972565s25.0896759,55.2972565,56.0393677,55.2972565s56.0393524-24.7574158,56.0393524-55.2972565S279.9242249,197.0477905,248.9745331,197.0477905z"
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
