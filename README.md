# CSS Stories

CSS Stories (CSSS) is a lightweight collection of pure CSS classes to easily define *one-page* layouts for *Scrollytelling* and similiar use cases.

## How to Use

Include a link to the stylesheet (`../csss.css`) in your `<head>` tag.

```html
<link rel="stylesheet" href="../story-container.css" />
```

## Documentation

- All stories are block elements with a smooth scroll behaviour and (block) snapping of its children enabled.
- All direct children of stories snap to their start position.

### story-horizontal

- Horizontal stories don't wrap their elements.
- All children in horizontal stories are displayed as blocks and have a width of 100%.

Example:

```html
<div class="horizontal-story">
    <!-- story sections here -->
</div>
```

### story-vertical

- Vertical stories do wrap their elements normal.
- All children in vertical stories are displayed as blocks and have a height of 100%.

Example:

```html
<div class="vertical-story">
    <!-- story sections here -->
</div>
```

### -hidden (Scrollbars)

Stories with the -hidden suffix don't show their scrollbars.

Examples:

```html
<div class="horizontal-story-hidden">
    <!-- story sections here -->
</div>
```

```html
<div class="vertical-story-hidden">
    <!-- story sections here -->
</div>
```

### -disabled (Scrollbars)

Stories with the -disabled suffix don't show their scrollbars nor do they allow scrolling (e.g. with mouswheel).

Examples:

```html
<div class="horizontal-story-disabled">
    <!-- story sections here -->
</div>
```

```html
<div class="vertical-story-disabled">
    <!-- story sections here -->
</div>
```

## Demo

Check out the [CSS Stories Demo](www.google.com) page to get an idea of how CSSS can be used (you can check the source in your browser or directly in the repo right [here](https://www.gitlab.com/web-utilz/csss/demo/demo.html)).
