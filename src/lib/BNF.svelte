<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'BNF';
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
    d="M277.7397766,225.44133v-44.9335632H512V225.44133H277.7397766z M512,329.6286316V284.698761H277.7397766v44.9298706H512z M237.7977753,191.1131744c0-34.4499664-40.1886597-56.0980835-72.1659546-38.8731079s-31.9772797,60.5212402,0.0000153,77.7462158S237.7977753,225.5631409,237.7977753,191.1131744z M23.982975,229.9862823c-31.977293-17.2249756-31.9773045-60.5212402-0.0000114-77.7462158s72.1659393,4.4231415,72.1659393,38.8731079S55.9602699,247.2112732,23.982975,229.9862823z M237.7977753,320.8868103c0-34.4499512-40.1886597-56.0980835-72.1659546-38.8731079c-31.9772949,17.2250061-31.9772797,60.5212402,0.0000153,77.7462463C197.6091309,376.9849243,237.7977753,355.336792,237.7977753,320.8868103z M23.982975,359.7599487c-31.977293-17.2250061-31.9773045-60.5212402-0.0000114-77.7462463c31.9772949-17.2249756,72.1659393,4.4231567,72.1659393,38.8731079S55.9602699,376.9849243,23.982975,359.7599487z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'BNF';
-->
