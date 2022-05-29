# Svelte-File-Icons

[![npm version](https://badgen.net/npm/v/svelte-file-icons)](https://www.npmjs.com/package/svelte-file-icons)
[![license](https://badgen.net/npm/license/svelte-file-icons)](https://github.com/shinokada/svelte-file-icons/blob/main/LICENSE)

930+ SVG file icon components for Svelte. Svelte-file-Icons support major CSS frameworks using the `class` props.

<p align="center">
<img width="400" src="https://raw.githubusercontent.com/shinokada/svelte-file-icons/main/static/images/file-icons1.png" />
<img width="400" src="https://raw.githubusercontent.com/shinokada/svelte-file-icons/main/static/images/file-icons2.png" />
<img width="400" src="https://raw.githubusercontent.com/shinokada/svelte-file-icons/main/static/images/file-icons3.png" />
<img width="400" src="https://raw.githubusercontent.com/shinokada/svelte-file-icons/main/static/images/file-icons4.png" />
<img width="400" src="https://raw.githubusercontent.com/shinokada/svelte-file-icons/main/static/images/file-icons5.png" />
</p>


## Icon name list

[Icon list](https://github.com/shinokada/svelte-file-icons/blob/main/icon-list.md)

## Installation

```sh
npm i -D svelte-file-icons
```

## Usages

In a svelte file:

```html
<script>
	import { Vite, Config, D3, Sublime, Svelte, VSCode, EJS } from 'svelte-file-icons';
</script>

<Vite />
<Config />
<D3 />
<Sublime />
<Svelte />
<VSCode />
<EJS />
```

## Size

Use the `size` prop to change the size of icons.

```html
<Vite size="40" />
<Config size="40" />
<D3 size="40" />
<Sublime size="40" />
<Svelte size="40" />
<VSCode size="40" />
<EJS size="40" />
```

## CSS HEX Colors

Use the `color` prop to change colors with HEX color code.

```html
<Vite color="#c61515" />
<Config color="#3759e5" />
<D3 color="#3fe537" />
```

## CSS framworks suport

Use the `class` prop to change size, colors and add additional css.

Tailwind CSS example:

```html
<Svelte class="h-24 w-24 text-blue-700 mr-4" />
```

Bootstrap examples:

```html
<Svelte class="position-absolute top-0 px-1" />
```

## Dark mode

If you are using the dark mode on your website with Tailwind CSS, add your dark mode class to the `class` prop.

Let's use `dark` for the dark mode class as an example.

```html
<Svelte class="text-blue-700 dark:text-red-500" />
```

## aria-label

All icons have aria-label. For example `Svelte` has `aria-label="svelte"`.
Use `ariaLabel` prop to modify the `aria-label` value.

```html
<Svelte ariaLabel="Awesome Svelte" />
```

## Passing down other attributes

You can pass other attibutes as well.

```html
<Svelte tabindex="0" />
```

## Using svelte:component

```html
<script>
	import { Svelte } from 'svelte-file-icons';
</script>

<svelte:component this="{Svelte}" />
```

## Using onMount

```html
<script>
	import { Svelte } from 'svelte-file-icons';
	import { onMount } from 'svelte';
	const props = {
		size: '50',
		color: '#ff0000'
	};
	onMount(() => {
		const icon = new Svelte({ target: document.body, props });
	});
</script>
```

## Import all

Use `import * as Icon from 'svelte-file-icons`.

```html
<script>
	import * as Icon from 'svelte-file-icons';
</script>

<Icon.Svelte />
<Icon.Vite />

<h1>Size</h1>
<Icon.Svelte size="30" />
<Icon.Vite size="40" />

<h1>CSS HEX color</h1>
<Icon.Svelte color="#c61515" size="40" />

<h1>Tailwind CSS</h1>
<Icon.Svelte class="text-blue-500" />
<Icon.Vite class="text-pink-700" />
```

## Other icons

- [Svelte-Icon-Sets](https://svelte-svg-icons.vercel.app/)
