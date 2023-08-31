<script>
  export let size = '24';
  export let role = 'img';
  export let color = 'currentColor';
  export let ariaLabel = 'SPARC';
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
    d="M201.5238647,511.9998474l-105.3897705-247.66922h110.4954224L150.257431,134.3630676L63.0672264,315.9495544H0L150.257431,0l135.3339691,315.9495544H172.3361053L201.5238647,511.9998474z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.vercel.app/)
## Props
@prop export let size = '24';
@prop export let role = 'img';
@prop export let color = 'currentColor';
@prop export let ariaLabel = 'SPARC';
-->
