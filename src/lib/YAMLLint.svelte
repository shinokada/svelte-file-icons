<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'YAMLLint';
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
    d="M320.4455872,29.3965263h101.780426l-302.743042,453.2069702H17.7033958L169.074707,256L0,29.3965263h101.7795715l118.184906,150.4206238L320.4455872,29.3965263z M272.0742493,377.5595398c10.2857666,8.2172241,21.2311096,22.4058228,32.8308105,42.5659485c44.0107117-97.6838989,94.2474976-180.9106598,148.0999756-231.5752106c1.9329834-3.6160278,78.471283-23.3442841,54.2693787-0.4140625c-91.7485657,87.0812225-142.7290344,204.299057-180.1026611,286.3615112c-2.0613403,1.9746704-12.0012207,8.7069092-36.5943909,6.5369263c-22.2215576-0.0323792-18.6898499-21.6177673-69.2982025-75.5751953C200.0683289,380.155304,239.8851776,349.2693481,272.0742493,377.5595398z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'YAMLLint';
-->
