<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Bikeshed';
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
    d="M384.0036011,319.2336426l-27.3482056-82.045639h-65.5612488v32.3463287h42.2510376l3.3753967,10.1254883l-72.5804749,53.4787598V63.9684677l59.2967529-31.6247826V0L0,172.499649v32.343689l21.5624561-11.5001373v307.9839172h242.577652V373.3121948l83.3314209-61.4021301l5.8298645,17.4885559c-58.3508301,30.6199646-70.5066833,112.7406311-18.6519775,158.3897705c55.9184265,49.2261963,144.6730347,19.4096985,159.3751831-53.5412598C507.6004944,366.8825378,448.7090759,309.0272217,384.0036011,319.2336426z M462.3182068,427.8572998c-9.8010864,48.6339722-68.9708557,68.5115356-106.2497864,35.6940613c-33.1027222-29.1410217-27.0287476-80.5272217,7.6960449-102.7655029l15.3065186,45.9162903c-3.3615723,8.0507202-1.8898621,17.9784851,5.5557861,24.5331726c12.4263,10.9391479,32.1495667,4.3134155,35.416687-11.8979187c1.9421997-9.6382141-2.8130798-18.3696899-10.26828-22.7870483l-15.3328552-46.0002136C435.3546143,347.6610413,470.9844971,384.8551025,462.3182068,427.8572998z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Bikeshed';
-->
