# Repolex Knowledge Graph of klen/muffin-example

RDF knowledge graph data for [klen/muffin-example](https://github.com/klen/muffin-example), parsed by [repolex](https://repolex.ai).

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
rlex download klen/muffin-example
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 83b0478668737279b1b94565467c11c7f1fc5b42
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 83b0478668737279b1b94565467c11c7f1fc5b42
│           └── chunk-001.nq.gz
├── blob
│   ├── 0a6ee958310ca78a98bf4803c291d5898c7fd5b4.nq.gz
│   ├── 0fb8a70b07566172e0dec41c643b4b8ed1710eed.nq.gz
│   ├── 10409ce07351b9cbe2c9eb4623d1f87b4dfbe92d.nq.gz
│   ├── 157522d945e4566927b1028762e66fd31199a072.nq.gz
│   ├── 205e3e6ceecb22e78ade65621cdffc6a12d3daef.nq.gz
│   ├── 23c5c150f58bdd129447223d88288e859f8cccb1.nq.gz
│   ├── 27da54149a82e2bffbf4b05499b0d8548c24adb4.nq.gz
│   ├── 41b8513cdc2851735bf4c4eab7a4bf80afceb6cf.nq.gz
│   ├── 48f6d70ce60007f5bec7d5e69a79d13b16e668ff.nq.gz
│   ├── 4e9d61de7b36b773010ccf31a908bcdcc57a198e.nq.gz
│   ├── 4f46c2128c4b5e9452598962ff0d7e416cdaad4c.nq.gz
│   ├── 5de0f3a0cde7dd094a1611f60bf0a5e957b5971e.nq.gz
│   ├── 5f1d5686f3dc12105665875988bbe0b90d32c2bc.nq.gz
│   ├── 62f8cdc1a28f0cd615942e2fe808750652f91d13.nq.gz
│   ├── 653221cc63e67f3579c5680279f2537e04211f34.nq.gz
│   ├── 666ce2a519fd8f0c3599a11f968422b82612ca92.nq.gz
│   ├── 66a3a983f4c052850c26e6b85c3a16df7ab718d9.nq.gz
│   ├── 78df056a6afd6b2f7c5a8695635380a19f30acd9.nq.gz
│   ├── 7a3f07ab83552f47a8705fa5d22729a324a2f71a.nq.gz
│   ├── 86569233e116eadd8264e969086e26a5cd9602e4.nq.gz
│   ├── 87da929e2733e513721d52b24506415aa5c9e4e6.nq.gz
│   ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
│   ├── 8dbdd195c655e700716c2d788d6e1ec1af94a2c5.nq.gz
│   ├── 9303a3e84e9e4d8071bef77e6f717a23bf6a6851.nq.gz
│   ├── 9c4403316e8b66b24a62fd2f0711ec56fa64e941.nq.gz
│   ├── 9d75ce9b74896ebb09557d229fe2ff1e4c535a60.nq.gz
│   ├── 9e7d9a315827494f13549315eb5ddd6003394342.nq.gz
│   ├── a3a03c3267f4963e15d6d060ced3a68bd92d3b6b.nq.gz
│   ├── a62182ec303925457409975d2b255d82e159c008.nq.gz
│   ├── a68827cf23ae44006d530b488ad85ae283232ddf.nq.gz
│   ├── a85612cabb80cd2035ee24e3cdbcf53a478ac3f3.nq.gz
│   ├── aff823b66d955df53efffa1861db242bfdd73425.nq.gz
│   ├── b52627ead9c16363d95d14b6dcf1b19aa2cd2651.nq.gz
│   ├── b60c13016b6cdb11590eb420774b951136252746.nq.gz
│   ├── b7e858ba762ad18a14d75fbc345386e7a0b0c145.nq.gz
│   ├── bb9a2d8dcfb7bcae9511c3adebf087aca48d693f.nq.gz
│   ├── c4922339e67f4b1d7efb9439f0aaf3c799f74d68.nq.gz
│   ├── c9c39008639022ff30b8aa0823e58c228375c793.nq.gz
│   ├── ce48f87110f5a00c4f3320f9ed0c8e630cb23daf.nq.gz
│   ├── cfc15a49b24029be2eb3882bbb13066495c9a1e9.nq.gz
│   ├── d24753ed4bfcf9b9f101d24c923ba890a703ab25.nq.gz
│   ├── e5880e03bfcdb9861c07ca3f79d25ee4847fbb86.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6e7ec05135e84a3e104ec28537e693ef58b9ccd.nq.gz
│   ├── e728d03676c20ba87a39556e60b642f5df17ebde.nq.gz
│   └── f61d33f643dbcd7566bde894d14cd83516d1cdad.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 83b0478668737279b1b94565467c11c7f1fc5b42.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 54 files
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

[klen/muffin-example](https://github.com/klen/muffin-example)

---
*Parsed on 2026-10-20 by [repolex](https://repolex.ai)*
