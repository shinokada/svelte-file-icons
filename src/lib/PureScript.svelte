<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'PureScript';
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
    d="M188.2068176,368.1990967l-39.9728546-37.3269043h175.53508l39.9728394,37.3269043H188.2068176z M188.2068176,237.3486023l-39.9728546,37.3269348h175.53508l39.9728394-37.3269348H188.2068176z M363.7295227,181.1401825l-39.9604797-37.3392944H148.2463226l39.960495,37.3392944H363.7295227z M129.7637787,218.0805511l-26.4066544-26.4067383l-97.9088135,97.896347c-3.5155382,3.515564-5.4600935,8.2149048-5.448256,13.2037048c0,4.9888,1.9327178,9.6763916,5.448256,13.1912842l97.9088135,97.9087524l26.4066544-26.394989l-84.7050476-84.7050476L129.7637787,218.0805511z M506.5275269,196.0465851L408.655304,98.1261063l-26.394989,26.4067383l84.6567993,84.7056656l-84.6567993,84.7050629l26.394989,26.3943787l97.8722229-97.8840027C510.0548401,218.9142914,512,214.2149506,512,209.2261505C511.9876404,204.2373505,510.0548401,199.5621338,506.5275269,196.0465851z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'PureScript';
-->
