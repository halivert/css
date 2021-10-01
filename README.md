# halivert.css

> Classless css stylesheet.
> Stylesheet to faster prototype.

- Modular.
- Easy to use.
- Customizable.
- Around 7KB.

## Usage

Add this to your html file

```html
<link rel="stylesheet" href="https://unpkg.com/halivert.css" />
```

And you're ready to go.
Optionally, add the suggested fonts:

```html
<link rel="preconnect" href="https://fonts.googleapis.com" />
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
<link
	href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&family=Raleway:wght@400;700&family=Ubuntu+Mono:wght@400;700&display=swap"
	rel="stylesheet"
/>
```

## Modules

If you want to use only some of the functionalities, I have divided the
stylesheet in modules:

- [base][1]: Foundations of the stylesheet, remove margins and add minor tweaks.
- [code][2]: Code, pre and kbd.
- [form][3]: All form styles.
- [layout][4]: Sets the grid of the body, and the colors.
- [links][5]: Anchor tag.
- [lists][6]: Only lists.
- [media][7]: Figures.
- [tables][8]: Stripped rows.
- [text][9]: Selection, mark and details.
- [titles][10]: Only titles.

[1]: https://github.com/halivert/css/blob/main/sass/base.scss
[2]: https://github.com/halivert/css/blob/main/sass/code.scss
[3]: https://github.com/halivert/css/blob/main/sass/form.scss
[4]: https://github.com/halivert/css/blob/main/sass/layout.scss
[5]: https://github.com/halivert/css/blob/main/sass/links.scss
[6]: https://github.com/halivert/css/blob/main/sass/lists.scss
[7]: https://github.com/halivert/css/blob/main/sass/media.scss
[8]: https://github.com/halivert/css/blob/main/sass/tables.scss
[9]: https://github.com/halivert/css/blob/main/sass/text.scss
[10]: https://github.com/halivert/css/blob/main/sass/titles.scss

### Example

If you only want to use forms.

```html
<link rel="stylesheet" href="https://unpkg.com/halivert.css/css/base.min.css" />
<link rel="stylesheet" href="https://unpkg.com/halivert.css/css/form.min.css" />
```

# Contributions

Issues and pull requests are welcome.

