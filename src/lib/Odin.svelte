<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Odin';
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
    d="M90.0761566,452.8389893L344.8582764,11.5241251C704.1462402,180.816803,420.0758972,682.5715332,90.0761566,452.8389893z M362.9530334,70.4307251L149.9002991,438.6415405C383.2495728,563.7615356,600.7075806,239.4835052,362.9530334,70.4307251z M301.1986389,3.2728307L60.3563766,423.2029419C-87.0823135,228.6764832,51.8651428-32.2359543,301.1986389,3.2728307z M224.7775421,46.5009079c0,0-89.5439301,12.350914-148.2106323,98.0351791c-59.6329041,87.0954285-15.4386024,189.8948517-15.4386024,189.8948517L224.7775421,46.5009079z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Odin';
-->
