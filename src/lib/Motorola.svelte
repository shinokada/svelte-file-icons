<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Motorola';
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
    d="M127.711113,477.5468445c-170.2814331-98.1691284-170.2814941-344.92453-0.000061-443.093689S512,59.6616783,512,256S297.9925537,575.7160034,127.711113,477.5468445z M410.831604,383.8144226h17.7280884L330.8048706,64.118187l-74.6818237,250.212616c0,0-74.6728058-250.2105865-74.6728058-250.2105865l-97.6917343,319.491272h17.9835739c6.6821747-26.0659485,14.1219177-51.4883118,24.9146881-74.2872314C140.5920105,279.255188,158.364151,264.9462585,180.1464386,263c29.3064728-2.6185608,52.662323,28.0310364,75.9334869,83.2154846C279.9602051,291.9601746,301.3186646,261.7067871,330.4717102,263c26.491394,1.1751404,45.6244507,19.9592285,61.5308533,61.4985046C398.9305115,344.0375671,404.7204895,363.98349,410.831604,383.8144226z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Motorola';
-->
