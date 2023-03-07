<h1 align="center">Svelte File Icons</h1>

<p align="center">
<a href="https://svelte-file-icons.codewithshin.com/">Svelte-File-Icons</a>
</p>

<p align="center">
<a href="https://github.com/sponsors/shinokada" target="_blank"><img src="https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub&color=%23fe8e86" height="25"></a>
<a href="https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps" target="_blank"><img src="https://img.shields.io/badge/PWA-enabled-brightgreen" alt="PWA Shield" height="25">
</a>
<a href="https://www.npmjs.com/package/svelte-file-icons" rel="nofollow" target="_blank"><img src="https://img.shields.io/npm/v/svelte-file-icons" alt="npm" height="25"></a>
<a href="https://twitter.com/shinokada" rel="nofollow" target="_blank"><img src="https://img.shields.io/badge/created%20by-@shinokada-4BBAAB.svg" alt="Created by Shin Okada" height="25"></a>
<a href="https://opensource.org/licenses/MIT" rel="nofollow" target="_blank"><img src="https://img.shields.io/github/license/shinokada/svelte-file-icons" alt="License" height="25"></a>
<a href="https://www.npmjs.com/package/svelte-file-icons" rel="nofollow" target="_blank"><img src="https://img.shields.io/npm/dw/svelte-file-icons.svg" alt="npm" height="25"></a>
</p>

930+ SVG file icon components for Svelte. Svelte-file-Icons support major CSS frameworks using the `class` props.

Thank you for considering my open-source package. If you use it in a commercial project, please support me by sponsoring me on GitHub: https://github.com/sponsors/shinokada. Your support helps me maintain and improve this package for the benefit of the community.

<p align="center">
<img width="650" src="/static/images/file-icons-650-1050-optimized.png" />
</p>

## Installation

```sh
npm i -D svelte-file-icons
```

## Icon names

[Icon list](/icon-list.md)

## Icon images

[Icon images](/icon-images.md)

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

## Faster compiling

If you only need to use a couple of icons from this library in your Svelte app, importing it directly. This can help optimize compilation speed. 
By importing only what you need, you can reduce the amount of code that needs to be processed, which can improve overall performance.

```html
<script>
  import Vite from 'svelte-file-icons/Vite.svelte';
</script>

<Vite />
```

If you are TypeScript user, **this require `"typescript": "^5.0.0"`.**

As of March 2023, the `typescript@beta` version is now available:

```sh
pnpm i -D typescript@beta
```

To avoid any complaints from the editor, add `node16` or `nodenext` to `moduleResolution` in your tsconfig.json file.

```json
{
  //...
  "compilerOptions": {
    // ...
    "moduleResolution": "nodenext"
  }
}
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

## Unfocusable icon

If you want to make an icon unfocusable, add `tabindex="-1"`.

```html
<Svelte tabindex="-1" />
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

## PWA: Fast & Offline

This website can be downloaded and installed on your device for offline access as a Progressive Web App.

To install a PWA, look for the "Add to Home Screen" option in the browser's menu or settings. On most mobile devices, this option can be found by visiting the website, then selecting the "Options" or "Menu" button in the browser, and looking for the "Add to Home Screen" option. On some desktop browsers, right-click on the page and select "Install".
