<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'WASI';
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
    d="M0,0v512c0,0,195.5027313-0.0348206,195.5027313-0.0523987c0-33.5697021,27.0864563-60.7832947,60.4993744-60.7832947c33.4128113,0,60.4992676,27.2135925,60.4992676,60.7832947C316.5013733,511.9651794,512,512,512,512V0H0z M210.1847687,268.2800598c-3.766983,37.2418823-43.8757172,47.0050964-91.8042755,47.0050964c-29.1376953,0-63.5759163-18.897583-63.5759163-55.764801l33.8570213-0.0000916c0,0,0.5620422,42.0762939,61.1259079,30.345459c42.4727173-8.2267151,31.7588501-44.5771637,4.2347107-50.5035858c-44.2521362-11.8981323-94.3457489-8.2311554-96.0675964-55.1042633c0.3826141-68.6833038,148.4631653-67.9179916,145.6477966-1.7949829h-34.2779694c1.5489502-36.4210205-78.4630661-33.0249329-77.4902115-1.6469574c0.3031921,9.781189-0.5901566,18.3648224,40.9425888,28.8113251C139.3368378,211.2772064,218.8535156,215.6341858,210.1847687,268.2800598z M282.3711853,313.7805481h-33.6719971v-178.053772h33.6719971V313.7805481z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'WASI';
-->
