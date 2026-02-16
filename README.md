# css-animation-play-state

Functional CSS for animation-play-state

## Filesize

| File | Size |
|------|------|
| `dist/animation-play-state.css` | 545 bytes |
| `dist/animation-play-state.min.css` | 423 bytes (139 Gzipped) |

## Install

```sh
npm install css-animation-play-state
```

## Usage

### Import

```css
@import "css-animation-play-state";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-animation-play-state/dist/animation-play-state.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-animation-play-state/dist/animation-play-state.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.a-running` | `animation-play-state: running;` |
| `.a-paused` | `animation-play-state: paused;` |
| `.a-running-s` | `animation-play-state: running;` |
| `.a-paused-s` | `animation-play-state: paused;` |
| `.a-running-m` | `animation-play-state: running;` |
| `.a-paused-m` | `animation-play-state: paused;` |
| `.a-running-l` | `animation-play-state: running;` |
| `.a-paused-l` | `animation-play-state: paused;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.a-running-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/animation-play-state.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/animation-play-state.css` — formatted
- `dist/animation-play-state.min.css` — minified

## License

MIT
