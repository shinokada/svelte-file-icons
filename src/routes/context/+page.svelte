<script>
  import { setContext } from 'svelte';
  import { Wget } from '$lib';
  const iconCtx = {
    size: '100', // Icon size in pixels
    color: '#004488', // Icon color in hexadecimal or CSS color name
    role: 'svg icon image'
  };
  setContext('iconCtx', iconCtx);
</script>

<Wget />