<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'PowerShell';
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
    d="M404.8582458,448.6902771H20.4225502c-13.1145916,0-22.8270435-12.1893005-19.8982811-24.9726868L76.0642395,94.0028839c4.0007706-17.9367981,15.6179581-30.6931534,33.9955215-30.6931534h382.2444458c12.6442261,0,22.0103149,11.7490616,19.1922302,24.0752411L434.249939,425.2598877C431.1157532,438.968689,418.9207764,448.6902771,404.8582458,448.6902771z M130.0076141,397.1522522l176.8035431-126.9797363c10.7348328-7.7538452,13.0192261-24.3576813,3.2654114-33.7968445L193.2624359,112.3276749c-19.2472687-20.43927-52.1007843,10.49823-32.8535156,30.9375076l99.1439667,105.2854919L103.6828232,360.4981689C78.7735443,378.3879089,105.0983276,415.0419922,130.0076141,397.1522522z M346.1577148,353.2391357h-93.8386993c-27.0326996,0-27.0326996,40.8302612,0,40.8302612h93.8386993C372.7884521,394.069397,372.7884521,353.2391357,346.1577148,353.2391357z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'PowerShell';
-->
