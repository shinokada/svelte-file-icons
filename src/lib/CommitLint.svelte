<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'CommitLint';
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
    d="M512,512H0V0h512V512z M332.2546082,329.7055664h134.597168v-20.7943726H332.2545776C332.2546082,308.9111938,332.2546082,329.7055664,332.2546082,329.7055664z M387.5117188,350.7772522L347.2097778,410h22.7722168l29.6530762-38.5892639L429.1242981,410h22.7722168l-40.3019409-59.2227478H387.5117188z M151.2420807,248.0971832c-2.907074-28.0629883-21.3528442-43.6038818-51.3151855-43.6038818c-34.9900055,0-54.7786865,20.4612274-54.7786865,56.7919464v14.0862732c0,36.4490356,19.788681,56.7919617,54.7786865,56.7919617c29.8506165,0,48.5198364-15.4269714,51.3151855-42.8152466h-25.4889069c-2.2367172,13.5254517-11.7400131,20.9037476-26.0497284,20.9037476c-18.3340454,0-28.3959732-13.1924438-28.3959732-37.2245178v-9.3937683c0-24.0364685,10.0619278-37.2245331,28.3959732-37.2245331c14.1979904,0,23.924736,7.7113037,26.0497284,21.6880188H151.2420807z M284.137085,329.7055054v-20.79422h-38.1227264V160h-64.7266998v20.79422h38.7930756v128.1170654h-40.1337891v20.7941589L284.137085,329.7055054z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'CommitLint';
-->
