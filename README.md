# Repolex Knowledge Graph of pypa/installer

RDF knowledge graph data for [pypa/installer](https://github.com/pypa/installer), parsed by [repolex](https://repolex.ai).

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
rlex download pypa/installer
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ba622422bc1c458d8cb82f08085a807cf2146d7a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ba622422bc1c458d8cb82f08085a807cf2146d7a
│           └── chunk-001.nq.gz
├── blob
│   ├── 01f044add93841fdc97ab865e549608e7625beef.nq.gz
│   ├── 0361a581a64af666a701aa6044f47471c4e5d00e.nq.gz
│   ├── 05c3a02da3a30c62272cdf6c6f5c051e4e6dda97.nq.gz
│   ├── 0e5973ac7f1bb5b2301bbe167571e8cef19a8979.nq.gz
│   ├── 121b9d3ef673f6c38d420201432c5d8a4f1bf28f.nq.gz
│   ├── 1799cf69c43befd48715eb0904cf9837987d040c.nq.gz
│   ├── 1b13c81ad5d71ade40fd2a405e50f786a0769875.nq.gz
│   ├── 22bbe11144d6bc89e277505ace59247a300d96e6.nq.gz
│   ├── 22c262db7b786d73915781c414a613da0265604b.nq.gz
│   ├── 2fed5cef13d52363df5b2cc5e4a058a50d3daa4a.nq.gz
│   ├── 3aad93c0fec8d4de52424f7d462787882583f7be.nq.gz
│   ├── 470d13e907cfb684f27476807ffb62fe626adb8c.nq.gz
│   ├── 4ee2d3a31b59e8b50f433ecdf0be9e496e8cc3b8.nq.gz
│   ├── 52154f0be32cc2bdbf98af131d477900667d0abd.nq.gz
│   ├── 53a4c106c03a6b5245852817ef2e57f776108e8e.nq.gz
│   ├── 5702cd9f113226fa4babae6006ac05ae4d5cad2b.nq.gz
│   ├── 5763076d2878093971a0ef9870e1cde7f556b18b.nq.gz
│   ├── 5d09f3056db92b0230e48727d5f0597cb0d7ba6d.nq.gz
│   ├── 5dc298d05bd5168c1bd76018c07e2f846ea7a5a9.nq.gz
│   ├── 697fb3147e686201bb549e8940727f5ac1ce912b.nq.gz
│   ├── 6b5b74164b6a70741c814fa0604d20a43842523b.nq.gz
│   ├── 6c93bb378acf9cc55bd7a4e4c84327051dec3116.nq.gz
│   ├── 780392d7d69077b3070d4eb37c704107ecea967b.nq.gz
│   ├── 78b1a59c8a9e8470ca41b403178144e0035da3a2.nq.gz
│   ├── 7ee8306d3f9aa0d22edcce1e8f5cd246ff994c80.nq.gz
│   ├── 836c1f20e7c79230d9433297e21e20241f41d723.nq.gz
│   ├── 8a74ad3c935c410e8b97b75cf9de1d2d943378a1.nq.gz
│   ├── 8b49513c7b12764e9a587a3d3f33378ecf32d63a.nq.gz
│   ├── 8c6345e152a1dc7e62e3b571324f035cb16d2b47.nq.gz
│   ├── 8cc312679cbf65a0d74a868c31ce12628d6365ee.nq.gz
│   ├── 951d5817c9e6d81c94a173a0d9fead7f1f143331.nq.gz
│   ├── 95699b5b4999ec79a5a5da417fd5bbc9f96899f5.nq.gz
│   ├── 97f3b097c564b586f1fa4604f0e7c85e4c1d79cc.nq.gz
│   ├── 9bb45c756fb9e6203c5b56deb3a0d8f2f6614e3d.nq.gz
│   ├── a19b33886cde9a9a6d03a5ca14829a1126fb518e.nq.gz
│   ├── a3dd063821c25db4afb274dc10f82ae3b296c98d.nq.gz
│   ├── a68160812f006585cb70cfe2a12bfb773bc32976.nq.gz
│   ├── a9320dc228ffa9a0747b11342a4b5506de6059f2.nq.gz
│   ├── b0201fdfd9455b44a9481dfbca2cc3969f3265e0.nq.gz
│   ├── b21a72ea996e8cf31c7271d6a01483f07aaeb79b.nq.gz
│   ├── b7a7445d4e5033c53ce01643e7f0a94bb8e80b77.nq.gz
│   ├── c20ceecabe41c326df2c95db5e67c578292d203f.nq.gz
│   ├── c3edf85944e1d6c15d54af009a41b0cd8281b809.nq.gz
│   ├── c51a3d8b7ddb87678559083a8a8f41067e1e1ae8.nq.gz
│   ├── c632e0eb2f55255a5ee2052e4b208619b920381c.nq.gz
│   ├── c862546f2ab5af07aafcb7cd578d5dbea212a2ac.nq.gz
│   ├── c8a93046d6bcc8bd74202b2cdce19e0f1263a14f.nq.gz
│   ├── cb09b3d1902f3ea9dd3ec68892abb4eab0d35e36.nq.gz
│   ├── d7cc6704883a8fb50efeaa91c8d5db5b349f77a6.nq.gz
│   ├── db10fc9b046b9242e707febaca871b22709fd5db.nq.gz
│   ├── dd167d6488a74b8ea6f58625ae9ce2a9cbc18502.nq.gz
│   ├── dfb53174620f0f0d669743d2f53f6fc47acb9873.nq.gz
│   ├── e1ab8f8f589eadabaf3efa068dce3ff620a01898.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8bebdba6d8f242244bf397ab067965d47c5093e.nq.gz
│   └── ea86f7215edc1b07dd5be3081074d784685467e0.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── ba622422bc1c458d8cb82f08085a807cf2146d7a.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 64 files
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

[pypa/installer](https://github.com/pypa/installer)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
