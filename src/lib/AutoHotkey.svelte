<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'AutoHotkey';
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
    d="M151.5456848,399.1699524l33.5879364-89.7650757h115.4033661l36.95047,89.7650757h61.0211487L264.9179077,74.6542969l-52.5053558,0.8540573L91.2973099,399.1699524H151.5456848z M240.0840759,162.5452576l37.2266541,90.4365997h-71.0653076L240.0840759,162.5452576z M512,64.6079102c0-30.0682564-24.4632568-54.5315094-54.5385132-54.5315094H54.5315094C24.4632568,10.0763988,0,34.5396538,0,64.6079102v378.1938171c0,47.4665833,33.4139328,59.1218872,53.8177643,59.1218872h413.6816406C484.7246094,501.9236145,512,486.8453369,512,442.8017273V64.6079102z M54.3502083,24.4080982l372.2339478-0.0008221c19.2987976,0,33.8722534,20.7576828,33.8722534,50.6758842s0,291.5744019,0,291.5744019c0,45.1609802-30.3866272,81.7701721-67.8696289,81.7701721H108.286293c-46.3750458,0-83.969986-36.6091919-83.969986-81.7701721c0,0,0-293.5719604,0-310.0350647S37.4622116,24.5612068,54.3502083,24.4080982z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'AutoHotkey';
-->
