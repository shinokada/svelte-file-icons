<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Test Generic';
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
    d="M33.9144897,413.6118164h149.5499878v27.5949097H27.4943848c-26.3479614,0-34.1365356-13.1942139-21.729248-34.3093262l132.1444092-219.1445923V61.9752808h-26.0749512c-19.5040283,0-19.5040283-27.5949097,0.0004883-27.5949097h189.9300537c19.5045166,0,19.5045166,27.5949097,0,27.5949097h-26.0755005v132.828064h-27.9630127V61.9752808h-81.8540649v132.828064L33.9144897,413.6118164z M169.5146484,244.4245605L84.690979,386.5740051l70.6011353,0.0004578l104.3745422-112.9078064l-15.5819397-29.2420959H169.5146484z M315.5102844,254.2075195l-106.009491,113.2981567l106.009491,110.2862549l33.5378418-33.5378418l-80.6507874-76.7484131l80.6507874-79.7603149L315.5102844,254.2075195z M372.4526672,287.7453613l80.6507874,79.7603149l-80.6507874,76.7484131l33.5378418,33.5378418L512,367.5056763L405.990509,254.2075195L372.4526672,287.7453613z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Test Generic';
-->
