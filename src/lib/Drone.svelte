<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Drone';
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
    d="M512,272.7478943H357.2092896c-30.3825073-117.1049042-176.8392181-106.0812836-202.4185791,0H0C13-23.8898182,475-50.5564842,512,272.7478943z M59.5348587,308.468811h95.2558212c26.8759918,104.9747009,168.2093201,116.3080444,202.4186096,0h95.2558289C404.3333435,513.4435425,136.3333282,538.7768555,59.5348587,308.468811z M321.4884949,290.6088562c0-50.226181-54.7462158-81.7879791-98.3066559-56.6748962s-43.5604401,88.2366943,0.0000153,113.349762C266.7423096,372.3968201,321.4884949,340.835022,321.4884949,290.6088562z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Drone';
-->
