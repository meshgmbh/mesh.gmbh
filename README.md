# mesh.gmbh

The company behind the mesh ecosystem.

This repo holds the public website for **mesh.gmbh** — served via [mesh.web](https://github.com/meshgmbh/mesh.web)
on the distributed mesh.eco infrastructure.

Edits to `index.html` (and any future content) automatically deploy to all 8 mesh fleet nodes via:

```bash
cd ../mesh.web
bash scripts/update-site.sh mesh.gmbh
```

