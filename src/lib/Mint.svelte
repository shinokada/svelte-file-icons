<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Mint';
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
    d="M512,169.9434357c-50.2958984,12.0326996-91.6525879,12.6312256-127.442627,7.489212c-22.8954468,27.9791718-36.9017029,56.091568-48.5680237,83.7376404c48.6929321-13.6398468,96.5822754-31.7118073,136.1236572-55.3400421c-42.6973572,31.4932098-92.066864,53.5538788-141.8173218,69.2754974C310.0269775,329.70047,290.4538879,375.6972351,253.221817,404.671814C311.6116943,384.3327637,413.4671326,328.8626099,512,169.9434357z M248.3629456,389.6121521c80.1028442-69.5482178,48.7803345-188.2660828,203.3840027-290.8230591C196.0269165,48.2121811,82.9381943,139.4328156,63.6025887,153.5348206c-103.9934082,75.8414459-56.637001,198.2597046-24.0404358,169.647644c53.2770042-46.0906677,133.2966003-158.4403839,286.561615-198.7374573c-139.1255798,37.8488998-237.2650146,170.6812744-263.03125,204.0834656C17.4947414,398.5248718,152.7467804,477.1705627,248.3629456,389.6121521z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Mint';
-->
