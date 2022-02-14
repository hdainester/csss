# CSS Stories

CSS Stories (CSSS) is a lightweight collection of pure CSS classes to easily define *one-page* layouts for *Scrollytelling* and similiar use cases.

## How to Use

Include the `<link>` to the stylesheet in your `<head>` tag.

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/web-utilz/csss@v1.0.0/csss.css" />
```

## Documentation

- All stories are block elements with a smooth scroll behaviour and (block) snapping of their children enabled.
- All direct children of stories snap to their start positions.

### story-horizontal

- Horizontal stories don't wrap their elements.
- All children in horizontal stories are displayed as blocks and have a width of 100%.

Example:

```html
<div class="story-horizontal">
    <!-- story sections here -->
</div>
```

### story-vertical

- Vertical stories do wrap their elements normal.
- All children in vertical stories are displayed as blocks and have a height of 100%.

Example:

```html
<div class="story-vertical">
    <!-- story sections here -->
</div>
```

### -hidden (Scrollbars)

Stories with the -hidden suffix don't show their scrollbars.

Examples:

```html
<div class="story-horizontal-hidden">
    <!-- story sections here -->
</div>
```

```html
<div class="story-vertical-hidden">
    <!-- story sections here -->
</div>
```

### -disabled (Scrollbars)

Stories with the -disabled suffix don't show their scrollbars nor do they allow scrolling (e.g. with mouswheel).

Examples:

```html
<div class="story-horizontal-disabled">
    <!-- story sections here -->
</div>
```

```html
<div class="story-vertical-disabled">
    <!-- story sections here -->
</div>
```

## Demo

Check out the [CSS Stories Demo](https://web-utilz.gitlab.io/csss) page to get an idea of how CSSS can be used.

> You can view the source in your browser or in the repository right [here](https://github.com/web-utilz/csss/blob/master/public/index.html).

<p>
    <a href="http://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fweb-utilz.gitlab.io%2Fcsss%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=">
        <img style="border:0;width:88px;height:31px"
            src="https://jigsaw.w3.org/css-validator/images/vcss-blue"
            alt="CSS ist valide!" />
    </a>
</p>
