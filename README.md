# Repolex Knowledge Graph of cohere-ai/north-mcp-python-sdk

RDF knowledge graph data for [cohere-ai/north-mcp-python-sdk](https://github.com/cohere-ai/north-mcp-python-sdk), parsed by [repolex](https://repolex.ai).

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
rlex download cohere-ai/north-mcp-python-sdk
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 069489699204bd4815ab85bb5fd798b807a6a980
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 069489699204bd4815ab85bb5fd798b807a6a980
│           └── chunk-001.nq.gz
├── blob
│   ├── 0eb22be258efbb6fbb50f2ee524ef03565d79ec6.nq.gz
│   ├── 17c1c3691f1ded0ef16845fcf1f389cd02f402da.nq.gz
│   ├── 190e1c1a30cfda4642ccc31e16d18bf1b084b1c7.nq.gz
│   ├── 1ad84bdd6f9fd4edf4cfb28b6c264485744a6e15.nq.gz
│   ├── 22472887245e75d95195a0295c397d6e834b9f62.nq.gz
│   ├── 24ee5b1be9961e38a503c8e764b7385dbb6ba124.nq.gz
│   ├── 320eeb793ec82cb6259690deaabd3136f8e9d7ab.nq.gz
│   ├── 32a37e9eca5c418742892fb6d55ac81630d41657.nq.gz
│   ├── 3d68e950f6bf3f2f2c7b87c1ac0f776a404964b5.nq.gz
│   ├── 43f2b47019c165749ee2d7a01e188cbf814a5fc2.nq.gz
│   ├── 4809eb49ce79dc71390026e78d95698110d8147e.nq.gz
│   ├── 4c0e0b721762caa62173f90f2bad60dd69a7202f.nq.gz
│   ├── 4c2137b2244ec08f354f2803bd1b677d422f7d41.nq.gz
│   ├── 505a3b1ca2716907d5b292ab90c36df043c42bb6.nq.gz
│   ├── 57f5efe1c1a80ae8769d3c2368ed88f86157e1d4.nq.gz
│   ├── 6633d444ca27698949167274eb665b7bd9a2dc0e.nq.gz
│   ├── 66bc775c1f8829ac0ac34a51b6031fa7217d695e.nq.gz
│   ├── 7c42763163fbf7c849cd9a4cbbcbdfc4b15d7fb3.nq.gz
│   ├── 7cb30f546c0e131b97557863f1b2ea867ae57b6b.nq.gz
│   ├── 7f8bd3a44f15d6b91b3ba4718c5be9ed81523d46.nq.gz
│   ├── 8590ef088d309a7aa7ef3385cc9689a7bc60e069.nq.gz
│   ├── 88aae312014d00f5cb14f588191077903c06d7d7.nq.gz
│   ├── 88b195e4515c525d925c62a743d0a7bc6d73f9f7.nq.gz
│   ├── 8c918b0f943dcf94f64bc7b9f1515404e159fe8b.nq.gz
│   ├── 8d1936259292eecbc4083bc777ec61274cce5e18.nq.gz
│   ├── 90d8412056651a83bfb861b14f3cdb27a8b595c8.nq.gz
│   ├── b52bd3de911fc5dfad6a71fb7940c76c0fbb0591.nq.gz
│   ├── b56baf3476108d9eff0b602e27432bdf9a97b811.nq.gz
│   ├── bd8ee89ff0b3a52a4250280b16ff017b2e958182.nq.gz
│   ├── c2cef533f855fb76d8a1f7482c6d178863f95749.nq.gz
│   ├── c2e641bf5fe1c6f67ae932b11a093146a2ac2226.nq.gz
│   ├── c4e9dd407543f0fdf39907813465ae6f064b6104.nq.gz
│   ├── ca105591a74976e6324d51bdba1b1a73346312e3.nq.gz
│   ├── d0e72f1d71201fc4118adaebcfcd5b0bd868b734.nq.gz
│   ├── d973fa66c5d09493367d2b218a14c3ba47ee5c09.nq.gz
│   ├── dc5de052ce86211a6ad74573ac6ca6fcc909fad7.nq.gz
│   ├── de5468cf084b997d71c245a16961ea94ef12333e.nq.gz
│   ├── e4fba2183587225f216eeada4c78dfab6b2e65f5.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e770c91efda2e8eaf2e672cfa0d1fb552e60794d.nq.gz
│   ├── e9902b3fb14830141455ac8a1e5e9598abece3e8.nq.gz
│   ├── e99928bc81825e35ffa33e099b5996aa4d00aef6.nq.gz
│   ├── ecadeff98447b8a666850289fb972a489f5a3824.nq.gz
│   └── f6c012938e3b0558342d4622d9e0f00203c8f09c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 069489699204bd4815ab85bb5fd798b807a6a980.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 52 files
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

[cohere-ai/north-mcp-python-sdk](https://github.com/cohere-ai/north-mcp-python-sdk)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
