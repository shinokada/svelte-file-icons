<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Strings';
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
    d="M378.283 64.148h-14.361v58.404c-2.143 14.636-10.959 18.011-23.936 14.362l-285.39-72.765h-20.032c-46.248 0-40.865-64.148 0-64.148h343.719c44.652 0 49.823 64.148 0 64.148zM61.23 137.362l285.074 69.833c21.371 5.236 29.344-27.313 7.974-32.548l-285.075-69.832c-21.811-5.343-29.784 27.205-7.972 32.548zM61.23 206.776l285.074 69.832c21.371 5.236 29.344-27.313 7.974-32.548l-285.075-69.832c-21.811-5.343-29.784 27.206-7.972 32.548zM61.23 276.19l285.074 69.832c21.371 5.236 29.344-27.313 7.974-32.548l-285.075-69.832c-21.811-5.343-29.784 27.205-7.972 32.548zM332.063 451.981l-260.3-66.543c-10.544-3.038-19.538-1.944-22.834 14.353v50.886h-23.485c-33.924 0-33.924 61.324 0 61.324h361.861c30.873 0 41.312-61.324-8.058-61.324l-47.183 1.305zM348.182 419.027c63.296 0.877 92.592 22.329 93.56 73.411 0.425 22.471 33.93 21.837 33.505-0.634-3.772-83.618-56.93-104.678-122.791-106.969l-283.252-69.386c-21.811-5.342-29.784 27.205-7.972 32.548l286.952 71.030z"
  ></path></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Strings';
-->
