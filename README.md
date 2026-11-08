# Repolex Knowledge Graph of nipy/PyLocator

RDF knowledge graph data for [nipy/PyLocator](https://github.com/nipy/PyLocator), parsed by [repolex](https://repolex.ai).

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
rlex download nipy/PyLocator
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a8561fbd5c9a3f988ce9abf017a1b01759fc250c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a8561fbd5c9a3f988ce9abf017a1b01759fc250c
│           └── chunk-001.nq.gz
├── blob
│   ├── 0019100428919de0f3b2dd83d468c948444511b3.nq.gz
│   ├── 01f73dd987907854f3d285370fc67f83566aefb0.nq.gz
│   ├── 01fba57a192a5cc50c1ae0e43fbe4d34a12a2179.nq.gz
│   ├── 06a4472b0166c6c846079bad3951ace3add2cd59.nq.gz
│   ├── 0e02a3a7e6799ad069ae33a8a02a48e533f2812d.nq.gz
│   ├── 0f1d6667584194e0348fabba627f57cd5a6f621a.nq.gz
│   ├── 154e9f93864ef8d299fd0c6302d8a27261b2a76f.nq.gz
│   ├── 16bb06b3819b78fe8fb033c9e623088f68d50dfe.nq.gz
│   ├── 19444aab1fce5812e4701c2d16d2371986a5208a.nq.gz
│   ├── 1a1304e749d950503d611bd1f1101887571f005b.nq.gz
│   ├── 1b6c4a0068db86475856a6cc0d793e73eef235f4.nq.gz
│   ├── 201cf750bb5e8a8be11855d53b40efc06a122634.nq.gz
│   ├── 21f34c7c848f3884e8541cbe48712e25dd9476ff.nq.gz
│   ├── 2459f26a1cb9cec399aef68ac56385cf09ab0854.nq.gz
│   ├── 265c81bf2c3147503796d7825ca85cdbfda8c412.nq.gz
│   ├── 2718764cf037f78de1babd80009453aac89b49c5.nq.gz
│   ├── 27ed038568fad120a5cb58596af9e632f81cbfd0.nq.gz
│   ├── 29409c0b7cbb55372f2d54cb7f0685e2098a6f6b.nq.gz
│   ├── 2c650976055715a7fb270d655b754515a14e89b5.nq.gz
│   ├── 2cd7b26b0c9fbc1abd8f8b67f7f586d7d7b6a21c.nq.gz
│   ├── 2d0521fd9dea95ff14429bb406c5a1cac27d4f16.nq.gz
│   ├── 2ea41fbb7a282b8d199fa1254cbc757a49cdfb18.nq.gz
│   ├── 377ae51a22d8d23c0d0e900a87ea42d198571a6d.nq.gz
│   ├── 37dcb93bae5f4184fa2b2f1f3e9dc16a277ebeee.nq.gz
│   ├── 37fef6245e30170543f6f57d7fd9c1da9df611a9.nq.gz
│   ├── 381ce2fee24e608286c4da7e03d543b0cc642979.nq.gz
│   ├── 478fae20739eaad24ef1c635902deadf19bf1885.nq.gz
│   ├── 47a1ba22a396e838dc864e3318f5e273e8a55d29.nq.gz
│   ├── 47cfa7544ec864834862ea0cf983e0d2f8d6c98f.nq.gz
│   ├── 483124ce72db6af3a7f0ea1d4c322e6b6097e70e.nq.gz
│   ├── 4b69578fe8712eb93fdf60b0921c2128d93ec6a9.nq.gz
│   ├── 4ba03c2942c5cf56333111e8437c8d33919009b4.nq.gz
│   ├── 536f6aed99846a93d5f42ec1c26ea836eba2101c.nq.gz
│   ├── 562f1e8e25e3990831d025c9c4e3d7cb2a767d09.nq.gz
│   ├── 5b4d5e80b683e156c459c9416354f0af4a4c6fa0.nq.gz
│   ├── 5e0342b0dc553b79be64797563561bfb669b5c63.nq.gz
│   ├── 6a94188316217534bb07dd89a4c4f663bce7c10e.nq.gz
│   ├── 6b42ac9b5c7c610839a299084705f858fa149a0b.nq.gz
│   ├── 6b66e66d4f5a5389677aee1ed8020375e5004b72.nq.gz
│   ├── 6bc9bfa8e34a879badd4e258c9ba7e5377545d04.nq.gz
│   ├── 6feddba469250b504211cdbb9fca6e9055faa8b1.nq.gz
│   ├── 75e12096e6fb0ba2e831d2765647dd89e35ff6c6.nq.gz
│   ├── 78951afa27f20d5a984255fb0751d3621f3a6dde.nq.gz
│   ├── 78d8daab4f6bc5ae22de5ec0d5589877c3ad8c4f.nq.gz
│   ├── 813d6833a8bda61372054e1ecb0926a390e7c56b.nq.gz
│   ├── 82cbaf19e7bc1155bd648a1c622f22da3fd17e5c.nq.gz
│   ├── 83b2fbcf4386418e8cd6acb214d9899e2de982c2.nq.gz
│   ├── 891c03944ad0b10d8a5a170e40f494cfbc3f6962.nq.gz
│   ├── 8afa58cceadf4349cccaba1122065700aafa8bdc.nq.gz
│   ├── 904270a52a1aa88ee895bf3e8bcf3d53da06d510.nq.gz
│   ├── 9988e4b2223fda93959da18bb825592d4130bb23.nq.gz
│   ├── 9de6baabde91b9e3813354b398356e4fc1a67d72.nq.gz
│   ├── 9f331496a8eea8a132ea8b81bc6e3f2fbc700537.nq.gz
│   ├── a5bddc99edc212a80e4a7015dcbf3ada9a354965.nq.gz
│   ├── a81093c675a8ef0f68e233cbefc2c1011adc21d7.nq.gz
│   ├── a898863c2b51417755079e7eedad8e64b338f67e.nq.gz
│   ├── a99d7232fb9e08628977a8aaad91c5a91ee75484.nq.gz
│   ├── aa761f061f52b274092f0595099f0e132c3dd647.nq.gz
│   ├── adf294c5e47bc917390cb10709d3756f0f1d6fe7.nq.gz
│   ├── aead07453f17c5240c463d1fe34943a2973f232b.nq.gz
│   ├── b22bf765f999cd43efcb9099c26fc47a209699b2.nq.gz
│   ├── b51cb88150a7477df8924ea3b02e40cdb156a30d.nq.gz
│   ├── b6491b2076374427b982290de1d7f127a24e2c62.nq.gz
│   ├── b831f18cd484ae5ef52be5600abbe3fa88f9213c.nq.gz
│   ├── b9ba9f769eaf983d884d6bde46c76e3a0d67b7b0.nq.gz
│   ├── bf73fbfd7a2fdb860f46b50da17abf175b62294e.nq.gz
│   ├── bfe77440f85545a2ef57f7efb413a87370ec8529.nq.gz
│   ├── c0f73f50646091c8d9200412d776860c71bc7d6f.nq.gz
│   ├── c567eba3a98effa0b1dad668ea3d96042e565a66.nq.gz
│   ├── c77eeb544e78bd38e9f32b5315026061c9c8a483.nq.gz
│   ├── c8c21abca669bdb26a91f8b44a53097c5c8379f0.nq.gz
│   ├── c9b568f7eac5edcb35307bb793869b2c20e5ae41.nq.gz
│   ├── cb2726f755652d80665ea7fad07bab35a2a98f46.nq.gz
│   ├── cfdb083d6208198bcc48f1134ba4c4fbad5c14c5.nq.gz
│   ├── d27caa4e0b30286892c58df93637b484a35ae956.nq.gz
│   ├── d431ecd3f900f53fff222070a120898e27a74aae.nq.gz
│   ├── d75455069c582e09ef5a19fa9d1e45f0e37cef6c.nq.gz
│   ├── d9eb8c34ee7394d87747bceb073afca7d41a2d9b.nq.gz
│   ├── dc19fcf81763220ab304063f040f4a694118c682.nq.gz
│   ├── def9ddfdd51817dfa285927c5220285603b3c77e.nq.gz
│   ├── df5713154facbf4ee5af58df647b15ae5562679e.nq.gz
│   ├── e00efc31ec2571318522f822bae7dcf68850c77d.nq.gz
│   ├── e0a2d3b7a1a2717c4809d6645a4a56b05829fc25.nq.gz
│   ├── e11eea90210734962afe50e53ee5892be6eb100e.nq.gz
│   ├── e19de6741fe402a8ce36d6424c10f2e8c034e39d.nq.gz
│   ├── e1c61ae1f3314f2607069eab3a20e331e8c7e7b3.nq.gz
│   ├── e43461874b22b7ee670ed5ca0f0077c3fdbe33d0.nq.gz
│   ├── e4dfd5cc787652cb1b90833a6e2572890c8f752c.nq.gz
│   ├── e68c9d493a9f72f45f531aa6d10db25d81fb0af5.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ebb2a4182bcc5962bc7539c7bc1c61eed31c3099.nq.gz
│   ├── ec246a8363ada0bb956aaaa0fea01879e9657cd7.nq.gz
│   ├── ef0e790c4acdf1790549d4b1d5548b5b22b4d99f.nq.gz
│   ├── f2bcf62e4052e52a6f9eb303646e088ef3de69f5.nq.gz
│   ├── f38293abcba40e926d796ac2129e2d6ffb98f867.nq.gz
│   ├── f39e1f570d9b97f49c0a8efb698f377f939172ec.nq.gz
│   ├── f769ddbbdb55b346b26e447f0791b96255da439c.nq.gz
│   ├── f852a4a960d9a74a501f17678791aa81f6930440.nq.gz
│   ├── fa8f0c731cb8cd84e660e8aed032e0e98b636832.nq.gz
│   ├── ff827913e11d8464f13d8795989285313390a0b3.nq.gz
│   └── ffcf51b353a106e50b3c4ec5bbd4ab4342bc7528.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── a8561fbd5c9a3f988ce9abf017a1b01759fc250c.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 109 files
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

[nipy/PyLocator](https://github.com/nipy/PyLocator)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
