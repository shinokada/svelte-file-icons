<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'V Ray';
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
    d="M182.8466492,333.4407654c-23.6625061-2.1510925-109.7079849-189.2997742-32.2670593-277.4962158c71.8761749-72.7859497,211.4444885-34.5088196,268.8921204,32.2670097C264.0532532,47.2164726,221.8232574,339.4697571,182.8466492,333.4407654z M255.9852905,473.2644653c-204.4552002,1.479187-319.5592957-265.5831909-137.67276-410.8665466C25.8136444,165.6523438,129.068222,389.3703003,187.1489105,395.8237c73.1386871,4.3022766,101.1034393-228.0202179,187.1489105-258.1361084C500.4248657,96.6117249,527.8666382,458.2854004,255.9852905,473.2644653z M264.5898438,38.7354813c-87.8465118,1.3848534-90.3968811,37.9693069-2.151123,38.7203979C349.6344604,76.5187378,351.7145081,39.7368965,264.5898438,38.7354813z M512,256C512,59.6616783,297.9924927-63.7160034,127.7110519,34.4531555s-170.2813721,344.9245605,0.000061,443.093689S512,452.3383179,512,256z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'V Ray';
-->
