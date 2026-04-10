# Repolex Knowledge Graph of isaacs/node-mkdirp

RDF knowledge graph data for [isaacs/node-mkdirp](https://github.com/isaacs/node-mkdirp), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download isaacs/node-mkdirp
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6fc29774a008f41d96b34523d6aae543ecb46cd1
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 6fc29774a008f41d96b34523d6aae543ecb46cd1.nq.gz
│   └── repolex
│       └── 6fc29774a008f41d96b34523d6aae543ecb46cd1
│           └── chunk-001.nq.gz
├── blob
│   ├── 0a034db7a73b5d2715f2b015f4feffd25301fcee.nq.gz
│   ├── 115a05f2dbfe8473e16ce603ebc2fed72ce6f6cd.nq.gz
│   ├── 1369002180ff109dbde0758f0e4f9b25bb2a96f0.nq.gz
│   ├── 22ed49ee9fe07ca994a41617464bb8022d6f3016.nq.gz
│   ├── 3d010feed80f515001c2d1ded85eab292791d922.nq.gz
│   ├── 40cccea90f8053e3c23b4c0bd5925daf9f8ac54f.nq.gz
│   ├── 45a01fa384d953919a5630e5735409fdcbf2baf6.nq.gz
│   ├── 48f7364bbed8d82fdcbf9f822818fad2c5978ff1.nq.gz
│   ├── 5083750a8966ff4dd880186bf7774d1b4e6fddf9.nq.gz
│   ├── 53210c4856913958d1faa77079c0c23f6b596c14.nq.gz
│   ├── 5bf92058a27b41f44c9d67ea8dc479c21e7a19b6.nq.gz
│   ├── 623ae28e8f1b7296a06bcd45064480cee1cb08fc.nq.gz
│   ├── 63da5f020b2abfa03dcd614bc1659a29386e3e4b.nq.gz
│   ├── 66bfef9fd67de5f76bb6978c284984869f45a22b.nq.gz
│   ├── 6791fbd441d8757db8846bf89160840ff499ead7.nq.gz
│   ├── 6bcf91085c9b5db943e0558e09078b1f171f65ff.nq.gz
│   ├── 6ca5345f19dd62c7c0610e458197d19a89aa222f.nq.gz
│   ├── 74ce986921d2cfc9ee77b3d3d7ccbaa7e61ea9b1.nq.gz
│   ├── 7982a2883ac4e813f942b90ba8b38083b0f6bf6c.nq.gz
│   ├── 8d030f71fb37498f5d4a794ab17f6458aa494762.nq.gz
│   ├── 8eb5e85565e9f4effc79ce93dafba8bdc2854f46.nq.gz
│   ├── 92fdbe5f7717ea5bf1f651527e275addd6816504.nq.gz
│   ├── 95f2cab0a6f052a60fb6cb4d873b0e56317de279.nq.gz
│   ├── 9fdb805acdbbe618242b64d496518050ec5ab9f0.nq.gz
│   ├── b28151b69e4440c159f645e6e90cb78bd284dca3.nq.gz
│   ├── b8ad884dc1cc9c07624017f8937e377cec781e28.nq.gz
│   ├── bc58d80112713a994b4e0bf83bdb57190cc60abc.nq.gz
│   ├── bebee46b9210589c56359f405e582a493732d77e.nq.gz
│   ├── cf594639a455b1b15a9dbd440ff763dd04f770bb.nq.gz
│   ├── da945b60b1e2ff2749551ca010121103c983a786.nq.gz
│   ├── da99b47568e3f6cc6469662acf8059aed192f0e6.nq.gz
│   ├── dba4325cb9a24dd89338ea7754bb765ccfbdcf93.nq.gz
│   ├── dc06ed4daf8b188476f15734736ab4a14bc3ddfd.nq.gz
│   ├── dd1427bc1cd2c30d6f24d1a0b9c629034fe8d78d.nq.gz
│   ├── df654b808755f55773aa511369a6ba3eb0dcda5a.nq.gz
│   ├── e5bc0ef831d7e76ca6144522fba8fb8e5325ed53.nq.gz
│   ├── e951d3fb33cc413f0660b59fa8e1c4ff1a1b3dfb.nq.gz
│   ├── efe88aaa1973e2078d3ca57b48db06d01969a79b.nq.gz
│   └── f31ac3314d6f6a4ec37ef31b5394c41953680e4f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 6fc29774a008f41d96b34523d6aae543ecb46cd1.nq.gz
├── filetree
│   └── 6fc29774a008f41d96b34523d6aae543ecb46cd1.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 49 files
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

## Source repository

[isaacs/node-mkdirp](https://github.com/isaacs/node-mkdirp)

---
*Parsed on 2026-04-10 by [repolex](https://repolex.ai)*
