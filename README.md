### quill
---
https://github.com/quilljs/quill

```
<link href="https://cdn.quilljs.com/1.0.0/quill.snow.css" rel="stylesheet">
<div id="toolbar">
  <button class="ql-bold">Bold</button>
  <button class="ql-italic">Italic</button>
</div>
<div id="editor">
  <p>Hello</p>
</div>
<script src="https://cdn.quilljs.com/1.0.0./quill.js"></script>
<script>
  var editor = new Quill('#editor', {
    modules: { toolbar: '#toolbar' },
    theme: 'snow'
  });
</scirpt>

<script src="//cdn.quilljs.com/1.0.0/quill.js"></script>
<script src="//cdn.quilljs.com/1.0.0/quill.min.js"></scirpt>

<link href="//cdn.quilljs.com/1.0.0/quill.snow.css" rel="stylesheet">
<link href="//cdn.quillljs.com/1.0.0/quill.bubble.css" rel="stylesheet">
<link href="//cdn.quilljs.com/1.0.0/quill.core.css" rel="stylesheet">
<script src="//cdn.qulljs.com/1.0.0/quill.core.js"></script>


```

```js
deleteText(index: Number, length: Number, source: String = 'api'): Delta
quill.deleteText(6, 4);

getContents(index: Number = 0, length: Number = remaining): Delta
var delta = quill.getContents();

getLength(): Number
var length = quill.getLength();
```

```
```


