<script>
  import { getContext } from 'svelte';
  const ctx = getContext('iconCtx') ?? {};
  export let size = ctx.size || '24';
  export let role = ctx.role || 'img';
  export let color = ctx.color || 'currentColor';
  export let ariaLabel = 'RDoc';
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
    d="M401.9462585,421.3902893v64.9683533h-64.9683533L401.9462585,421.3902893z M213.7170715,452.8630676H33.4955101V50.9168167h234.468689l100.4865417,100.4865952v1.0506744h33.4955139v-34.5462494L301.4597168,17.4213085H0v468.9373474h247.2126465L213.7170715,452.8630676z M402.0476379,172.7216492H182.1429443L72.1905975,282.6739807l219.9047089,219.9047241L512,282.6739807L402.0476379,172.7216492z M127.1667786,282.6739807l82.4642639-82.4642487h164.9285278l82.4642639,82.4642487L292.0953064,447.6025085L127.1667786,282.6739807z M374.5595703,227.6978149h-82.4642639v192.416626l137.4404297-137.4404602L374.5595703,227.6978149z"
  /></svg
>

<!--
@component
[Go to docs](https://svelte-file-icons.codewithshin.com/)
## Props
@prop export let size = ctx.size || '24';
@prop export let role = ctx.role || 'img';
@prop export let color = ctx.color || 'currentColor';
@prop export let ariaLabel = 'RDoc';
-->
