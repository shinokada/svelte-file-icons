<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Houdini';
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
    d="M82.7739639,512H0v-93.1856079C15.5832949,458.3516235,45.6715431,491.2770081,82.7739639,512z M0,212.9211426v89.8017273c54.4722748-149.1810303,276.3323059-146.3903351,291.7906799,12.4942017c5.3787842,144.5567017-188.1092072,152.7427368-189.2344513,44.2501221c1.9424286-27.0896301,22.7369919-45.4233093,49.4558563-44.510437c-21.6329956,24.2358704,0.3437195,61.9799805,32.2767029,54.4016418c24.8375549-4.8024292,42.6275787-26.7654114,42.1676483-52.0589905c-12.6356506-95.6646881-177.0074158-64.1298676-175.1783142,45.0310669c-1.8222542,70.2796326,64.0327072,116.6120605,130.1474304,117.3930359c102.0355225,1.8219299,160.6018677-62.9914551,160.6018677-158.5196838C337.6936035,152.4540405,126.0070114,87.6815109,0,212.9211426z M407.6218262,321.2038269C411.4629211,399.9098511,370.157959,473.9359131,301.1613159,512H512V0H0v147.3268738C150.7511444,31.0304604,405.8204041,95.4954453,407.6218262,321.2038269z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Houdini';
-->
