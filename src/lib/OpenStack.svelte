<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'OpenStack';
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
    d="M464.4281921,5.4559383H47.5713348C21.4070969,5.4559383,0,26.8630333,0,53.0272636v112.1009216h115.6247406v-18.3193512c0-14.2097321,11.5228195-25.728157,25.7325439-25.728157H370.646698c14.2096252,0,25.7281494,11.518425,25.7281494,25.728157v18.3193512h115.6247559V53.0272636C511.9996033,26.8630333,490.5924377,5.4559383,464.4281921,5.4559383z M396.3752441,365.1911621c0,14.2097473-11.5183716,25.7325745-25.7281494,25.7325745H141.3577576c-14.2097244,0-25.7326126-11.5228271-25.7326126-25.7325745v-18.3149719H0.0004033v112.0965271c0,26.1686401,21.4070988,47.5713501,47.5713348,47.5713501h416.8569946c26.1642151,0,47.5712585-21.40271,47.5712585-47.5713501V346.8761902H396.3752441V365.1911621z M0.0030917,313.8141174h115.6247406V198.1893921H0.0030917V313.8141174z M396.3735046,313.8141174h115.6247559V198.1893921H396.3735046V313.8141174z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'OpenStack';
-->
