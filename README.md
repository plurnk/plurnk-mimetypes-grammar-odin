# @plurnk/plurnk-mimetypes-grammar-odin

Pre-built `tree-sitter-odin` WASM grammar for the [@plurnk/plurnk-mimetypes](https://github.com/plurnk/plurnk-mimetypes) framework.

## install

```
npm i @plurnk/plurnk-mimetypes-grammar-odin
```

## what's in here

- **`odin.wasm`** — pre-built from the pinned upstream [tree-sitter-odin](https://github.com/tree-sitter-grammars/tree-sitter-odin) commit (SHA in `.grammar-pin`)
- `scripts/build-wasm.mjs` — reproducible rebuild from the pinned source
- `scripts/verify-wasm.mjs` — CI byte-identical reproducibility check

Declares only `web-tree-sitter` as a peer — no native `tree-sitter`, no node-gyp.

## license

MIT. The bundled `odin.wasm` is built from the upstream tree-sitter-odin grammar; see the pinned commit for that project's attribution.
