<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Moustache';
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
    d="M55.1558876,248.5812836c1.4362183-7.9670258-2.5345993-15.0987396-10.9114647-14.4231873c-11.3637581,0.9164276-19.2700691,24.5676117,4.9030876,32.4378815c19.8188896,6.4526062,34.2473259-8.4853516,57.0795937-31.5335541c51.017952-51.5004272,112.6209793-56.4952698,150.1885986-4.5062714c15.4844055-28.4930115,76.5196533-75.9898376,169.7158203,22.5314178c34.2359924,36.1921844,64.8265991,2.1566315,48.0670166-16.523056c-7.6231689-8.4965057-22.5246277,3.3690186-15.0209656,12.0167694h-1.5020752c-34.9783936-31.0209503,38.0841064-60.0064087,52.5628967-7.5104828c14.9598999,79.0168152-68.3929749,91.8624268-135.1676636,63.0775452c-129.0569-64.5886688-130.4335175-47.2378235-255.3352051,6.0083923c-38.331131,15.7136841-85.2765274,6.735321-104.2267303-11.4334412c-22.5065975-21.5784912-21.1144371-72.8563995,8.1031084-83.1880951C53.431942,203.5727997,78.6595688,229.1815338,55.1558876,248.5812836z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Moustache';
-->
