# css-forms

Functional CSS for forms

## Filesize

| File | Size |
|------|------|
| `dist/forms.css` | 1 bytes |
| `dist/forms.min.css` | 0 bytes (20 Gzipped) |

## Install

```sh
npm install css-forms
```

## Usage

### Import

```css
@import "css-forms";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-forms/dist/forms.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-forms/dist/forms.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|


### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.example-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/forms.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/forms.css` — formatted
- `dist/forms.min.css` — minified

## License

MIT
