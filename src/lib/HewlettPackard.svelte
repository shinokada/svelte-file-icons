<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'HewlettPackard';
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
    d="M249.2702026,511.9648438l52.2069397-143.4865112h72.1177368c12.6569519,0,26.5518188-9.7312927,30.8813171-21.627655l56.8478699-156.1607056c9.3022461-25.5572662-5.3337708-46.4826965-32.5389099-46.4826965H328.730896L197.2765503,505.3395081C-47.7753601,448.8968811-79.6285629,93.4835281,187.4709015,9.2141361l-130.7612,359.2641907H111.05159l69.4263916-190.5720062h40.8465881l-69.4263916,190.5720062l54.3221283,0.0097351l64.6976318-177.7984161c9.3022461-25.5569458-5.3437805-46.4823761-32.5194397-46.4823761H192.715271L245.1706238,0.03515C599.4024658,2.8821478,601.1053467,506.0979919,249.2702026,511.9648438z M371.0205383,177.7702026L313.841156,334.6525879h40.8271179l57.1793823-156.8823853H371.0205383z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'HewlettPackard';
-->
