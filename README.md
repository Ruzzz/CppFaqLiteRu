# Перевод "Краткий FAQ по C++"

Сохраняю здесь, чтоб не потерялся.

- [Оригинал на английском](http://www.dietmar-kuehl.de/mirror/c++-faq/)
- [Скачать html версию](https://github.com/Ruzzz/CppFaqLiteRu/releases)

# Конвертировать в html

```
pandoc -f markdown-raw_html -t html -s CppFaqLiteRu.md -o CppFaqLiteRu.html
```

# Сделать красиво

```html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/kube/6.5.2/css/kube.min.css"/>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/highlight.js/9.7.0/styles/default.min.css"/>
<script src="https://cdnjs.cloudflare.com/ajax/libs/highlight.js/9.7.0/highlight.min.js"></script>
<script>hljs.initHighlightingOnLoad();</script>
<style type="text/css">
body {
    width: 800px;
    margin: 30px auto;
}
pre code {
    padding-left: 30px !important;
}
</style>
```