<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Microsoft Outlook';
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
    d="m0 57.690141v391.81221l298.06573 62.49765v-512zm150.16744 287.02768c-94.754452-6.11092-84.995376-176.90624 2.21145-178.26253 93.4227 6.17457 84.25838 176.90008-2.21145 178.26253zm1.36533-144.82148c-49.9185 3.46583-47.68409 110.40624-0.7692 111.26505 49.70332-3.20373 46.78409-110.43451 0.7692-111.26505zm197.31951 68.11282c4.49983 3.30757 9.92271 0 9.92271 0-5.40365 3.30757 147.62907-98.34246 147.62907-98.34246v184.07001c0 20.03771-12.82644 28.44124-27.24898 28.44124h-162.26314l0.01-136.11027zm-31.94111-159.45554v100.15008l34.99869 22.03763c0.92304 0.26922 2.92297 0.28845 3.84601 0l150.62894-101.55387c0-12.01878-11.21112-20.63384-17.53779-20.63384z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Microsoft Outlook';
-->
