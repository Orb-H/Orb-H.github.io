# Jekyll One

## Useful if...

* You want to create an "about me" page from a single markdown file and host it under a custom domain name.
* You want to create a single-page website that's mostly text, like [Know Your Company](https://knowyourcompany.com/).
* You want to share a single markdown file and tried GitHub Gist ([example](https://gist.github.com/dypsilon/5819504)), but would like something nicer-looking.
* You want something like GitHub's [automatic page generator](http://pages.github.com/) for a non-code repository.

This page itself is built with Solo. It's generated from [this markdown file](https://github.com/chibicode/solo/blob/gh-pages/_includes/index.md).

## Usage

First, [install Jekyll](http://jekyllrb.com/docs/installation/). Then download Solo from its [GitHub Repository](https://github.com/chibicode/solo). Start Jekyll and you should see this page up and running.

### Files

* Edit `_config.yml` to change the site's title and description.
* Edit `_includes/head.html` to add custom code to `<head>`.
* Edit `_includes/scripts.html` to add custom code before `</body>`.
* Edit `CNAME` to host on a custom domain.
* Edit `README.md` before pushing your code.

### Don't use `<h1>` tags

Wthin `index.md`, do not use `<h1>` tags - `<h1>` is reserved for the site title.

### Supported Tags

Solo supports lists, `<hr>`s, `<table>`s,

> blockquotes, and...

~~~html
<pre>code blocks with syntax highlighting.</pre>
~~~

### License

[MIT License](http://chibicode.mit-license.org/)
