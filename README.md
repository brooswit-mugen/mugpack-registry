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
