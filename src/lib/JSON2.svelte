<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'JSON 2';
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
    d="m127.45223 34.272471c-169.93631 97.968619-169.93631 345.46291 0 443.43151 169.9363 97.9686 384.54777-25.74845 384.54777-221.71576 0-146.97549-120.71871-253.31042-254.83439-255.98597-44.77864-0.18102993-88.55694 10.543443-129.71338 34.270218zm267.8263 107.48894c28.84087 106.82281-12.55299 207.36135-109.50264 229.0692 75.78765-57.07418 61.78676-161.17368 22.8985-209.06347-52.6181-65.754677-135.37955-45.60156-180.32992 2.46109-67.501501 78.11361-50.141533 213.82163 10.90115 289.24995-149.08263-90.65169-151.48071-307.36315 0.85637-395.18578 97.90387-59.405432 212.15384-37.902651 255.17654 83.469008zm19.42359 150.34478c31.35519-79.33931 10.60661-179.4546-46.63558-237.62016 68.99429 38.408577 117.65929 111.3811 118.60626 201.50219 1.58899 151.21827-191.40041 297.12853-303.39708 190.71564-112.10599-106.51677-82.78028-288.43631 42.52854-304.50301-92.9601 78.87787-51.16226 218.17395 29.02661 243.6682 72.45841 23.03651 137.55616-37.29808 159.87125-93.76286zm-160.15902-141.22373c82.90916 40.64978 77.57939 173.01161-2.20916 209.8671-82.20711-56.09905-63.28271-170.22023 2.20916-209.8671z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'JSON 2';
-->
