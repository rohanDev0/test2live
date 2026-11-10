# Black iframe site

A minimal black-background website with one small, centered iframe.

## Run locally

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

The production output is generated in `dist/`.

## Change the embedded page

Open `index.html` and replace the iframe's `src` value:

```html
src="https://example.com"
```

Some websites block being embedded in an iframe. If the page does not load, use a URL that allows iframe embedding.
