<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'WebAssembly';
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
    d="M394.2523499,320.6066895l16.9839783,66.5570984h-46.0523987l14.79599-66.5570984H394.2523499z M314.611908-0.0000467H512V512.000061H0V-0.0000467h197.3878021C197.3877869,81.8827438,314.6118774,81.8827438,314.611908-0.0000467z M152.6673737,275.9338684H118.746521l39.059021,181.2601929h34.3488617l27.0938873-123.3614502l25.1907806,123.3614502h33.6830292l43.197998-181.2601929h-33.2547302l-26.6895447,124.931488l-25.3572998-124.931488h-31.732605L176.098053,399.342926L152.6673737,275.9338684z M466.4232483,457.1940613l-53.3314514-181.2601929h-53.521637l-43.8638306,181.2601929h34.1110535l8.8964539-40.3436279h60.9432983l11.5606384,40.3436279H466.4232483z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'WebAssembly';
-->
