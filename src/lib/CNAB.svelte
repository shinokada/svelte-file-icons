<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'CNAB';
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
    d="M244.2695465,287.0512085h165.6064606v165.6064758H244.2695465V287.0512085z M414.0161743,59.3422852H269.1105347V171.12677L202.8679199,38.6414795L99.3638916,245.6495972h207.0080566l-20.7008057-41.4016113h128.3450317V59.3422852z M151.8059235,59.3423195L59.3423195,238.7493286V59.3423195H151.8059235z M0,0v144.9056549h20.7008095V20.7008095h124.2048492V0H0z M324.3126831,0v20.7008095h124.204834v124.2048492h20.7008057V0H324.3126831z M448.5175171,367.0943298v124.2048645h-124.204834V512h144.9056396V367.0943298H448.5175171z M197.2507019,400.9657898c39.6477509-68.671936-10.2898254-155.0406952-89.671875-155.0906677S-21.6319771,332.131134,18.102335,400.8529968S157.602951,469.6376953,197.2507019,400.9657898z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'CNAB';
-->
