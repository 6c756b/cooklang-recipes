# Recipe Collection

My personal recipe collection in [Cooklang](https://cooklang.org/) format. Recipes are written in German.

## What is Cooklang?

Cooklang is a simple plaintext format for recipes. Each `.cook` file is human-readable – ingredients are marked with `@`, cookware with `#`, and timers with `~`. All recipes use YAML frontmatter for metadata (title, servings, time, source, tags).

## Viewer

The recipes are hosted via [GitHub Pages](https://6c756b.github.io/cooklang-recipes/) using a bundled build of [cooklang-webapp](https://github.com/6c756b/cooklang-webapp).

## Update Process

After adding, removing, moving, or editing recipes, rebuild the index:

```bash
node generate-index.mjs
```

Then commit and push - GitHub Pages will update automatically.
