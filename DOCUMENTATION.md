# Documentation

## Guide For CSS / SCSS

As we using Parcel-Bundler it will take care (compilation) of your scss files.

You can link your scss file directly to "index.html"

```bash
<head>
    <!-- main scss -->
    <link rel="stylesheet" href="./style/scss/main.scss">
</head>
```

**OR**

You can import your scss file into "index.js"

```bash
import "./style/scss/main.scss"
```

Note : Don't Forget to remove link "<link rel="stylesheet" href="./style/scss/main.scss">" from "index.html".
