# Repolex Knowledge Graph of miguelgrinberg/Flask-Migrate

RDF knowledge graph data for [miguelgrinberg/Flask-Migrate](https://github.com/miguelgrinberg/Flask-Migrate), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download miguelgrinberg/Flask-Migrate
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── bce4d35a0c61d2516c76744a1f168bc6af26d55e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── bce4d35a0c61d2516c76744a1f168bc6af26d55e
│           └── chunk-001.nq.gz
├── blob
│   ├── 02cce84ee2b7916aaa9f5afa8e3f7d177747b057.nq.gz
│   ├── 06933c1da21eddaed365265655d1520eecbacae3.nq.gz
│   ├── 07c392100ab95825a9fc02e4dbf28697d2c60137.nq.gz
│   ├── 07cf159b2eb0974a21432f04be1ce5a39c839408.nq.gz
│   ├── 0e048441597444a7e2850d6d7c4ce15550f79bda.nq.gz
│   ├── 136f4a38bba5762182cf197de02018ee5ac32cda.nq.gz
│   ├── 197f17bdab6bc0c820052d34d7943d9c0eb8af2d.nq.gz
│   ├── 1cabd31f78997b70e9ab67694508cb31bfbf31b7.nq.gz
│   ├── 2448fd2665df720101cf6662b17bfdfbda3e7cc3.nq.gz
│   ├── 250f570e6e94706459402810dd05090ea476a264.nq.gz
│   ├── 27f573b87af11e2cbbd9f54eb1ee285a58550146.nq.gz
│   ├── 298ea9e213e8c4c11f0431077510d4e325733c65.nq.gz
│   ├── 2c0156303a8df3ffdc9de87765bf801bf6bea4a5.nq.gz
│   ├── 2efc467034a0fbfc214182f2b9993ee708ef81df.nq.gz
│   ├── 31b8e7248bac6fe0933b4104092182d6a8d731a9.nq.gz
│   ├── 3307cbd19aa481e73d53114ecb00eb83f513ec10.nq.gz
│   ├── 3a1ece5acba194e155a145846baa6bfec0231327.nq.gz
│   ├── 3beabc46397a862b61217f3ae5fcb6397a6ca72f.nq.gz
│   ├── 44ee59a8edcabde444b7514d63557514fca1cfee.nq.gz
│   ├── 4a025e5e9dba893a1962371b31eb4830466d96d6.nq.gz
│   ├── 4c9709271b2ff28271b13c29bba5c50b80fea0ac.nq.gz
│   ├── 4ccfad466c853df000a2d31f49cc8d1a504d9308.nq.gz
│   ├── 4fabece25c8c3c51773b13a83b580a0cf1e9b58e.nq.gz
│   ├── 58939747f855b8390be9b1e63a29b41aa9ff79f7.nq.gz
│   ├── 6239577c663af635a72b7d38b1787635f5795a30.nq.gz
│   ├── 69080a2650cde7b9dee0b12f1550d85495ddd7e6.nq.gz
│   ├── 6ed8020e0b66ef283f87e4e64b16222191d2bbea.nq.gz
│   ├── 828c8cd3cbfd70000af584ae6a2ded4000289e1a.nq.gz
│   ├── 87d2a739d4bc56a16b31d2a388927d730cbdb79c.nq.gz
│   ├── 8b9d1cea8b4a831c719f030541c33158a0c158ec.nq.gz
│   ├── 93482794391896a8715f85cebfd8c8cb5c48684b.nq.gz
│   ├── a1cacb3d505a9310466831b04f0738f993bb38eb.nq.gz
│   ├── a46282abfbf8258186de12d3147d1d199cf5e9bf.nq.gz
│   ├── a4b1b790cb1fb126d07cff36eb491ead9530509a.nq.gz
│   ├── b9305e341a06609e799c39e1572005044ae4f1ff.nq.gz
│   ├── cad70c6ab019229d394b0824143aacacdaefe37c.nq.gz
│   ├── d193300028da657c802545acf32ebbaa5e70e22e.nq.gz
│   ├── d96da57a106e3dc647a681fb5530506d1c89389e.nq.gz
│   ├── e2503c4442ba3221f4d48111cb4667af36680c19.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eaae2511a060b2ed968be4c363abb453cbf0215c.nq.gz
│   ├── ec9d45c26a6bb54e833fd4e6ce2de29343894f4b.nq.gz
│   └── f14bd6c091bc954c6a5ddcf7f081057f6ffbb432.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── bce4d35a0c61d2516c76744a1f168bc6af26d55e.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 51 files
```

| Directory | What it contains |
|-----------|-----------------|
| `blob/` | Per-file AST graphs, content-addressed by git blob SHA. Each file in the source repo gets its own graph. |
| `aggregate/ast/` | Combined AST graph per parsed commit. Merges all blob graphs for a snapshot of the entire codebase at that point. |
| `aggregate/lsp/` | Language Server Protocol enrichment: resolved symbols, definitions, references, and type information. |
| `aggregate/dataflow/` | Interprocedural data flow edges between functions and modules. |
| `aggregate/repolex/` | Combined graph (AST + LSP + dataflow) per commit. |
| `commit/` | Git commit metadata (author, date, message, parent links). |
| `branch/` | Branch metadata. |
| `tag/` | Tag metadata. |
| `filetree/` | File tree snapshots per commit (which files existed and their blob SHAs). |
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[miguelgrinberg/Flask-Migrate](https://github.com/miguelgrinberg/Flask-Migrate)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
