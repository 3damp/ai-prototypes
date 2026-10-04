# AI Prototypes

Small experiments built with AI. Each prototype is a self-contained folder served by GitHub Pages.

**Live site:** https://3damp.github.io/ai-prototypes/

| Prototype | Description | Play |
| --- | --- | --- |
| [Moth Night](moth-breeding-game/) | Breed moths for wing traits and fill collectors' orders | [Play](https://3damp.github.io/ai-prototypes/moth-breeding-game/) |

## Adding a prototype

1. Create a kebab-case folder, e.g. `my-new-prototype/`.
2. Name the entry file `index.html` so the URL is `.../my-new-prototype/`.
3. Add a short `README.md` in the folder.
4. Add a link to the root `index.html` and to the table above.

## Setup after cloning

Turn on the pre-commit check that blocks API keys, tokens, private keys, local file paths and your git email address:

```sh
git config core.hooksPath .githooks
```

If it flags a false positive, commit with `git commit --no-verify`.
