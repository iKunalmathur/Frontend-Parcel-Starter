# Documentation

## Installation

Clone Repo or Download Zip.

### HTTPS

```bash
https://github.com/iKunalmathur/Frontend-Parcel-Starter.git
```

### SSH

```bash
git@github.com:iKunalmathur/Frontend-Parcel-Starter.git
```

### GitHub CLI

```bash
gh repo clone iKunalmathur/Frontend-Parcel-Starter
```

### Download Zip

[Download 🌠](https://codeload.github.com/iKunalmathur/Frontend-Parcel-Starter/zip/refs/heads/main)

## Usage

Run "npm install" Download Dependencies

```bash
npm install
```

Run "npm run dev" start local development server on localhost:1234

```bash
npm run dev
```

## Wanna change port ?

Add -p 3000 (port flag with port number) after entry html file ("index.html").

```bash
"scripts": {
    "dev": "parcel ./src/index.html -p 3000",
    "build": "parcel build ./src/index.html"
  },
```

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
