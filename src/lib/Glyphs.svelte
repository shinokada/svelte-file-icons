<script>
  export let size = '24';
  export let role = 'img';
  export let color = 'currentColor';
  export let ariaLabel = 'Glyphs';
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
    d="M282.6425171,308.126709c-30.1176453,0-44.0180817-16.2171936-44.0180817-56.7601929c0-44.0180969,18.5339508-55.6018066,99.6199493-55.6018066c44.0180969,0,91.511322,3.4751129,149.4298706,9.2669678l18.5338745-191.1312256C444.8144836,4.6334796,375.3122253,0,304.6515808,0C82.2443237,0,0,71.8190002,0,256.0000305C0,444.8144836,81.0859756,512,301.1764832,512c61.3936768,0,126.2624207-4.6335144,203.873291-19.6923218V240.9411621H296.5429993v67.1855469C296.5429993,308.126709,288.4343872,308.126709,282.6425171,308.126709z"
  /></svg
>
<!--
@component
[Go to Document](https://svelte-file-icons.codewithshin.com/)
## Props
@prop size = '24';
@prop role = 'img';
@prop ariaLabel = 'icon file name';
@prop color = 'currentColor';
## Event
- on:click
- on:keydown
- on:keyup
- on:focus
- on:blur
- on:mouseenter
- on:mouseleave
- on:mouseover
- on:mouseout
-->
