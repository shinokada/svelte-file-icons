<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'HaxeDevelop';
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
    d="M493.0899963,457.9100037L255.9387054,62.6352654L18.9112701,457.7635803L493.0899963,457.9100037z M94.2563858,219.5873718l-67.4727325,203.229126L230.361908,83.4818954L94.2563858,219.5873718z M485.09375,422.7376709l-67.9345093-203.9611816L281.4929504,83.4255676L485.09375,422.7376709z M99.2118301,371.7529907H274.870697v11.2623596H99.2118301V371.7529907z M304.8961487,371.7529907h108.7041931v11.2623596H304.8961487V371.7529907z M77.4079208,416.8023987h91.4052353v11.2623596H77.4079208V416.8023987z M200.1788025,416.8023987h148.3476868v11.2623596H200.1788025V416.8023987z M377.2004089,416.8023987h61.0869751v11.2623596h-61.0869751V416.8023987z M258.0109863,44.086174l168.7437744,168.7550659L512,469.1130371L0,468.9939575l84.6383438-255.3418732L254.4070282,43.5568466C255.9024353,42.4222527,257.0550842,42.81567,258.0109863,44.086174z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'HaxeDevelop';
-->
