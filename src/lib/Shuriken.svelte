<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Shuriken';
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
    d="M328.8759766,132.5421448C371.3331909,201.1544342,478.1032104,73.603653,499.8647461,16.565836c61.182312,226.6875153-128.5315552,308.9147949-135.4263916,328.8926086c7.2550049,69.3253784,51.509552,118.1947937,131.3958435,156.3851624c-99.1514587,29.8260803-238.6083679-6.4488525-316.8009644-121.7224731C143.0673523,327.0992737,30.8019505,430.3282166,13.780839,496.2008667c-34.3766518-113.4429626,2.4183283-172.5073853,35.5939369-230.9724121c38.4000206-67.671936,102.2507477-75.3491211,97.4141083-117.2668152C140.0868835,89.8777008,73.1363449,30.5032635,14.5869474,13.3414001C131.6380463-32.9872322,278.9995422,51.9401283,328.8759766,132.5421448z M303.8504028,263.709137c0-40.709198-44.3727722-66.2905884-79.6792755-45.9359894s-35.3065033,71.5173798,0.0000153,91.8719635C259.4776611,329.9997253,303.8504028,304.418335,303.8504028,263.709137z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Shuriken';
-->
