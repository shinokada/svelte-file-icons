<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Moment';
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
    d="M242.1621552,62.3649979v179.7971497h-96.9059601c-18.562767,0.7186737-18.0959396,27.0164337-0.022583,27.6756744h124.6042175V62.2823334C269.2958374,44.0486259,242.9074554,44.0486259,242.1621552,62.3649979z M145.0473938,447.6081848C-2.223104,362.7051086-2.2231429,149.2949371,145.047348,64.3918457S477.4054871,86.1938095,477.4054871,256S292.3179016,532.5112305,145.0473938,447.6081848z M512,256C512,59.6616783,297.9924927-63.7160072,127.7110519,34.4531631s-170.2813873,344.9245605,0.0000534,443.093689S512,452.3383484,512,256z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Moment';
-->
