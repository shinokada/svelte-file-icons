<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'TemplateToolkit';
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
    d="M83.6208878,46.5444107l353.4684448-2.6461334c110.0090027,10.3597565,92.8681946,178.9690552-12.3677673,180.2234497l-77.1717529,1.8474426v163.045105c0.0934753,101.3328857-174.3762817,107.7906189-177.198822,4.8591003V224.9948883h-76.698967C-24.3169346,231.6262512-34.3480606,53.1757622,83.6208878,46.5444107z M294.378418,389.0142822V170.9428253h129.7637634c40.6680603,0,49.1228638-68.7852097,10.2156067-73.9039001L84.9586487,99.7062378c-46.389225,3.8050613-40.5847168,73.1528473,5.9208374,71.2365875h128.173233v222.6326752C226.0404205,424.2557068,296.3792419,422.0565491,294.378418,389.0142822z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'TemplateToolkit';
-->
