<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Atoum';
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
    d="M488.3023987,70.4250183V46.3937378h-21.3611145v47.0613251h-24.0312805v23.0299149H69.0899963V93.4550629H46.0600815V46.3937378h-22.362484v24.0312805H0v115.8176422h23.0300407v23.3636017h116.8187561v22.6858368h-24.0312881v23.7078094H92.7875977v46.7275085h47.061203v46.7275085h22.3624878v69.4237061h24.0312805v23.3637085h22.696228v23.3639221h94.1223907v-23.3639221h22.6962585v-23.3637085h23.0299072v-69.4237061h23.3638611V302.727417h47.0611877v-46.7275085h-23.0299072V232.292099h-24.0312805v-22.6858368h116.8187561v-23.3636017H512V70.4250183H488.3023987z M208.9343414,256.66745v-47.0612488h24.0312805V256.66745H208.9343414z M243.8564453,385.2515869H208.938797v-23.7281494h23.2809143v11.3592224h11.636734V385.2515869z M303.0611877,385.2515869h-34.8764954v-12.368927h10.9865112v-11.3592224h23.8899841V385.2515869z M303.0612488,256.66745h-24.0312805v-47.0612488h24.0312805V256.66745z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Atoum';
-->
