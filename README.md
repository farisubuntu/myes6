# Quick modification:


1. checkout to `gh-pages` branch
2. fix / add / modify `es-6.md`
3. when ready, do:

```bash
$ pandoc es6.md -s -o index.html --template templates/default.html5 --metadata title='ES6'
--no-highlight
```

> add your custom styles in `custom.css` 

**related to pandoc:**


- custom styles by generate a `json` file my.theme: [https://pandoc.org/chunkedhtml-demo/13-syntax-highlighting.html](https://pandoc.org/chunkedhtml-demo/13-syntax-highlighting.html)
