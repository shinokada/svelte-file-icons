<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Kivy';
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
    d="M447.69 205.966c3.584-0.435 4.453 1.304 1.846 3.91l-89.166 89.057-74.721-74.612 162.040-18.355zM341.147 311.096c0 4.779-1.846 9.231-5.213 12.598l-52.891 52.565c-3.367 3.367-7.928 5.213-12.707 5.213s-9.34-1.846-12.707-5.213l-52.782-52.783c-8.58-8.58-16.073-26.717-16.073-38.881v-133.476l147.269 147.269c3.366 3.367 5.213 7.928 5.104 12.707zM113.184 322.065c-5.974-6.082-5.974-15.856 0-21.938l58.864-58.864v139.667l-58.864-58.865zM157.713 210.202c5.974 6.082 5.974 15.857 0 21.83l-58.864 58.865v-139.559l58.864 58.864zM437.020 74.981c-48.352-48.352-112.64-74.981-181.019-74.981s-132.667 26.628-181.019 74.981c-48.352 48.352-74.981 112.639-74.981 181.019s26.628 132.668 74.981 181.019c48.352 48.352 112.639 74.981 181.019 74.981s132.668-26.629 181.019-74.981c48.351-48.352 74.98-112.639 74.98-181.019s-26.629-132.667-74.98-181.019z"
  ></path></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Kivy';
-->
