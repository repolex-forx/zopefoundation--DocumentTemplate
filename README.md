# Repolex Knowledge Graph of zopefoundation/DocumentTemplate

RDF knowledge graph data for [zopefoundation/DocumentTemplate](https://github.com/zopefoundation/DocumentTemplate), parsed by [repolex](https://repolex.ai).

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
rlex download zopefoundation/DocumentTemplate
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7a5f477e3c29a8242db9fb0d635dfb1746615c9a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 7a5f477e3c29a8242db9fb0d635dfb1746615c9a
│           └── chunk-001.nq.gz
├── blob
│   ├── 00d6c4f2a082f6e49e56d573e20097792ae9b8a6.nq.gz
│   ├── 01998a13e2c216eaf51dd3ed9af875df6560ff01.nq.gz
│   ├── 04b18a4175950e6ed4c4d672b3dfc1f90c81826d.nq.gz
│   ├── 05a8e6862ca524c5758c7514146a51a1ce5bb01d.nq.gz
│   ├── 0a9f9914391505a7264c9ac6abb887e8ea1783d9.nq.gz
│   ├── 0df2200864b71f187222fe8da91bf2f7e84dcaa8.nq.gz
│   ├── 14eea5c2e4a5a13bc78b8db88e9cc3f1f38c68de.nq.gz
│   ├── 1a422d021fada68fe4d9ec812579f298d0e65476.nq.gz
│   ├── 1eee2ced90c068d05b79fc923814650cf3fc5fb5.nq.gz
│   ├── 1fe50256b2654527e526deeda7e55736479d0889.nq.gz
│   ├── 2095d4394dc5799fdad6c99d166e14687a4c3b64.nq.gz
│   ├── 23a344086d6bf20863340e2a338a1883c0c045fe.nq.gz
│   ├── 2632a94123963963bfee3fbc2eb24b24f792aae9.nq.gz
│   ├── 30caf16a0f3fca3bd702c8b943100a5062509688.nq.gz
│   ├── 38483a5bc9491520242b9ffee13aaa2691bab805.nq.gz
│   ├── 39ba6a8bfc0a55b7de8753d50cbb53c6c5b28b32.nq.gz
│   ├── 3a960de95530d83374fd6a96950157d7bc0933e3.nq.gz
│   ├── 4103c2ef4cd53c97c3284dcb61ded90f4ae444ef.nq.gz
│   ├── 50a91183eb11636978ae05217e2ee74dd749156d.nq.gz
│   ├── 54ef1fbb743c1be7e5de6852e58a15841f50cba9.nq.gz
│   ├── 656bd7acd0e501915b3bab0c5f747eb46eae19ce.nq.gz
│   ├── 66eadfcea5682d191fc8844ea15e77464caaa444.nq.gz
│   ├── 67fe1fbf166ba7910dfb9c5859259778b6d7adec.nq.gz
│   ├── 6ee7ae39cf7f5fd29f9ced43833e40de904171a6.nq.gz
│   ├── 7016f46ceeab3149255b65b69532fb1c29393c0f.nq.gz
│   ├── 72d1b943c25e137fc2ffb276b629e6ba06eda914.nq.gz
│   ├── 743268ea68dc49e96ea10b1923740774fcb06756.nq.gz
│   ├── 7dfdbc8b7fb1fafbe73b3e1818a79298b6bbfc37.nq.gz
│   ├── 820bd3710616ebeedaa53e843469a1d7731bdf14.nq.gz
│   ├── 8468834a9ae787691f243d57c6ec0dbecbb69b79.nq.gz
│   ├── 864e3400f51a674cdf15c9010020f5a691693181.nq.gz
│   ├── 8843e4f8daf7ce037c9185818d444eac1455fc06.nq.gz
│   ├── 979a7afec00213aca62c2460da3f8e77b4c97e84.nq.gz
│   ├── 9aea56fa71380082c334d7f1805b6c0e2d6b423d.nq.gz
│   ├── 9b43eb2bfc04a08efb5b897ecbe28c5253c97d0c.nq.gz
│   ├── a0c56896dece0960f66bd4e7720b7556a55921a4.nq.gz
│   ├── a128fb906d1482fbbc7b731c965c1d29c48189e5.nq.gz
│   ├── a2b2dcac566ed48222b7b73c94a53358843df545.nq.gz
│   ├── a766a804ccaf653c28b4059d73eb699e2971e8ec.nq.gz
│   ├── aad785ab8c1e63a58437629ad8a21928d723c763.nq.gz
│   ├── aafddff801c9a2a6e9ef235cee553c4c3728e793.nq.gz
│   ├── ab8ee119c91ae3a6710a95d1d3da56344680249d.nq.gz
│   ├── b1a4a419f001cffb485a1bee87b23db50d01bdbc.nq.gz
│   ├── b8581dd898cbb33e63961b4d181ff0ffbe5d03ee.nq.gz
│   ├── c1510d98178c3de0bfa14404a51a8f38482d8297.nq.gz
│   ├── c734f43700e31d2e29734c27ac3c54d7b568eef2.nq.gz
│   ├── c7bcfa62ba0adea60cc51b111c765bbb75011f6f.nq.gz
│   ├── c886de823535afdf1373110208bfb53d097f9f45.nq.gz
│   ├── c9e2a18f32f1f9edb4b5454445ba8cdf3ef739bb.nq.gz
│   ├── d42adf146765ee256320aa6df4dfbd62cc6f9736.nq.gz
│   ├── d450742c9f4e6e78bc16ce40473b7f6b72b85b88.nq.gz
│   ├── d67ef8f91aad6f7a4b1d1010f9a3732a06f302fa.nq.gz
│   ├── da8ec36072d5560c58b2066836f5f70cf56f3922.nq.gz
│   ├── dd11ae7ae6db50ba2525c6c4984c77a12aaec399.nq.gz
│   ├── de9138315a169723e5b45a6a0cd023059727273c.nq.gz
│   ├── e1f9ad7b3b48377bfbfaa1b380c384ddea24060f.nq.gz
│   ├── e911eff4c4ddc00365a0000cb5b22678d305cc0a.nq.gz
│   ├── ea4154184db5c033779fc1dcc463dd4c179e431b.nq.gz
│   ├── f08edc31b4415aa48bd68c3195e00e32233ed9c2.nq.gz
│   ├── f43442298113b9a32235d572937c1d26352b99b5.nq.gz
│   └── fa3b38a9b68206ffe91daf0590dc52dc5c14c8c3.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 7a5f477e3c29a8242db9fb0d635dfb1746615c9a.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 69 files
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

[zopefoundation/DocumentTemplate](https://github.com/zopefoundation/DocumentTemplate)

---
*Parsed on 2026-11-02 by [repolex](https://repolex.ai)*
