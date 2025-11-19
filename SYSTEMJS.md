In your ```system.config.js```

Append to ```map```

```js
var map = {
    'dz-pdf-viewer': 'node_modules/dz-pdf-viewer/bundles',
    'pdfjs-dist': 'node_modules/pdfjs-dist'
}
```

and then add to ```packages```

```js
var packages = {
    'dz-pdf-viewer': { defaultExtension: 'js', format: 'cjs' },
    'pdfjs-dist': { defaultExtension: 'js' }
}
```
