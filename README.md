# Proa Gulp

Gulp settings for projects of Proa Data.

## Tasks

- `gulp` or `gulp serve` are for running a test (development) server with live reload.
- With `gulp serve:dist`, the server is production, but without the reload.
- `gulp build` builds the distributable version.

## Folder structure

Here is the essential basic organization you must to put in your project:

```text
├─ bower_components/
├─ nodes_modules/
├─ src/
│  ├─ fonts/
│  ├─ styles/
│  │  └─ index.less
│  └─ index.html
├─ .gitignore
├─ bower.json
├─ gulpfile.js
├─ package-lock.json
└─ package.json
```

The disposition of the other files present in `src` is merely indicative; and its content, adjustable and optional.

## Pending

- Once the server waits for changes, synchronize also the deletion of files (from `src`).
- Bower should be replaced as a dependency manager. It is currently [under maintenance](https://bower.io/blog/2017/how-to-migrate-away-from-bower/) and, therefore, its use is not recommended.