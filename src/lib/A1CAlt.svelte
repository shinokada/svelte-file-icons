<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = '1C Alt';
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
    d="M433.8036194,79.1272736H87.5054474L0,256l87.5054474,176.8727417h346.2981567C476.6254272,432.8727417,512,397.4981995,512,354.6763611V157.3236389C512,114.5018234,478.4872742,79.1272736,433.8036194,79.1272736z M433.8038025,118.2254639c22.3418274,0,39.0982056,16.7563477,39.0982056,39.0981903v197.3527069c-0.0001831,22.3418274-16.7565613,39.098175-39.0983887,39.098175H117.294548c0,0-78.1963577-126.6036682-78.1963577-134.0509033l78.1963577-141.4981689H433.8038025z M350.0217896,235.5200043c-13.6784058-32.9733124-57.6777649-38.0210419-79.6305542-9.5905304c-23.1878662,31.6891479-1.7380981,74.2789612,36.8087769,74.7541504h119.1563416v37.2363586H307.2000122C221.5,334.25,200,238.75,250.210083,192.7695923c47.2904053-43.7007446,124.6932983-19.8923035,138.999939,42.750412C389.210022,235.5200043,350.0220032,235.5200043,350.0217896,235.5200043z M204.7999878,172.2181396v167.5636597h-37.2363281V237.3817749h-37.2363892v-37.2363281h37.2363892v-27.9273071H204.7999878z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = '1C Alt';
-->
