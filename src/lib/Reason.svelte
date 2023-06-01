<script>
  export let size = '24';
  export let role = 'img';
  export let color = 'currentColor';
  export let ariaLabel = 'Reason';
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
    d="M512,512H0V0h512V512z M314,464h155v-38H362.5v-39h93v-39h-93v-38.5H466v-40H314V464z M110.6666641,465h49.6666641v-55.3792725h38.5343933L228,465h57l-41.3333435-65c35.3514404-14.8952332,45.0846558-62.1753845,28.5059204-95.2625732C261.6375122,283.7119751,239.0782623,269.9040527,208,269h-97.6666641L110.6666641,465z M206.4995422,308.6318359c35.1526337,2.9315186,36.0776978,62.1359863-7.8630981,62.1359863h-37.9278412v-62.1359863H206.4995422z"
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
