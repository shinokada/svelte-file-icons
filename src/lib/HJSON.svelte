<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'HJSON';
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
    d="m216.49131 118.74839 7.13118 40.44524-84.81615-34.03526c-3.64276-5.50777-2.67105-13.94254 3.73527-15.16933 3.7384-1.11961 73.9497 8.75935 73.9497 8.75935zm68.38624 177.72013-18.12121 3.19519-16.95028-96.12778 18.1219-3.19521zm222.31606-85.09886c34.87271 126.04705-129.86496 103.64235-177.58324 129.63909-15.8189 8.61808-21.48029 27.54648-15.11153 55.35329l-37.94355 6.94146s-4.14918-27.13712-10.60829-33.83152c-37.17078-52.99352-253.61966 91.58565-265.947-65.31288l38.216651-6.9915c11.649345 119.29641 205.68705-37.33335 248.74633 56.62416 2.26547-97.20794 211.69337-23.46614 182.01328-135.43059zm-232.34432-58.1673c-14.22809-9.14905-14.22809-32.14588-1e-5 -41.29493 14.22809-9.14906 32.10977 2.34935 32.10977 20.64746 0 18.29812-17.88167 29.79653-32.10976 20.64747z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'HJSON';
-->
