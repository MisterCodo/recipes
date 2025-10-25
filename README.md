# Recipes

Serve a static website of family recipes: [https://mistercodo.github.io/recipes/](https://mistercodo.github.io/recipes/)

## Run Locally

On Windows, using PowerShell:

```bash
docker run -it -v ${PWD}:/src -v ${HOME}/hugo_cache:/tmp/hugo_cache -p 1313:1313 hugomods/hugo:dart-sass hugo server
```
