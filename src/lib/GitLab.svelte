<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'GitLab';
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
    d="M256.0004272,491.8162537l94.2719421-290.1400146H161.7344971L256.0004272,491.8162537z"
  /><path
    d="M29.6064854,201.6762543L0.9559237,289.8457947c-2.6114008,8.0434875,0.2494971,16.8548889,7.0926433,21.8226624l247.9518585,180.1477966L29.6064854,201.6762543z"
  /><path
    d="M29.6064854,201.6762543h132.122467L104.9462357,26.9274158c-2.9205017-8.9915886-15.6406784-8.9915886-18.5597992,0L29.6051006,201.6762543H29.6064854z"
  /><path
    d="M482.3934937,201.6762543l28.6505737,88.1695404c2.6113892,8.0434875-0.2494812,16.8548889-7.0926514,21.8226624L256.0004272,491.8162537L482.3934937,201.6762543z"
  /><path
    d="M482.3941956,201.6762543H350.2709961l56.7827454-174.7488403c2.921875-8.9915886,15.6420593-8.9915886,18.562561,0L482.3941956,201.6762543z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'GitLab';
-->
