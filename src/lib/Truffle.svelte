<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Truffle';
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
    d="M205.1043549,486.6675415c-0.6417236,17.8714905-103.0670853-17.9546814-157.5139771-62.4330139C207.3560791,603.2116089,479.4619446,485.516449,490,277.0112305C457.5218811,379.3476562,326.8509827,398.468689,199.245285,313.834259C44.5386276,201.0399933,82.4550247,29.7963257,240.0841827,13.7807026c104.9976044-7.41185,213.1708527,84.4387207,177.0770721,156.3765259c-44.0438538,80.6804962-192.5512695,16.0308228-180.7579193-67.3549118c2.6979828-26.8078537,29.8852692-43.467392,21.9844818-16.4316864c-19.2488861,61.3997421,96.1730957,107.696907,122.241333,49.5705338c24.8137817-63.9482269-116.1818848-111.9157867-160.4762115-69.1332474C108.6619415,178.7281189,370.7311401,322.63974,443.3773804,213.0899048C495.074585,130.7575836,374.6342773-5.6237822,238.0560303,0.1793406C17.3901825,3.4578915-73.1395721,248.8959503,66.9882736,390.4570618C146.857132,468.5036316,207.0772858,474.7788696,205.1043549,486.6675415z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Truffle';
-->
