<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Kusto Alt';
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
    d="M0,71.0102692v378.3574219l286.5257874,46.9164734V15.7158461L0,71.0102692z M167.5589447,345.2483826l-55.8529892-84.9402466v84.9402466H69.2576981V168.753006h42.4482574v81.1729126l55.8529892-81.1729126h46.9164734l-61.4382477,86.2462921l73.4466705,90.2490845H167.5589447z M304.8484497,82.1611481v120.4666138h30.6838989v191.8541718h-30.6838989v40.2510986H512V82.1611481H304.8484497z M400.2701111,394.4819336h-49.8547058V258.7727661h49.8547058V394.4819336z M467.8682556,394.4819336H415.460968V144.7398529h52.4072876V394.4819336z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Kusto Alt';
-->
