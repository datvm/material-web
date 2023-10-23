This is a build of Google's Material Design 3 [Material Web](https://github.com/material-components/material-web). It uses GitHub Actions to build the project and then bundle it with `esbuild`. The result is commited back to `dist` folder.

You can host it offline or serve through a CDN:

- Latest build: https://cdn.jsdelivr.net/gh/datvm/material-web/dist/bundle.esm.min.js (you should not use integrity check with this link because it will change every time a new build is published).

- With a tag: https://cdn.jsdelivr.net/gh/datvm/material-web@v1.0.1/dist/bundle.esm.min.js

```html
<script src="https://cdn.jsdelivr.net/gh/datvm/material-web@v1.0.1/dist/bundle.esm.min.js" integrity="sha512-jFjF3vQYBwwXh8pgesz1xdfZA8J6yak2R6S/nuOZxJP3lgpxKvN6o8iHM4PTFMJqnVmgestaRChwpL7nwYTomw==" crossorigin="anonymous"></script>
```

- Sometimes (probably only during pre-release), a build is made on a specific day. I will mark them with tags like: https://cdn.jsdelivr.net/gh/datvm/material-web@2023.09.26/dist/bundle.esm.min.js

This bundled is used by my Blazor wrapper [Blazor Material Web](https://github.com/datvm/BlazorMaterialWeb/).