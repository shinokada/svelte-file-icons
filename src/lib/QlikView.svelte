<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'QlikView';
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
    d="m150.92298 271.66807c-23.05869-63.81434 31.88856-128.90649 98.66764-116.88464 66.77911 12.02187 95.75898 92.2229 52.03855 144.0154-43.72041 51.79248-127.6475 36.68356-150.70619-27.13076zm75.60343-263.68282c-153.44182 4.1923296-267.6722 160.02364-212.3702 313.07052 54.330781 150.35904 236.28539 198.40345 357.2134 110.42843l85.68074 72.59459 54.94965-66.69259-81.12197-68.78881c116.89897-187.34547-36.34717-364.53799-204.35162-360.61214zm2.8289 88.61139c9.85408-0.26925 19.97765 0.46849 30.26301 2.32009 109.71048 19.75057 157.32527 151.51991 85.49757 236.60911-71.82769 85.08918-209.71621 60.26944-247.59903-44.57027-34.33129-95.01098 36.582284-191.75634 131.83845-194.35893z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'QlikView';
-->
