<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Curl Lang';
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
    d="M512,6.4584961v231.4690552C366.1229858,218.4994507,366.1229858,25.8865967,512,6.4584961z M52.7320557,380.4248047c4.6139526-56.5650024,32.9242554-92.4883423,90.8496704-102.6143799c7.6697388-89.9746094,56.7178345-139.4564209,137.2941284-156.555542C284.7368164,71.9747314,295.9334717,30.5866089,317.1699219,0H0v410.9274902C17.0948486,392.1320801,34.6506958,381.5794067,52.7320557,380.4248047z M296.0733032,201.8296509c-96.7640991,7.2799072-92.5639648,151.4853516,5.7175903,151.1049805v79.4705811c-64.3776855,2.9803467-121.1107178-32.3887939-147.1765137-102c-63.6627197,4.0951538-62.4758301,100.7075806,5,99.6928101V487c-41.600769-0.2810059-76.6091309-20.1528931-101.3071899-70.973877c-43.5804443,2.5319214-41.7836304,65.6445923,1.6143799,67.666687V512H512V357.5644531C399.6739502,350.800354,333.5483398,292.3433838,296.0733032,201.8296509z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Curl Lang';
-->
