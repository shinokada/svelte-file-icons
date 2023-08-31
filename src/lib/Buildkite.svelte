<script>
  export let size = '24';
  export let role = 'img';
  export let color = 'currentColor';
  export let ariaLabel = 'Buildkite';
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
    d="M512,169.843811L342.6939087,256V85.0318604L512,169.843811z M330.6939087,90.947876l-154.031311,75.9379272v170.944519l154.031311-75.9160156V90.947876z M164.6625977,166.8620605L0,85.0318604V256l164.6625977,81.8065796V166.8620605z M342.6939087,269.4644165v157.5036621L512,340.7874756v-157.479248L342.6939087,269.4644165z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.vercel.app/)
## Props
@prop export let size = '24';
@prop export let role = 'img';
@prop export let color = 'currentColor';
@prop export let ariaLabel = 'Buildkite';
-->
