<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Wenyan';
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
    d="M0,113V85c36.3502502,0,42-17.1597824,42-23c0-11.7970734-20.7081203-14.1384277-20-32c1.599905-40.3559227,58.1625748-39.6151428,68,0C101.493454,76.2839584,68.4420471,117.0046387,0,113z M125,106h175V65H125V106z M0,187h125v-41H0V187z M173,187h127v-41H173V187z M0,267h125v-41H0V267z M173,267h127v-41H173V267z M125,348v-41H20v205h105v-41H66V348H125z M173,307v41h59v123h-59v41h105V307H173z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Wenyan';
-->
