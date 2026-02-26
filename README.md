# @light-aos.js

This is literally just animate on scroll. All you gotta do is add `aos` to your elements and choose your animation. That's it.

## Installation

```html
<script src="light-aos.min.js"></script>
```

## Size

- **minified:** ~3KB
- **compressed (tar.gz):** ~1KB

That's it. That's the whole library.

## Mobile Support

Not applicable - this is a pure UI library.

## Quick Start

```html
<h1 aos="fade">Hello</h1>
<h2 aos="fade;down">World</h2>

<script src="light-aos.min.js"></script>
```

## Usage

### Effects

```html
<div aos="fade">Fade in</div>
<div aos="zoom">Zoom in</div>
<div aos="flip">Flip in</div>
```

### Simple scroll effects

```html
<div aos="hide-scroll-down">Visible when scrolling up, hidden when scrolling down</div>
<div aos="show-scroll-down">Only visible when scrolled 30%+ and scrolling down</div>
```

### Direction

```html
<div aos="fade;top">From top</div>
<div aos="fade;down">From bottom</div>
<div aos="fade;left">From left</div>
<div aos="fade;right">From right</div>
<div aos="fade;top-left">From top-left</div>
<div aos="fade;top-right">From top-right</div>
<div aos="fade;down-left">From down-left</div>
<div aos="fade;down-right">From down-right</div>
```

Combine effect and direction with semicolon:

```html
<div aos="zoom;left">Zoom in from left</div>
<div aos="flip;top">Flip in from top</div>
```

### Distance

Default distance is 20px. Change it:

```html
<div aos="fade;top=50px">Move 50px from top</div>
```

### Duration

```html
<div aos="fade;top;500">500ms animation</div>
```

### Easing

```html
<div aos="fade;top;300;linear">Linear easing</div>
<div aos="fade;top;300;ease-in">Ease in</div>
<div aos="fade;top;300;ease-out">Ease out</div>
<div aos="fade;top;300;ease-in-out">Ease in out</div>
```

Or cubic-bezier:

```html
<div aos="fade;top;300;cubic(0.175, 0.885, 0.32, 1.275)">Custom cubic</div>
```

### Once

By default, animations play every time you scroll. To play only once:

```html
<div aos="fade;top;300;once">Animates only once</div>
```

## Browser Support

Chrome, Firefox, Safari, Edge.

## License

MIT
