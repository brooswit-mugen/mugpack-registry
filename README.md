# MugPack Registry

Each character pack has one manifest at `char/<author>/<character>.json`.
For example, `char/gm/ryu-sf3.json` supplies the install ID, archive source,
and author credit for this MugPacks reference:

```yaml
items:
  - pack: gm/ryu-sf3
```

Use lowercase names for both path segments. To add or update a build, edit
its manifest directly.

Stage packs live at `stage/<author>/<stage>.json` and use references like
`stage/neogouki/suzaku`. Both pack types link to the original archive.

Author metadata lives at `author/<author>.json`. Its `links` array contains
typed homepage, profile, social, or release links where available.
