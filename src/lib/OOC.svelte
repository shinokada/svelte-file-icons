<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'OOC';
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
    d="M201.5739594,228c4.3344421-100.8123779,54.1499329-174.099762,136.0000153-228l2,16c0,0-9,20-8,32s49,32,55,68c-0.3999329,14.7746887-22.5647583,12.2936554-53.3696899,8.802597c0,0-7.5154114,56.0742645,12.1605225,87.5557404c8.1069946,12.9712067,0.1827698,54.6852417,0.9934998,91.9775085c0.6387939,29.3850403-21.8438721,67.6260071-40.8810425,74.4249878C280.9888916,387.5066833,258.8998413,414.5335083,280.5739746,470l10,21l-67.0000153,2c0,0-3-51-17-51s-68-26-68-39s-34.9999924,11-34.9999924,33s18,49,18,49s-3.8276291,13.8320923-37.9767456,9.7667236C85.2233658,506.9628296,69.573967,512,69.573967,512c-13.3076019-2.0720825-16.0103188-18.0463562-24.1912384-18.0463562c-17.0745583,0-12.8320007-36.2215881-16.2798595-93.3911438L8.7943888,381.7494202L7.5739646,292c0,0-20-33,4.9999995-52s40-34,64-16C88.573967,233,201.5739594,228,201.5739594,228z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'OOC';
-->
