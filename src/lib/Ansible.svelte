<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Ansible';
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
    d="M260.8456726,115.0143204l89.6253662,221.2051086L215.0935211,229.5816193L260.8456726,115.0143204z M512,256c0,196.3383179-214.0074463,319.7159424-384.2888794,221.546814s-170.2814941-344.9244995-0.000061-443.093689S512,59.6616821,512,256z M420.0633545,387.1765747L282.2013855,55.4023056c-7.2346802-19.6264496-35.9119873-19.2634583-43.3018036,0L87.5868073,419.3171082h51.7616882l59.8983765-150.0432129l178.7501678,144.4087219C399.886322,434.3363647,431.002594,413.5922241,420.0633545,387.1765747z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Ansible';
-->
