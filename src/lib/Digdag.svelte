<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'Digdag';
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
    d="M48.6336098,214.7301483c65.5636749-90.1705627,132.5703583-138.5000305,171.8410645-154.9160309C373.7820435-4.2716713,416.6377258,80.4530182,512,69.8309937c-21.5674133,47.2024536-65.9227905,76.5788574-138.8544922,75.2991791c17.8272095,17.7961884,36.2743225,29.4030304,55.2654724,35.5771332c-61.9141235,69.1364594-98.7870178,165.1055908-113.2941895,295.6702576c-44.9195557-4.1118469-93.8516846-34.3338928-145.0718536-79.4441223c-19.5532074,14.2935791-46.2571182,21.2955627-84.4525375,16.5796814c7.8756104-22.7272644,20.7867737-43.5162659,36.095253-63.3825684c-27.6192017,16.1191406-61.6874466,21.2003174-99.3051453,20.2064209c11.0798645-33.9889526,28.0638008-61.4994812,50.7751579-82.7254944C50.927681,297.3508301,27.1533775,303.9637451,0,308.0838318C3.9136379,265.1106873,20.8236866,235.5531921,48.6336098,214.7301483z M369.550415,77.1719666c0-10.5147781-11.4610291-17.1221886-20.5803528-11.8647995c-9.1192932,5.2573853-9.1192932,18.4722137,0,23.729599C358.089386,94.2941589,369.550415,87.6867447,369.550415,77.1719666z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'Digdag';
-->
