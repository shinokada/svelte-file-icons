<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Cordova';
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
    d="M465.4983521,500.5552979H382.614563l5.7825623-69.8729553h-40.7190247l-5.7825928,69.8729553H170.1044617l-5.7825928-69.8729553h-40.7190475l5.7825851,69.8729553H46.5016441L0,197.6922455L116.374588,11.444706h279.2507935L512,197.6922455L465.4983521,500.5552979z M372.2541199,104.688942h-74.6917725l5.0597534,34.93647h-93.2442169l5.0597687-34.93647h-74.6917725l-46.7425919,93.0033035l23.3712997,186.2475433h279.2507935l23.3713074-186.2475433L372.2541199,104.688942z M196.3670044,282.5039978c0-33.262085-9.6679535-54.1637573-17.3605652-37.5327148c-7.6925964,16.6310425-7.6925812,58.4343872,0.0000153,75.0654297S196.3670044,315.7660828,196.3670044,282.5039978z M343.1000061,278.8890076c0-33.2621002-9.6679688-54.1637726-17.3605652-37.5327301s-7.6925964,58.4344025,0,75.0654449S343.1000061,312.1510925,343.1000061,278.8890076z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Cordova';
-->
