<script>
  export let size = '24';
  export let color = 'currentColor';
  export let ariaLabel = 'Spray';
</script>

<svg
  version="1.1"
  xmlns="http://www.w3.org/2000/svg"
  width={size}
  height={size}
  viewBox="0 0 512 512"
  fill={color}
  class={$$props.class}
  {...$$restProps}
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
  ><style type="text/css">
    .st0 {
      fill: #181816;
    }
  </style><path
    class="st0"
    d="M386.2128906,512H65.9689941c-35.7232018,0-65.4998627-28.416626-65.9633942-64.1368103C-0.4653673,411.5692139,28.8142662,382,65,382h253v-59H61.5019531C27.5353622,323,0,295.4646301,0,261.4980469V64.0839844C0,28.1390915,29.1390915-1,65.0839844-1l315.9470215-0.0000001c35.7232056,0,65.4998779,28.4166203,65.9633789,64.1368179C447.4653625,99.4307709,418.18573,129,382,129H125v64h258.8085938C419.2605286,193,448,221.7394714,448,257.1914062v193.0214844C448,484.3369751,420.3369751,512,386.2128906,512z"
  /></svg
>
<!--
@component
[Go to Document](https://svelte-file-icons.codewithshin.com/)
## Props
@prop size = '24';
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
