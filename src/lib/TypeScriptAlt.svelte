<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'TypeScript Alt';
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
    d="M0,0v512h512V0H0z M294.4450989,222.2295074h-72.8156281v225.5530853l-40.1008606-0.000061V222.2295074h-72.6645889v-37.2979736h185.5810852V222.2295074z M443.6569519,424.7886963c-24.4429932,31.8499451-94.5575867,36.7136841-135.3250732,10.2143555v-49.8566589c22.1905823,24.2348938,45.1519165,27.6982117,63.0422668,29.3413391c55.8893738,4.6504517,57.5086975-41.9042969,34.8855591-61.1010437c-33.3111572-26.8851318-99.6495972-41.8435974-97.578125-99.9373474c-0.4820251-41.6179657,31.8292236-69.5560608,79.9127502-72.1525879c18.2202759-0.983902,44.1927185,0.1495972,60.526886,10.6986389v46.8667297c-38.3365173-35.1743927-118.1293945-25.7407379-98.7814941,26.4697876c17.5126953,32.2354431,77.7337036,35.4049988,103.0762634,86.453064C464.1708374,380.5033264,458.1839294,405.8595581,443.6569519,424.7886963z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'TypeScript Alt';
-->
