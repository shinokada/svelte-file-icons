<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Logtalk';
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
    d="M76.1398773,422.0431824H0V90.2876053h76.1398773v23.246048H33.2086372v281.942627h42.9312401V422.0431824z M434.7931519,89.9568176v23.2460403h43.9981995v282.2734375h-43.9981995v26.5668945H512V89.9568176H434.7931519z M361.3579712,303.7374268l-0.0713501-16.6043396l-190.502121,0.802063v-39.4348602l190.5702362-0.8024445l-0.0713501-16.6043243l-190.4988861,0.8020477v-72.2006226h-16.6043243v212.5352783h16.6043243V304.539856L361.3579712,303.7374268z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Logtalk';
-->
