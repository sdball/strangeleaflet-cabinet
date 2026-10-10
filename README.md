# strangeleaflet-cabient

A cabinet of curiousities I can serve up from curious.strangeleaflet.com.


## Analytics

Every page in `public/` includes the GoatCounter snippet just before `</head>`. A pre-commit hook refuses commits that add or change a page without it, and the deploy workflow checks again before publishing.

After cloning, turn on the hook once:

```sh
git config core.hooksPath .githooks
```
