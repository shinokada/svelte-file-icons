<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'CSound';
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
    d="M507.6217346,256c0,141.3848877-113.6350098,256-253.8108673,256S0,397.3848877,0,256S113.6349945,0,253.8108673,0S507.6217346,114.6151047,507.6217346,256z M215.6563568,242.3917999V189.372818c-25.6212616-18.4081268-86.6242371-29.998703-126.8862152,8.4331818s-34.771698,130.7072449,0,160.5987244c34.7717056,29.891449,91.5581055,34.0544128,133.0401306-1.9373474l-16.5244293-31.8824158c-24.9148712,20.8981628-95.1571808,35.4889832-95.1571808-45.5913696c0-93.9445801,67.0958099-64.7167816,67.0958099-64.7167816v29.9450836L215.6563568,242.3917999z M252.1441345,193.0489655c0,84.9120941,121.8994751,58.5955811,122.6979675,109.9611664c0.692627,44.5536499-78.4560547,41.8171082-81.5155945,25.0490417v-29.7192078l-40.6112061,1.3849792v61.9322205c45.2813721,35.6053772,173.5054016,30.304657,173.5054016-59.3868713c0-93.937149-125.5278015-70.1617737-125.5278015-117.5817566c0-34.6777191,57.5913391-40.8885803,72.5011902-24.1080933v32.240799l43.2705383-5.0906525v-62.7847214C323.0457153,92.4281387,252.1441345,116.2035217,252.1441345,193.0489655z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'CSound';
-->
