<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Meson';
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
    d="M512,442.9060059C511.7919312,261.5803833,415.0180664,93.4453125,258.0566406,2.8759074l-0.0250244-0.0015883C99.3798599,92.4575958,0.9029443,260.3049622,0,442.6091919C165.9948425,533.1116943,360.9474182,529.3682861,512,442.9060059z M343.4773865,196.976181c23.523407,15.9853668,20.0331421,54.4673157,16.2442627,80.81987c-4.8192749,29.0284119-32.6390076,76.7597961-68.7972717,107.9030457c4.6787109,6.7061462,7.3804016,14.9644775,7.3426819,23.7755432c-22.4064636,11.3257141-44.6246796-1.4477234-71.5140839-24.4747925c-26.8889923-23.0266724-55.8920135-69.1709595-65.5166626-116.59021c-8.5362854,0.9033508-17.2726898-0.9998474-24.7702179-5.7287903c1.9567719-26.589386,30.17836-42.3960876,55.188797-51.719162c25.010849-9.322876,89.4494476-12.4651184,134.8793793,3.684845c3.544281-7.4373779,9.4050903-13.6815491,16.9439087-17.643158L343.4773865,196.976181z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Meson';
-->
