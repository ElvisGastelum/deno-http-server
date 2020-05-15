# Hello world version deno http server
I'm using deno for create a basic http server, and i use a importmap to import without directly link to dependencies in ts files,
instead use alias, in this case a rename "https://deno.land/std/http/mod.ts" to "http".

## Run this module
```
deno run --allow-net --importmap=importmap.json --unstable mod.ts
```
