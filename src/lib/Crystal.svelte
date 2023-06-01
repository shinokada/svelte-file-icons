<script>
  export let size = '24';
  export let role = 'img';
  export let color = 'currentColor';
  export let ariaLabel = 'Crystal';
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
    d="M510.923 324.993l-185.416 184.901c-0.515 0.515-1.545 0.515-3.091 0.515l-252.887-67.471c-0.515 0-1.545-0.515-2.060-2.060l-67.471-252.371c0-0.515 0-2.060 0.515-3.090l185.416-184.9c0.515-0.515 1.545-0.515 3.090-0.515l252.887 67.986c0.515 0 1.545 0.515 2.060 2.060l67.471 252.371c1.030 1.030 0.515 2.060-0.515 2.575zM263.188 124.126l-248.251 66.956c-0.515 0-0.515 0.515 0 1.545l181.81 181.811c0.515 0.515 0.515 0 1.545 0l66.955-247.736c-1.030-2.575-2.060-2.575-2.060-2.575z"
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
