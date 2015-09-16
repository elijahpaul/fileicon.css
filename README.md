Languages: [中文文档]

# Intro

Pure CSS file icons. Help you create file icons with pure CSS codes. (eg. doc, pdf, png, zip and so on).

See the [DEMO]

# Usage

```html
<div class="file-icon file-icon-xl" data-type="doc"></div>
```

Will display:

![doc](https://dl.kraken.io/web/55/23d2ac7012d4820d049febc3879424/pdf2.png)

## Type

Use attribute `data-type` to define the file type, We had already defined some file type styles, includes:

- doc, docx
- xls, xlsx
- ppt, pptx
- pdf
- zip

## Size

Use class `file-icon-xx` for size define, We support some size below:

- xs  (12x16)
- sm  (18x24)
- default (24x32)
- lg  (48x64)
- xl  (96x128)

## Custom

Use `data-type` css selector to style your file type colors:

```css
.file-icon[data-type=custom] {
  background: #38A240;
}
```

# Who are using

- PUBU.im - [https://pubu.im](https://pubu.im)

# License

Copyright (c) 2014-2015 Picturepan2. MIT Licensed, see [LICENSE] for details.

[DEMO]: https://picturepan2.github.io/fileicon.css
[LICENSE]: https://picturepan2.github.io/fileicon.css/LICENSE
[中文文档]: https://github.com/picturepan2/fileicon.css/blob/master/README_CN.md
