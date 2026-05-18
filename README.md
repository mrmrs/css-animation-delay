# css-animation-delay

Functional CSS for animation-delay

## Filesize

| File | Size |
|------|------|
| `dist/animation-delay.css` | 1201 bytes |
| `dist/animation-delay.min.css` | 863 bytes (187 Gzipped) |

## Install

```sh
npm install css-animation-delay
```

## Usage

### Import

```css
@import "css-animation-delay";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-animation-delay/dist/animation-delay.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-animation-delay/dist/animation-delay.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.a-delay-1` | `animation-delay: .5s;` |
| `.a-delay-2` | `animation-delay: 1s;` |
| `.a-delay-3` | `animation-delay: 2s;` |
| `.a-delay-4` | `animation-delay: 4s;` |
| `.a-delay-5` | `animation-delay: 8s;` |
| `.a-delay-6` | `animation-delay: 16s;` |
| `.a-delay-1-s` | `animation-delay: .5s;` |
| `.a-delay-2-s` | `animation-delay: 1s;` |
| `.a-delay-3-s` | `animation-delay: 2s;` |
| `.a-delay-4-s` | `animation-delay: 4s;` |
| `.a-delay-5-s` | `animation-delay: 8s;` |
| `.a-delay-6-s` | `animation-delay: 16s;` |
| `.a-delay-1-m` | `animation-delay: .5s;` |
| `.a-delay-2-m` | `animation-delay: 1s;` |
| `.a-delay-3-m` | `animation-delay: 2s;` |
| `.a-delay-4-m` | `animation-delay: 4s;` |
| `.a-delay-5-m` | `animation-delay: 8s;` |
| `.a-delay-6-m` | `animation-delay: 16s;` |
| `.a-delay-1-l` | `animation-delay: .5s;` |
| `.a-delay-2-l` | `animation-delay: 1s;` |
| `.a-delay-3-l` | `animation-delay: 2s;` |
| `.a-delay-4-l` | `animation-delay: 4s;` |
| `.a-delay-5-l` | `animation-delay: 8s;` |
| `.a-delay-6-l` | `animation-delay: 16s;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.a-delay-1-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/animation-delay.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/animation-delay.css` — formatted
- `dist/animation-delay.min.css` — minified

## License

MIT
