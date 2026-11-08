# Rustle design template packs

Upload this `templates` folder to the `rustle-order` GitHub repo, next to `index.html`.
The packs are then at https://jared1402.github.io/rustle-order/templates/index.json, and the Design Centre lists them under "Get more templates".

- `index.json` lists the packs. When you change a pack, raise its `version` in both files, and Rustle offers "Update".
- One pack per file. A template is settings only, never pictures: `kind`, `style`, `palette` (0–26) or `colors`, `font`, `texture`, `frame`, the words, and sample `items`.
- Older apps skip any template that uses something they can't draw. A pack with `"format"` above what the app knows is hidden.
