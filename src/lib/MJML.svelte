<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'MJML';
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
    d="M289.6430054,149.25H62.6445847c-83.5732727,0-82.8099136-119-2.0001259-119h225.9983673C378.3079529,30.25,374.3103027,149.25,289.6430054,149.25z M444.3747253,200.75H218.376358c-80.8097992,0-81.5731506,119,2.0001221,119h226.9984283C532.0421753,319.75,536.039856,200.75,444.3747253,200.75z M286.6428223,363.25H60.6444588c-80.8097916,0-81.5731506,119,2.0001259,119h226.9984131C374.3103027,482.25,378.3079529,363.25,286.6428223,363.25z M120,260.25c0-46.0167999-50.1580048-74.9334412-90.0677185-51.9250336s-39.9096985,80.8416901,0.0000134,103.8500824S120,306.2667847,120,260.25z M512,89.75c0-46.0167923-50.15802-74.9334412-90.0677185-51.9250412s-39.9096985,80.8416977,0,103.85009S512,135.7667999,512,89.75z M512,422.25c0-46.0167847-50.15802-74.9334412-90.0677185-51.9250488s-39.9096985,80.8417053,0,103.8500977S512,468.2667847,512,422.25z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'MJML';
-->
