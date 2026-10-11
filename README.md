# Repolex Knowledge Graph of litestar-org/litestar-templates

RDF knowledge graph data for [litestar-org/litestar-templates](https://github.com/litestar-org/litestar-templates), parsed by [repolex](https://repolex.ai).

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
rlex download litestar-org/litestar-templates
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d5c671f8c207ec9b70c8a30cebf184c703c85213
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d5c671f8c207ec9b70c8a30cebf184c703c85213
│           └── chunk-001.nq.gz
├── blob
│   ├── 06b94c54739a73fed72874b86ee9e86ea5072ef0.nq.gz
│   ├── 07a65d9b49b36f298e7dfcc6c7d436e24842aa6f.nq.gz
│   ├── 0a6c11ce932b0e713d3a12033846dbc57fced03a.nq.gz
│   ├── 0ccf74a817c4b477cb05374500b5bd86b538c321.nq.gz
│   ├── 0cf5464be90273210468d660325c6ec56683f8f0.nq.gz
│   ├── 18146b4e045a9e1bfda370a2ba67dd061a24fb08.nq.gz
│   ├── 199a978e960437a74f1aeede0ae0c74851e0a066.nq.gz
│   ├── 1baf14100fca1d68cc3436bcbb6ba90f07fb82fe.nq.gz
│   ├── 1ec39ed1a6c5d677c8964a5feb1a4f7360d547f1.nq.gz
│   ├── 24068f3dcb0076707eb6723f6fd23014548cea92.nq.gz
│   ├── 2e3cfb559cfaa9ad40af07f48adefd44b68f08d3.nq.gz
│   ├── 33aae54b14b1d5301be9ab03351f124cd9d135ac.nq.gz
│   ├── 33f33f657b5325e05fc8bc969680db6026da1194.nq.gz
│   ├── 3dcce1e80f5429a0b0cc98e2f8c2e6c1e95c7712.nq.gz
│   ├── 4176cdea879f465d2deb717c4241ad1e1f5ad4ee.nq.gz
│   ├── 4e1bc2efed888e3f2b1a8325e9e9e4f38eef0272.nq.gz
│   ├── 533675cbf7245a33fd7c173e5a1395727ff3326c.nq.gz
│   ├── 57186ca2e9959786187819954f36e24c609caa31.nq.gz
│   ├── 5786829440180f4ca2d1545d89420bcd911d5fed.nq.gz
│   ├── 58ef3a1e23ecde662f95f8ef99046a8c25fc8f73.nq.gz
│   ├── 5aa5166d67fcb2fe2483a189bdf3fc644da65b7f.nq.gz
│   ├── 5c53fe0acfe59ac255eb218ec6f6466698700d8f.nq.gz
│   ├── 5ea33efc299dd92990437f0eff0f60e82a489bcb.nq.gz
│   ├── 5f1d141e6b325cafff7ba130d90fec065d37645b.nq.gz
│   ├── 5f9c4cd06c42603db227b13f64635619648a4b1b.nq.gz
│   ├── 63e894a9ef2eb6257a47dbe93c11c5133d3d71ec.nq.gz
│   ├── 6809e7044cb236d2354da5f1a161677805eb1e74.nq.gz
│   ├── 6ac3565ad9757b7a34c0ad7eb3223b2374c0f48f.nq.gz
│   ├── 6f5ed3c6c9a00353ebb9d94c082e6ed74c1f3ca3.nq.gz
│   ├── 717a6ec695dd6c05ecc55c4c22d169c2e89d59d8.nq.gz
│   ├── 72efa46f9bccece5e09aeeb2fde75771f5d7873a.nq.gz
│   ├── 760383394b317b75b604f13cac5ef45ac80b889b.nq.gz
│   ├── 7979dfacf6ec2e24066f9f0b0c85e1dbf3f8b39d.nq.gz
│   ├── 83124180f309b74412eed31cd645137ee72a60a7.nq.gz
│   ├── 86d9312a92031089b976dd1f1bfb6ee399f2a529.nq.gz
│   ├── 90406904639e4daad66497bac619e97de3da29a2.nq.gz
│   ├── 905905142f9151eb5338f5a3e887b5f8f6a10a35.nq.gz
│   ├── 983f04a0683967bfbf504be7c175c81663d85430.nq.gz
│   ├── 98e0a5113756fcfd187d0ce09d4d20c61ef67c22.nq.gz
│   ├── 9a3c7cd7564d98c1acaefd4a990ee2601ee40942.nq.gz
│   ├── 9c99c4d8e772c86c843c7298b459d5e33d5ea206.nq.gz
│   ├── 9d29b0e250113a8ff674b2d54530f58ed2708dd0.nq.gz
│   ├── a266e7c86295a9295ce1588e8facf021d0d211d8.nq.gz
│   ├── a47aa75b1c4e7cea8ca9b9a7e2f50e28967c1b2b.nq.gz
│   ├── a5082ba278aa9cc423ba9d675a6b1afad0d1535f.nq.gz
│   ├── abda4bf3d50a2ece8e388aa33fdab9b5e9ba477f.nq.gz
│   ├── b2b2912193918f9cc88fba56d64277812a754642.nq.gz
│   ├── b533f16913ff999144a299a57265916fc3bd9b69.nq.gz
│   ├── b6490abdefa7def14dedcb06498ac4439012d99c.nq.gz
│   ├── b92a6dea27eb353a937959c310244eb4f3b0caff.nq.gz
│   ├── c0574860d693eacce0f9d93de2a98147551e903a.nq.gz
│   ├── c2ee7beba00427c83b88ffd1ca9305b6ec66998d.nq.gz
│   ├── c6c5918f3a01ca137fd50d43454479c93711d497.nq.gz
│   ├── c7008876d237f05bd9282294c64a2c896c840b12.nq.gz
│   ├── c7faf807ba587f6151b12175c8810f66daae9fee.nq.gz
│   ├── cff683485c7533882b5a34ea06ca7b51b33184e5.nq.gz
│   ├── d517f48d707dce5a32af202fd72b6ddba5b36371.nq.gz
│   ├── d77ba055bd6dfa8f78faec96ea29ecc9d19651fd.nq.gz
│   ├── e26b7c9e524106c96de7af5a987c506c70fd3637.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8e3abc21f877845063cc054f61442869e55bd04.nq.gz
│   ├── eb30c33da3a5070dc516cf4e14299b9b59f374cc.nq.gz
│   ├── ec1a586e5d255d6911a89d4954677b288e5b618f.nq.gz
│   └── f34926a42ea260886827026cd7a28b3b02ef19a4.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── d5c671f8c207ec9b70c8a30cebf184c703c85213.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 71 files
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

[litestar-org/litestar-templates](https://github.com/litestar-org/litestar-templates)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
