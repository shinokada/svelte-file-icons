<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Wercker';
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
    d="M0,264.0000305h35.5570602V132.8000031L191.991394,40l156.4589539,92.8000031v166.4000092c0,25.6000061-9.2503052,46.4000244-25.2503052,68.8000183c-38.6819763,52.7999878-108.8000336,91.1999817-131.2000275,102.3999939c-22.0442963-11.2000122-86.4000092-46.3999939-128.0000153-96h206.2085266c14.940033-14.3999939,19.3914795-19.2000122,32.1914673-36.7999878H4.9430642C33.8478012,440.0000305,182.0000153,512,182.0000153,512c-0.0406342,0,168.4000092-70.3999634,197.2000275-174.3999634c3.0143738-11.2000122,4.7999878-25.6000061,4.7999878-38.4000244V112L191.991394,0L0,112V264.0000305z M282.0440979,163.2000122v30.3999939H99.1263046v-30.3999939H282.0440979z M297.239563,217.6000061v30.4000092H83.8379364v-30.4000092H297.239563z M293.4016418,270.4000244v30.3999939H80.0000076v-30.3999939H293.4016418z M232.4589539,110.4000015v30.4000015h-83.8379364v-30.4000015H232.4589539z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Wercker';
-->
