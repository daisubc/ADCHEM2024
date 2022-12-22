# ADCHEM 2024

The International Federation of Automatic Control (IFAC) is pleased to announce the 12th IFAC Symposium on Advanced Control of Chemical Processes (ADCHEM 2024) that will be held in Toronto, July 14-17, 2024. The International Program Committee is preparing an exciting scientific program that explores recent advances in the control of chemical, biochemical and related process systems. Both academic and industrial control engineering practitioners will have the opportunity to present their work and exchange research ideas with colleagues from across the globe.

## Instructions

See below for instructions on how to update this website. This website is built using Markdown files.

*If you are not familiar with Markdown, please start with this tutorial*:

- The Biochemistry Department at UW Madison compiled a [list of resources](https://bcrf.biochem.wisc.edu/2021/06/03/do-yourself-a-favor-learn-markdown-master-it-in-10-minutes/) to learn Markdown in 10 minutes.

### Updating the home page

Modify the `index.md` Markdown file. You may see references to other page snippets known as *includes*, for example:

```
# Conference Location

{% include /_info/location.html %}
```

These page snippets help us re-use the same content across multiple locations in the website. You can find and modify these snippets in the `_info` folder.

### Updating other pages

Find and modify the Markdown file in the `_pages` folder. You may also see snippets from other pages.

### Updating the navigation bar
Edit the `navbar-links` in the `_config.yml` file.

### Updating announcements

1. Add your announcements in `_data/announcements.yml`

### Adding sponsors

1. Upload the sponsor's logo to `assets/img/sponsors`
2. Add the sponsor's information in `_data/sponsors.yml`

## License

Copyright (C) ADCHEM 2024 Organizing Committee. Website design and framework developed by [Siang Lim](https://www.siang.ca).

#### MIT License
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
