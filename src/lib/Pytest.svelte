<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'pytest';
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
    d="M47.2890472,47.8176079V0h80.312355v47.8176079H47.2890472z M353.2745361,47.8176079V0h-80.3123779v47.8176079H353.2745361z M240.4380341,47.8176079V0h-80.3125v47.8176079H240.4380341z M489.4819336,63.1054382H22.5796967c-30.1062622,0.0000305-30.1062622,45.0886841,0,45.0886536h466.9022217C519.5060425,108.1940918,519.5060425,63.1054382,489.4819336,63.1054382z M466.111145,47.8176079V0h-80.3123474v47.8176079H466.111145z M385.7987976,123.4819183v117.1345367h80.3123474V123.4819183H385.7987976z M272.9621582,123.4819183v201.8516083h80.3123779V123.4819183H272.9621582z M160.1255341,123.4819183v311.2155762h80.3125V123.4819183H160.1255341z M47.2890472,123.4819183V512h80.312355V123.4819183H47.2890472z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'pytest';
-->
