<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Stylus Orb';
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
    d="M127.7110596,34.453125c-170.2814331,98.1691895-170.2813721,344.9245605,0.000061,443.093689S512,452.3383179,512,256S297.9924927-63.7160034,127.7110596,34.453125z M339.543396,160.1678467l-7.2876587-5.0697021c36.4382324-41.5078125-7.2875977-71.6090088-27.8831177-40.557312c-19.328125,29.1505737,6.9707642,65.2719727,22.8134766,112.1663208c25.0314331,74.1438599,21.229248,114.0674438-11.0899048,152.7236328c-81.4314575,96.9573364-233.8381958,59.885437-181.2404785-40.557312c18.06073-34.5371094,49.4292603-59.251709,102.9775391-53.2314453c5.0697021,6.3370361-0.3168335,8.8718872-4.1190796,10.7730103c-43.4089966,21.5460815-68.4404297,108.0471802-30.7348022,106.1460571c18.0606689-0.633667,44.9932251-18.694397,58.9348145-49.4291992c16.1595459-35.8045044-3.8022461-80.7977295-18.0606689-123.2562256c-33.2697144-100.1258545,42.1415405-186.6269531,128.3258667-141.633728C404.8153076,105.3521118,383.2692871,165.2374878,339.543396,160.1678467z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Stylus Orb';
-->
