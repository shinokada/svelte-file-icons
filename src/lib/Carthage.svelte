<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Carthage';
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
    d="M256,0C114.6149902,0,0,114.6149902,0,256s114.6149902,256,256,256s256-114.6149902,256-256S397.3850098,0,256,0z M259.664856,435.0324097C20.1135864,435.0343628,20.1106567,80.9703979,259.6619263,80.9684448c13.3584595-0.6360474,14.3096313,19.3414917,0.9511719,19.9775391c-212.8156128-0.0020142-212.8185425,314.105896-0.0029297,314.1079102C274.0169678,415.6882324,273.0716553,435.666748,259.664856,435.0324097z M259.6697388,392.7609253c-187.5577393,0.0020142-187.5606689-269.5184937-0.0029297-269.5205078c13.2700806-0.6253662,14.2114868,19.3521729,0.9414062,19.9775391c-159.4755859-0.0020752-159.4785156,229.562439-0.0029297,229.5644531C274.4790649,373.4320679,273.5435181,393.4105835,259.6697388,392.7609253z M260.5964966,329.0880737c13.2194824,0.6074219,12.3015137,20.5859375-0.9179688,19.9785156c-126.90271,0.0020142-126.9056396-182.1307983-0.0029297-182.1328125c13.1015625-0.605835,14.0253906,19.3726807,0.9238281,19.9785156C159.802124,186.9102173,159.7991943,329.0859985,260.5964966,329.0880737z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Carthage';
-->
