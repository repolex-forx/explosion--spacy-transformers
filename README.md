# Repolex Knowledge Graph of explosion/spacy-transformers

RDF knowledge graph data for [explosion/spacy-transformers](https://github.com/explosion/spacy-transformers), parsed by [repolex](https://repolex.ai).

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
rlex download explosion/spacy-transformers
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2442e8c15152d1a7f66e90f07642baf87dba65f3
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2442e8c15152d1a7f66e90f07642baf87dba65f3
│           └── chunk-001.nq.gz
├── blob
│   ├── 03622615234288806596d60b351465f56f1ca2d4.nq.gz
│   ├── 087c4282983af92885704e798aac4c40aa32577c.nq.gz
│   ├── 0aee88f69671c14fb6a117fb72db57422b273255.nq.gz
│   ├── 12ea45744b666cbe9e73e38cd1dd9709fb892a08.nq.gz
│   ├── 1c5fe1766969c99317779697cd35430989a3f8dc.nq.gz
│   ├── 1d83f669f2e418c0f0d31f1d8a4cecbf4ad9d8b3.nq.gz
│   ├── 212cd41cd3962c62ad8d9e293f237ef96652d689.nq.gz
│   ├── 238a1d63b993394695405db7003e5f45ce207ef6.nq.gz
│   ├── 295d35b14d15c410feb7606a7a54c13a6dc60fb9.nq.gz
│   ├── 2a5ef8df8d40d0678eb57d7e8bc04190a7afcd28.nq.gz
│   ├── 2df7da05a6517974aa24aa5dffe62bacddd0cf4a.nq.gz
│   ├── 2f213cf999d50fa65af65af926e85db2e28b1882.nq.gz
│   ├── 30746cacc8b31ab8f7b453972b7adb35f7d3c6f1.nq.gz
│   ├── 3713751e0d5442ec83ba8342d8cde8c673d426a1.nq.gz
│   ├── 37f77c60f9236be556499225f09cb67c00eb4795.nq.gz
│   ├── 3af8060dba870aac31bba2badb5c2ad1f3847bbc.nq.gz
│   ├── 3d340a423c2597f6b31c8dab370e6d9b7d42ef88.nq.gz
│   ├── 3d4fded10fddcb5590f4e2a2320bcfa1726fa1ac.nq.gz
│   ├── 3f5a27711626b9a27181e29c3e9d08fb3648d9ab.nq.gz
│   ├── 40d14591a86ab597781a627890274530b43e32d0.nq.gz
│   ├── 43a802686c31fa507a436c7f9868f5ad7a19e17e.nq.gz
│   ├── 4d73207f320f3fb514ecb1303429ca9357b02419.nq.gz
│   ├── 5540d634d69b8f1781f37434dc5e4ffc461f31b0.nq.gz
│   ├── 5a2adcbd98361507a2243df3ca9c8af1d3cf7315.nq.gz
│   ├── 5ae07fc6fa55ac6ec2e372e8728341d87edddfc2.nq.gz
│   ├── 65cff21cc4491d7311af85f2e4838c4607804442.nq.gz
│   ├── 6f9bbe6eafb473e03fab93f1975eee6c7234ca9f.nq.gz
│   ├── 74a790581a4fc9cb1525636b8d393fe2fc9d4992.nq.gz
│   ├── 770d127242d6cf98a7e12be341a921a9788ff388.nq.gz
│   ├── 7736564c76471b57357c97a72869d552f4ead659.nq.gz
│   ├── 7b263ccd7f494c369b61e165e3090206e5b5616a.nq.gz
│   ├── 7bd4f5d389fee84b9e398c7dcb7364ce15898489.nq.gz
│   ├── 8649f16f5868ae60e3a5259f8bc9685aa84ea836.nq.gz
│   ├── 8b43a5e765defef2b622047f92939c1a70a570f4.nq.gz
│   ├── 8cc8659a4bb910e2c2a4a48922c7de0b395d43d1.nq.gz
│   ├── 941eb179e3a08a33da04737e4af2cea5b3323652.nq.gz
│   ├── 95e0014aa7b0a7160d78200ff654fe889b486208.nq.gz
│   ├── 984c1f393f98b2dd7df704a00d71c18b53654ba3.nq.gz
│   ├── 99cde866cb9312ea79a7582a6e5fd96300d88071.nq.gz
│   ├── 9c80db6fadbe0e286d9fb29f033165db7de42411.nq.gz
│   ├── 9cf541a3baf99ccb3f811c926adcede9a8724274.nq.gz
│   ├── a7ba878488d0d7aea14428d06c1950b352639597.nq.gz
│   ├── a8740dccddd0212b0e5d7bbaff8926af8a23eb8f.nq.gz
│   ├── b35bb92cfb0727a8dda8d5c876fcac28ad900dd8.nq.gz
│   ├── b54ca57eb1584e1b5c6b85da148143aba1794aec.nq.gz
│   ├── bb37997185b7aa816715374d97be785197d60e4d.nq.gz
│   ├── d3dc360cadebfb79ae86d00dc9ff080c2e58a5b6.nq.gz
│   ├── dce8bc916e4c1ba2ffff04b82d973c05eb18a74f.nq.gz
│   ├── ddbd963bc62e34563083f2bb2414722fbf73a35a.nq.gz
│   ├── de637347f5e9e9ad8fade80d245ba91cb07d8902.nq.gz
│   ├── e602a54d08b5ef6ac2992077750f9b2140caa1a4.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea78104b90550db8a8b046c31550d43c8b1cf8f4.nq.gz
│   ├── ed7856c2090f2e543235d384692474ba8d6e34e8.nq.gz
│   ├── efb0e62a974e2694f89603e612aa0399c731a95b.nq.gz
│   ├── fb1a8437b940e29c50d9bdb73ca242df8fb886ed.nq.gz
│   ├── fd1aa77bdc2c55f7307731ab464bb98658193f56.nq.gz
│   └── ff1875b0bca126d485c410a82c8b20efdc44bf84.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 2442e8c15152d1a7f66e90f07642baf87dba65f3.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 65 files
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

[explosion/spacy-transformers](https://github.com/explosion/spacy-transformers)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
