<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Kotlin';
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
    d="M477.3764648,483.9453125c-14.684906,16.1938171-34.8822937,24.4255066-55.1483765,24.4255066c-17.8322449,0-35.7146912-6.3686523-49.966217-19.2909546L197.9376678,330.9917908c-0.9297028-0.8431702-1.8313141-1.7056274-2.7084961-2.584137l137.4603119-76.1317291L472.2418823,378.830719C502.6872559,406.4405823,504.9836731,453.499939,477.3764648,483.9453125z M173.8935547,94.2127762V79.5800552C173.8935547,35.6288719,138.2646942,0,94.3135071,0S14.7334547,35.6288719,14.7334547,79.5800552v102.7822037L173.8935547,94.2127762z M13.8556614,427.1002502v4.4418945C13.8556614,475.9781189,49.8775291,512,94.3135071,512s80.45784-36.0218811,80.45784-80.4578552v-93.564209L13.8556614,427.1002502z M488.8136292,42.0739937C468.8990173,6.1214604,423.6128235-6.8814387,387.6629333,13.0305309L17.1914558,218.212677v170.1320496l442.5773621-245.1187134C495.7213745,123.3140411,508.7255859,78.0265274,488.8136292,42.0739937z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Kotlin';
-->
