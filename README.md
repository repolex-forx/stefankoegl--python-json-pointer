# Repolex Knowledge Graph of stefankoegl/python-json-pointer

RDF knowledge graph data for [stefankoegl/python-json-pointer](https://github.com/stefankoegl/python-json-pointer), parsed by [repolex](https://repolex.ai).

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
rlex download stefankoegl/python-json-pointer
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── ada0cade3bcd21d5726dd701d092c7d0d1ce8c41
│   │   │   └── chunk-001.nq.gz
│   │   └── fc5603b445c09c8ad9414f7ec2705e58d4bfb618
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── ada0cade3bcd21d5726dd701d092c7d0d1ce8c41.nq.gz
│   └── repolex
│       ├── ada0cade3bcd21d5726dd701d092c7d0d1ce8c41
│       │   └── chunk-001.nq.gz
│       └── fc5603b445c09c8ad9414f7ec2705e58d4bfb618
│           └── chunk-001.nq.gz
├── blob
│   ├── 016ac01da0c360befbcc14b0c674d42873ea16b1.nq.gz
│   ├── 024d9889e8fc56e0fb2c82a594396b55f4b0666c.nq.gz
│   ├── 06c8aeff26b8b2de36f4702f93a5e4096fd923a8.nq.gz
│   ├── 0f9b9f67c6f5ce6dfdda92573503509776aecaad.nq.gz
│   ├── 1dcd460ea07712c8aa40b6674157d55b3c37bb5b.nq.gz
│   ├── 2285ffce192fc66df4b769982e2d782339f6921f.nq.gz
│   ├── 239fccaa5617f3232916f45f1453ae68a87a6e4f.nq.gz
│   ├── 26f34eea1101cdeb00f1ba2d756861d4ef243d23.nq.gz
│   ├── 2cfd0498a1792df364957be95ba0e4c531f81590.nq.gz
│   ├── 3276190789a34b98b4c117da956a494c492ea1e0.nq.gz
│   ├── 357bebd9bbdcb92f1a537206623d57b2d4fd0391.nq.gz
│   ├── 3b70831aea68b70e8baf7719034ea721b59ebd12.nq.gz
│   ├── 491196d773493c591f1287107c3d368f2f8263d3.nq.gz
│   ├── 4b36d81b7cf5e9a36ded0d00a9507fac2c2fee07.nq.gz
│   ├── 4e74a2d317d54e9279c15d32c3484f3248deea08.nq.gz
│   ├── 5493fbbe2a5209dc24a06af8b8d5451a251531b8.nq.gz
│   ├── 57ba54a011acd9ce272681755dd2b986d0e456c1.nq.gz
│   ├── 683330dbee8f7377a1bc431f4672ea276935bdba.nq.gz
│   ├── 6966869c7054c18810eb323772b93ba5a42cefc5.nq.gz
│   ├── 6fedd8fb11d5e7344de56653cfadd99767f35711.nq.gz
│   ├── 785d397f6aa5578baabce67410b762869106e4c6.nq.gz
│   ├── 7929d6d9bf6dbda2f3ed2437d4d37d4b1281444a.nq.gz
│   ├── 8319fec44d8e4d467b2e4827738b91ff706f93d5.nq.gz
│   ├── 861d6b2e75ed97304e2205d5e1aec2a3de877e39.nq.gz
│   ├── 9384294dee393358255a375c6f27358b6681a990.nq.gz
│   ├── 9d7b21d48c4ce37056fc76f3cbf06a928e5b7738.nq.gz
│   ├── 9f9b74f91072c797a0b4f59bb7e96e4e195f7d45.nq.gz
│   ├── a011a88232b8396707c1318b48e9fea67f74b4f2.nq.gz
│   ├── a11f33611e2804fed0d7eba215a349276b164ea0.nq.gz
│   ├── b4a01deb6fc22367c4315bfa4bdc1210bb8b8a4b.nq.gz
│   ├── cbb2a24549eae81684d80665ac4785f04cf6d431.nq.gz
│   ├── cefc95a1574a4f1eedef8a2e301ff9dbbdc52209.nq.gz
│   ├── d1926e78788a71f3d0d66db497600dc037c24313.nq.gz
│   ├── d3d27ae5f16ffc4b3ce592299f30a63774aa6e39.nq.gz
│   ├── d4c8cb758171d53716093558dea0390513d1b832.nq.gz
│   ├── e1e0aaefb113ce4f8436a4bf1021b6078979fa14.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   └── f472f575f63acd43eda461a02d21f84719f32fef.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── ada0cade3bcd21d5726dd701d092c7d0d1ce8c41.nq.gz
├── filetree
│   ├── ada0cade3bcd21d5726dd701d092c7d0d1ce8c41.nq.gz
│   └── fc5603b445c09c8ad9414f7ec2705e58d4bfb618.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

17 directories, 51 files
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

[stefankoegl/python-json-pointer](https://github.com/stefankoegl/python-json-pointer)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
