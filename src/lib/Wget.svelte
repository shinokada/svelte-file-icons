<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Wget';
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
    d="M477,30H36C15.4975586,30,0.0005493,45.4975586,0,66v378c-0.0005493,20.5028076,15.4971924,37.9993896,36,38h439c20.5028076,0.0005493,36.9994507-17.4971924,37-38V66C512.0005493,45.4967651,497.5032349,30,477,30z M285.8339844,244.4248047l49.1816406,43.5166016v-132.5h40v132.5005493l49.1826172-43.5161743l26.5058594,29.9570312l-95.6884766,84.6650391l-95.6875-84.6660156L285.8339844,244.4248047z M97.1850586,281.1269531l-28.2841797-28.2851562l70.8344727-70.8320312l-70.8344727-70.8359375L97.1850586,82.890625l99.1186523,99.1191406L97.1850586,281.1269531z M459,433H252v-40h207V433z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Wget';
-->
