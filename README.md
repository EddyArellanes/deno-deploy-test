# Deno Deploy
Is the official deno.com feature to deploy deno projects, it has `Free` started so let's try a little bit how it works.

## Test
```bash
deno run index.ts
```
Or test; 
```bash
deno run https://deno.land/std@0.144.0/examples/welcome.ts
```

## Knowledge Facts

> At a high level, Deno converts TypeScript (as well as TSX and JSX) into JavaScript. It does this via a combination of the TypeScript compiler, which we build into Deno, and a Rust library called swc. When the code has been type checked and transformed, it is stored in a cache, ready for the next run without the need to convert it from its source to JavaScript again.

> routing request to different Control is not supported out-of-box. 