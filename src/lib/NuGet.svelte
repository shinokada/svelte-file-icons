<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'NuGet';
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
  ><style type="text/css">
    .st0 {
      fill: #181816;
    }
  </style><path
    class="st0"
    d="M219.0230103,70.4013443h152.1773376C448.9618835,70.4013443,512,133.4394684,512,211.200943v152.1770782c0,77.7615356-63.0381165,140.7996521-140.7996521,140.7996521H219.0230103c-77.7614746,0-140.7995605-63.0381165-140.7995605-140.7996521V211.200943C78.2234497,133.4394684,141.2615356,70.4013443,219.0230103,70.4013443z M99.5571442,57.6008949c0-38.1775055-41.6132317-62.1679955-74.7240448-43.0792427s-33.1107979,67.0697327,0.0000095,86.1584854S99.5571442,95.7783966,99.5571442,57.6008949z M241.7779236,196.978363c0-40.3776093-43.9901428-65.7506256-78.992218-45.5618134s-35.0020523,70.9348297,0.0000153,91.1236267S241.7779236,237.3559723,241.7779236,196.978363z M448.0001221,363.3781128c0-69.8232727-76.0916443-113.6997528-136.6362-78.7881165s-60.5445557,122.6646118,0,157.5762634S448.0001221,433.201416,448.0001221,363.3781128z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'NuGet';
-->
