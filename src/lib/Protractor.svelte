<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Protractor';
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
    d="M380.333313,273.1111145h-247C133.333313,227.7242126,166.5317383,146,256,146C368,146,380.333313,257.5830688,380.333313,273.1111145z M512,256c0,196.3383179-214.0074463,319.7159424-384.2888794,221.546875s-170.2814941-344.9245605-0.000061-443.093689S512,59.6616821,512,256z M451,324v-40.8888855h-41.666626V262.5h41.4993896c-1.8225098-47.4682617-20.8424072-88.4584351-49.5385742-119.6640625l-29.3642578,29.3642578l-14.8492432-14.8492432l29.2016602-29.2015991c-33.4263306-29.4012451-76.2097168-47.2977905-119.5015869-49.8238525v41.6218262h-21v-41.635376c-43.3592529,2.484436-86.1821899,20.2960815-119.5734253,49.7653809l29.2733765,29.2734375l-14.8492432,14.8492432l-29.4063721-29.4063721C82.7842407,173.8952026,63.9598999,214.8169556,62.1641235,262.5h41.0639648v20.6111145H62V324H451z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Protractor';
-->
