# Repolex Knowledge Graph of google-deepmind/treescope

RDF knowledge graph data for [google-deepmind/treescope](https://github.com/google-deepmind/treescope), parsed by [repolex](https://repolex.ai).

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
rlex download google-deepmind/treescope
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7a9f0e82c9c1c05577dd6f386f9ee48e4d7d3175
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 7a9f0e82c9c1c05577dd6f386f9ee48e4d7d3175
│           └── chunk-001.nq.gz
├── blob
│   ├── 03d4b4cb9f4f1ae3607da3b848acd36089196965.nq.gz
│   ├── 067a8190154781d7b09298287496a3b6c4aec171.nq.gz
│   ├── 07e37dba55715b2e5debbfb6651663266efbe113.nq.gz
│   ├── 0a764ae7af0143be9a1470d45c45ac6dd9fb4ffb.nq.gz
│   ├── 156e133c2183b385052cfd7d6216bb4dabd74214.nq.gz
│   ├── 16f29fe86d5485a03c6c59f447d7b02e5e5991dc.nq.gz
│   ├── 1807b476598a3784589c1f86a2a77d996c48131d.nq.gz
│   ├── 1f0fd5a6f7c9d416cc3c6b8bdb28d799568ccfbb.nq.gz
│   ├── 1f45e88a99e5b2a94e565f1d0238888f0ce78ea2.nq.gz
│   ├── 200e51a1f908e74741c2e29f6c3d3fb34cd36e56.nq.gz
│   ├── 254c5a02413a0b3d145cc39ebad2e19623725871.nq.gz
│   ├── 2db42d2fd9d7062b79bb17ee903fa3f5d22d474e.nq.gz
│   ├── 2f385222ccb13cb872cddc277fbc6cb0ac00ab7b.nq.gz
│   ├── 2f99f242ce1c63824fb88c696ca7bfde46d4a29d.nq.gz
│   ├── 33b4d8ac61e54142fc8611de7bd93be5cbcb74fa.nq.gz
│   ├── 35f52c2f0bf6b36e748f8164f2d9340c79d8a110.nq.gz
│   ├── 36071c1290ea9b8c309ffcb12ad12797baeb8035.nq.gz
│   ├── 3930041f13f95a00b4fa9aa34bd0e9d90d279f01.nq.gz
│   ├── 3adaaddba70f341ed50d9fb08ef9cca87805ba85.nq.gz
│   ├── 3bfe0cb955f0cac7b34ae0c60adaf2bda55d9a8d.nq.gz
│   ├── 3ccb206bf5730a144eb6873bfbbbe11fa3ccfda9.nq.gz
│   ├── 3d3b773d44accfedbc3e3d6dd7df0501db0f2d70.nq.gz
│   ├── 3f05838db6d60dfef225a9ea8ec7d3e3081f1471.nq.gz
│   ├── 4224ad87921e8ebfe2283250bb8b5a255f8bda92.nq.gz
│   ├── 44808cbcbab65997cf147d59b9b43aa3b73f925b.nq.gz
│   ├── 46a910bed9acf49ff6ca352f63656702eacc6e84.nq.gz
│   ├── 4afcce2aa46f1266c1d286f5b5fd03e137e39fa9.nq.gz
│   ├── 4c4c87be6b730856887bfb1fb4ab167df6d44917.nq.gz
│   ├── 4dad3d719fde58fa5de7310f03fcf307192d5e6d.nq.gz
│   ├── 4e66431e72333422fe0bfbb92bab6d5096927519.nq.gz
│   ├── 51b91afc1c623c8a6902d87f127bb9e5ecc4516c.nq.gz
│   ├── 53248cad11ada3cd201788b609e64c7afcae4962.nq.gz
│   ├── 5536fa10863f92500ee1d202eac32102dd02471f.nq.gz
│   ├── 5921461fc1d507530b4b54befa566fb0094efb31.nq.gz
│   ├── 5dc4cde5dffaa7fa0a6d2ff39942c16872cf638b.nq.gz
│   ├── 628b639dc290cc04366596840512980a01db39b5.nq.gz
│   ├── 62ff5ad10eac5ce813621f80a3f52c6ed18df7f5.nq.gz
│   ├── 6368494b974b1fab186af6e6371596a0b815d299.nq.gz
│   ├── 67380fec667e39cd6cb5fd3d0ac10f863b6b74ca.nq.gz
│   ├── 680288e55472656b10d3e7b870b97e618a1f854b.nq.gz
│   ├── 69a4600404c7ca49e0ced4c55379f78c173ba892.nq.gz
│   ├── 6b413f6b9f2e28e4c0a752229b3fb1a59fecbd23.nq.gz
│   ├── 6c3409accb577a3743c766df9b6b723f30f6509f.nq.gz
│   ├── 6e4a58e6a414d0a7bd2b2b79a0b8d8aaa1700c9f.nq.gz
│   ├── 71309dabcfa9cb355aef598cc7350a3f407ad0d4.nq.gz
│   ├── 722f33a40583a44948e96261cdc2c042e6734cd5.nq.gz
│   ├── 750267ca96ea909979ecb373f5db94a5b3ee2adc.nq.gz
│   ├── 7752c3cfafaf9525c81b306315b0c1cab6e22937.nq.gz
│   ├── 77c81fccd9577f14dd5de2a01f4f1eb06821bb58.nq.gz
│   ├── 7f83bf562565ab10a8aa70e2082c19334cbebdd7.nq.gz
│   ├── 8130e712c3445d5d0ae9384b51f1b8940e3e7b69.nq.gz
│   ├── 84013c4fc07845b8519efc083a2a7f9f3a3fc7d6.nq.gz
│   ├── 85c6c1796eca9e87d761984bd5fadc96a60a99f5.nq.gz
│   ├── 87a82eaacf3518dbdbf27807a6ce7d8a0a392a1b.nq.gz
│   ├── 88b500f85632752027e2e85d82b736194b51dc15.nq.gz
│   ├── 8c73897abc78ed4f46efde79911d7c3458d1b1db.nq.gz
│   ├── 94fe8f900ce0ee16f4ae3219ebc43b742353775b.nq.gz
│   ├── 983e610414974da8adce037ab70cb6e28b43f8b6.nq.gz
│   ├── 99cc21215d28d2f08ed6463ccf116796b6f084ac.nq.gz
│   ├── 9a36e3565a635a9d93d41fcf21733aba1a4515db.nq.gz
│   ├── 9a64d6ad5b223078a9ab372338799e9155e09390.nq.gz
│   ├── 9af066e124bd9d4e608769a1cbed6f282503c79f.nq.gz
│   ├── 9d5d7337fa0bf85c2566eda28d913f37cf3bd58e.nq.gz
│   ├── 9f719800606bd9a19a0fff10514c3101799d535d.nq.gz
│   ├── a61e3be6e8eea33d90884b87cada049ad1531c8c.nq.gz
│   ├── a784a9a5282f818280236604d11477010043d695.nq.gz
│   ├── adbf3c572054261fbb8f1cd634d5dc2bef74aa6e.nq.gz
│   ├── b24f1483dea7786045c917bc1ccd0a581edd72d5.nq.gz
│   ├── b76e957d236997f88924060eca93891c2aa5a825.nq.gz
│   ├── b958c1526386f64ac96d772d131498b57d93e657.nq.gz
│   ├── bde5700b7b408100e260d7ad8515b520ebc349e6.nq.gz
│   ├── bdfdf194e32c9c9a6247258066356aaa1418d288.nq.gz
│   ├── c3b2a1f5513bd56083b286c7c7139594024b93da.nq.gz
│   ├── cc6397709961fedb7e329617aec1f63d2d6a2b38.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── d7931f930c22b1b655f4ecdd7d99ad22ac8c04d7.nq.gz
│   ├── d94adde7b73a40c14c87f0a0cd164d90acf63479.nq.gz
│   ├── dbdd13608762ccbc2234aeba60c57e570d7d8910.nq.gz
│   ├── dee74eccf2b37a99570d7b36f6ec771f690eb2c8.nq.gz
│   ├── e268e4b6e90bbd602610aa6ebf630da213c03cac.nq.gz
│   ├── e3f7ba9d2befcae144b7bec51d0c1da838e52af5.nq.gz
│   ├── e5c90252a28ed34579ac9d114ea8040c0d4420fc.nq.gz
│   ├── e6689f663f3ca33a279eae160f4feff463bfce36.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e85d9451a8b06aef26eecd751141c6737e1ae2f9.nq.gz
│   ├── eeb1015998d22abe7325ede7f00aa9f5c6ed491b.nq.gz
│   ├── f6a5fc63e23aef135deeb27e4e419b7f712bd46d.nq.gz
│   ├── fb1e785591f6da80e69a00655f3c4f62c28dcdb4.nq.gz
│   └── fe59d1ebdf4de24d473d3ccf431a4f9f5698d415.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 7a9f0e82c9c1c05577dd6f386f9ee48e4d7d3175.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 97 files
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

[google-deepmind/treescope](https://github.com/google-deepmind/treescope)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
