<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'CocoaPods';
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
    d="M497.8897705,5H14.1102295C6.3496094,5,0,11.3496094,0,19.1102295v473.779541C0,500.6503906,6.3496094,507,14.1102295,507h483.779541C505.6503906,507,512,500.6503906,512,492.8897705V19.1102295C512,11.3496094,505.6503906,5,497.8897705,5z M183.333313,404c-65.6293335-4.272644-135.1008911-50.4210205-140.333374-140C31.5470581,67.9297485,312.4368286,51.9724121,335.4161987,223H266.999939c-17.2642212-87.1252441-156.6072998-76.5736694-156.9852295,34.0009766C109.6998291,349.1073608,235.3753662,378.2228394,266.999939,294h70.0002441C323.406311,365.9830322,255.7182617,408.7124634,183.333313,404z M407.333313,395.333313l-43-18l52.7602539-121.8953857L365,132.333313l42.81427-18.3877563L468,256.3334351L407.333313,395.333313z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'CocoaPods';
-->
