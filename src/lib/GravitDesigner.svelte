<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Gravit Designer';
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
    d="M33.5960426,351.4538574c-12.0182323-27.5296326-18.3200817-56.0758362-19.5085011-84.3855286L164.7533112,97.160881l76.384964-67.592514L33.5960426,351.4538574z M223.829834,17.3461418C177.6389618,66.2097855,102.3382187,140.7078247,16.0159283,225.1290436C29.8733978,122.4823074,109.4632339,31.847578,223.829834,17.3461418z M238.5095825,496.134613c5.5484467-155.042572,52.5004578-314.5883179,122.7523193-456.1974182c94.6600647,46.9653625,151.7835083,154.3086395,130.6081238,262.1862488c-85.4130249,59.8498535-165.8218079,154.5989685-194.989624,190.9461975C277.787323,496.3051147,258.3797302,497.6270447,238.5095825,496.134613z M512,256C512,59.6616783,297.9924927-63.7160034,127.7110519,34.4531555s-170.2813873,344.9245605,0.000061,443.093689S512,452.3383179,512,256z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Gravit Designer';
-->
