<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Meteor';
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
    d="M0 4.991l438.476 464.452c0 0 14.938 10.536 26.361-1.756s2.636-24.584 2.636-24.584l-467.473-438.113z"
  ></path><path
    d="M138.836 48.89l333.909 359.972c0 0 14.938 10.536 26.361-1.756s2.636-24.584 2.636-24.584l-362.907-333.633z"
  ></path><path
    d="M41.3 142.834l333.909 359.972c0 0 14.938 10.536 26.361-1.756s2.636-24.584 2.636-24.584l-362.906-333.633z"
  ></path><path
    d="M256.204 86.644l233.282 251.491c0 0 10.437 7.361 18.417-1.227s1.841-17.175 1.841-17.175l-253.542-233.089z"
  ></path><path
    d="M73.433 251.703l233.283 251.491c0 0 10.437 7.361 18.417-1.227s1.841-17.175 1.841-17.175l-253.542-233.089z"
  ></path><path
    d="M376.087 141.078l105.731 114.331c0 0 5.163 3.449 9.111-0.575s0.911-8.048 0.911-8.048l-115.753-105.708z"
  ></path><path
    d="M131.806 367.597l105.732 114.331c0 0 5.162 3.449 9.111-0.575s0.911-8.048 0.911-8.048l-115.753-105.708z"
  ></path></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Meteor';
-->
