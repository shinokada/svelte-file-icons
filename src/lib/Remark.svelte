<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Remark';
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
    d="M58.3576736,122.3432007V78.889061H0v354.2218018h58.3571777V213.7223969C60.163929,143.2742767,94.3069305,121.122963,168.875,128.0691376V75.2025757C115.1862793,67.9662552,79.1359253,85.550148,58.3576736,122.3432007z M277.4318848,270.3539734h233.899353c6.9005127-117.8020782-39.4517517-195.0558777-145.9713745-197.1907806c-93.0263672,0-145.8929596,66.7499542-145.8929596,160.0900116v39.7676086c0,100.7916565,56.2393951,165.8160095,148.6382294,165.8160095c78.1233215,0,125.028717-43.4541626,138.5198975-102.1250916h-57.6512756c-11.4518127,33.0219727-38.4341431,53.5725098-79.5351868,53.5725098C316.255249,391.3765259,277.303772,349.3088989,277.4318848,270.3539734z M453.3662415,223.4380951l-175.9343567,0.0104828c0-55.9256134,34.3554382-101.7328262,88.3201599-101.7328262C418.6185913,121.7157516,453.3662415,167.1987305,453.3662415,223.4380951z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Remark';
-->
