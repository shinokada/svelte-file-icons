<script>
  export let size = '24';
  export let role = 'img';
  export let color = 'currentColor';
  export let ariaLabel = 'Galaxy';
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
    d="M0,166.5648193V54.9356194h381.0335083v111.6291962H0z M0,312.9132996V201.2841339h284.3467712v111.6291656H0z M130.0875549,457.0643921V345.4351807H512v111.6292114H130.0875549z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.vercel.app/)
## Props
@prop export let size = '24';
@prop export let role = 'img';
@prop export let color = 'currentColor';
@prop export let ariaLabel = 'Galaxy';
-->
