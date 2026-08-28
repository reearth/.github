<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/reearth-dark.webp">
  <img src="./assets/reearth.webp" alt="Re:Earth" width="320">
</picture>

### Open source software for the geospatial world

Build maps, manage data, automate pipelines — all in the open.

[Website](https://reearth.io) · [Docs](https://docs.reearth.io/en/) · [Discord](https://discord.com/invite/XJhYkQQDAu) · [X](https://x.com/ReEarth_Eukarya) · [YouTube](https://www.youtube.com/@reearth5830)

</div>

---

## Products

<table>
<tr>
<td width="50%" valign="top">
<img src="./assets/visualizer.webp" width="56" alt="">

### [Re:Earth Visualizer](https://github.com/reearth/reearth-visualizer)

A free, open and highly extensible WebGIS platform. Bring your GIS data onto a 3D globe, style it, tell a story with it, and publish it — no code required.

`React` `TypeScript` `Go` `GraphQL`

</td>
<td width="50%" valign="top">
<img src="./assets/cms.webp" width="56" alt="">

### [Re:Earth CMS](https://github.com/reearth/reearth-cms)

Creating and publishing databases. Model your geospatial content, keep it reviewed and versioned, and serve it straight to your apps through an API.

`React` `TypeScript` `Go` `GraphQL`

</td>
</tr>
<tr>
<td width="50%" valign="top">
<img src="./assets/flow.webp" width="56" alt="">

### [Re:Earth Flow](https://github.com/reearth/reearth-flow)

An ETL web tool to build and run automated workflows. Wire up nodes on a canvas to convert, validate and transform large geospatial datasets.

`Rust` `React` `TypeScript` `Go`

</td>
<td width="50%" valign="top">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/navara-dark.webp">
  <img src="./assets/navara.webp" width="56" alt="">
</picture>

### [Navara](https://github.com/reearth/navara)

A highly extensible 3D map engine. A headless GIS core in Rust/WebAssembly with a tiered API — declarative config at the top, your own shaders at the bottom.

`Rust` `WebAssembly` `Three.js` `TypeScript`

</td>
</tr>
</table>

## Services

Open data services that anything on the map can build on.

| Service | Description | Source |
| --- | --- | --- |
| [**Re:Earth Terrain**](https://terrain.reearth.land/) | Open terrain tiles for 3D globes | [reearth-terrain](https://github.com/reearth/reearth-terrain) |
| [**Re:Earth Buildings**](https://buildings.reearth.land/) | Overture Maps → 3D Tiles 1.1, served from Cloudflare Workers | [reearth-buildings](https://github.com/reearth/reearth-buildings) |
| [**Re:Earth Papers**](https://papers.reearth.land/) | A tile service for beautiful, openly-licensed maps of the world | [reearth-papers](https://github.com/reearth/reearth-papers) |

## Libraries

The pieces we built along the way — each usable entirely on its own.

**Rendering & maps**

| | |
| --- | --- |
| [**resium**](https://github.com/reearth/resium) | React components for 🌏 Cesium |
| [**ezu**](https://github.com/reearth/ezu) | Painterly cartography — render vector tiles as watercolor, ink wash or pencil sketch on a GPU-free CPU renderer |
| [**hokusai**](https://github.com/reearth/hokusai) | Pure-Rust brush engine inspired by libmypaint, WASM-ready with `.myb` compatibility |

**Geospatial data**

| | |
| --- | --- |
| [**terrain-codec**](https://github.com/reearth/terrain-codec) | RTIN mesh, Cesium quantized-mesh codec and ECEF transforms for Rust |
| [**draco-oxide**](https://github.com/reearth/draco-oxide) | Rust crate for the Google Draco mesh compression library |
| [**kenro**](https://github.com/reearth/kenro) | SpatiaLite-style spatial SQL for SQLite in pure Rust — PostGIS-compatible `ST_` functions, GeoPackage R-tree, CRS transform, H3, MVT |
| [**flatgeobuf-overviews**](https://github.com/reearth/flatgeobuf-overviews) | Scale-optimized, fgb-compatible vector format for fast on-demand MVT tiles from one static file |
| [**maplibre-expr-rs**](https://github.com/reearth/maplibre-expr-rs) | Pure-Rust parser and evaluator for MapLibre GL style expressions |

**Platform**

| | |
| --- | --- |
| [**ygo**](https://github.com/reearth/ygo) | A pure-Go, production-grade implementation of Yjs — a Hocuspocus-compatible websocket server with versioned persistence |
| [**quickjs-emscripten-sync**](https://github.com/reearth/quickjs-emscripten-sync) | Sync objects between the browser and QuickJS |
| [**zushi**](https://github.com/reearth/zushi) | A framework-agnostic browser plugin runtime — untrusted code in an isolated WASM backend, UI in sandboxed iframes |
| [**mongogit**](https://github.com/reearth/mongogit) | Git-style versioned documents for MongoDB, in Go |
| [**fastxml**](https://github.com/reearth/fastxml) | A fast, memory-efficient XML library for Rust with XPath and schema validation |

## Community

Ask questions, share what you built, or just say hi.

- 💬 [**Discord**](https://discord.com/invite/XJhYkQQDAu) — chat with users and maintainers
- 📖 [**Documentation**](https://docs.reearth.io/en/) · [**Developer docs**](https://visualizer.developer.reearth.io/) — guides, APIs and plugin development
- 📣 [**X**](https://x.com/ReEarth_Eukarya) · [**YouTube**](https://www.youtube.com/@reearth5830) — releases, demos and talks
- 📈 [**Status**](https://github.com/reearth/status) — uptime for our hosted services

## Contributing

Every repository is open to issues and pull requests — start with the `CONTRIBUTING.md` in the one you care about.

We are also hiring full-time OSS committers: [eukarya.io/join](https://eukarya.io/join)

<div align="center">
<sub>Built by <a href="https://eukarya.io">Eukarya, Inc.</a></sub>
</div>
