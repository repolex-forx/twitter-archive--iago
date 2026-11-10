# Repolex Knowledge Graph of twitter-archive/iago

RDF knowledge graph data for [twitter-archive/iago](https://github.com/twitter-archive/iago), parsed by [repolex](https://repolex.ai).

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
rlex download twitter-archive/iago
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 019a4adfbfa913e6307cdc5a589089e95cfb6285
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 019a4adfbfa913e6307cdc5a589089e95cfb6285
│           └── chunk-001.nq.gz
├── blob
│   ├── 03b5854015e8c23c551e10b89eb5c99d1d093e01.nq.gz
│   ├── 064be84a9f65d284d7efe15a55b148bf53c8a8a9.nq.gz
│   ├── 0d66106094ec91c280c89db704d150db4afa6365.nq.gz
│   ├── 0ee5813988a99f0f96349603bb2d5e7a34be6b6c.nq.gz
│   ├── 0fa46de7dd9561d12a0b776830bf10ab807a9f80.nq.gz
│   ├── 0ff26b8f22108aef4cafc1f698fdef6f1e2f158b.nq.gz
│   ├── 1085112f3c00ffe7af45c76399cf5800c1047108.nq.gz
│   ├── 1273bebe72e145a26794afb5b3d6c523ce9f4b31.nq.gz
│   ├── 13b07d96e17c56527a1af25717ae096e323641fd.nq.gz
│   ├── 1711d68f162954a7281d78c909496d46fafca732.nq.gz
│   ├── 172c9a03435b8f82d189a18348a29a61a465b7f6.nq.gz
│   ├── 17ef9db6e4a0f7419ae1119222902af2255b42e7.nq.gz
│   ├── 1a0c0cadcb441b734a14af104f71445ab36735a5.nq.gz
│   ├── 1b76b6365d9895ee183f62f8f83d555de3335117.nq.gz
│   ├── 1c9a5ccd707775fadbd5dc76f496960adcaffd7d.nq.gz
│   ├── 1d8fc8259b5a9b72d9160ef0eb624d43bc1034b0.nq.gz
│   ├── 297860e6e9ad3f545db9403eb09e2d6ab04d0c4e.nq.gz
│   ├── 2a2d29dd54db10bb605662b45d801105efb8b4ef.nq.gz
│   ├── 2c254a3b97db6c2afc4c5288673056ebd9ddb5ce.nq.gz
│   ├── 2dccb04341785c4270568530841872eec560c87d.nq.gz
│   ├── 2f287af9985d698e46221b2c1f263c76bead352e.nq.gz
│   ├── 3076c05470bafd6562a003edba1549cccc1ecbb9.nq.gz
│   ├── 3266c5a5c59bb3b61a6e935334f1495e9f758e2e.nq.gz
│   ├── 32a5d6c090944a530be8296fb675e40a184c214b.nq.gz
│   ├── 36caa2030be40968d7f6085559053a7552af2a21.nq.gz
│   ├── 36e8ea7c0a6efe13e3d5afc45eebf0282b79eb96.nq.gz
│   ├── 3841d2c45e6e08e6065f8cbf3055befd438e29f5.nq.gz
│   ├── 3c000ad05352b88547dd0b5be329dba154aa91f1.nq.gz
│   ├── 3d26b9d9261003174bfbc75cfaae9e5f9bbecf4c.nq.gz
│   ├── 42577b4cb502e9b02984beea7aea630698424fc3.nq.gz
│   ├── 44657d5b24acba7837b218f4dcc1c5b320366deb.nq.gz
│   ├── 4641aa2e25b9ab374cc9be8b870ea8e5947abd83.nq.gz
│   ├── 4a1cdf99da77a0f1b96b8864e3d85bc92bb815be.nq.gz
│   ├── 4a85c841e7612f6158e9428b2fc85459d4307f1e.nq.gz
│   ├── 4bb7d1373606daca2ee64e76f6a8734b1eb8c0f4.nq.gz
│   ├── 4c7da79e5c421f9f7687aa6ef43456a7121fb57d.nq.gz
│   ├── 4ee0e507f9fcb3b98dea9b44b05b7b00d0064417.nq.gz
│   ├── 5124e97e9271979fdaa31b51e7cf4c2e61e652b3.nq.gz
│   ├── 51a1a484df955fa9a5c841bd4caa279284bcbe46.nq.gz
│   ├── 53fb52ef7bf296990418e357ce5002163dbacf52.nq.gz
│   ├── 54699dffc9e9d5ddda306b6077248d61cebaf9bf.nq.gz
│   ├── 5505992692077665796302e5a31e08ce9296396c.nq.gz
│   ├── 559d7d6f887212c23da30e3fd8921a89abe84509.nq.gz
│   ├── 5a46d3985c61fa1beb93769f99904d72c9984788.nq.gz
│   ├── 5cbeb2376ab337d5dacde60f501b6ece36c36880.nq.gz
│   ├── 5ee5b691049ec73bc9a132b5519df631d5eaad6f.nq.gz
│   ├── 6007aaabe2c6446ad69add11322ea97fe88b33b4.nq.gz
│   ├── 63021b1e4b8c1cc4fea79d4843490b0739b53011.nq.gz
│   ├── 65848caddc9a2b9329f38dcc95213a35b4a2ff5d.nq.gz
│   ├── 67e102cd5145cab86e853a706b33b5e3e071a48b.nq.gz
│   ├── 69284810eb8f7d1e141e14bd1e5c8bbcea356db4.nq.gz
│   ├── 733b0ef97a890c0a24c43132bdaa3595068f67a6.nq.gz
│   ├── 740c90237216a2c323cd86dc5e6d2312605129c2.nq.gz
│   ├── 747f1bbb98c948253e4a6817b879d2fb19837732.nq.gz
│   ├── 74fbfcb20686a0148565e752dae422b2b4a53f7b.nq.gz
│   ├── 791a1b3fc00849e5f13079b434e75e48c88a9909.nq.gz
│   ├── 8085c2cb3b9ce70d57e18c3af20012caf606a61f.nq.gz
│   ├── 86b77b06e7ca63041dfb2fd55b3095689aebee07.nq.gz
│   ├── 8789d20fd0ef02b1a6aa69dd1b7c1d2ef8c92156.nq.gz
│   ├── 884f90c44dd8f90af05a9e05c08ea6a9e4baed95.nq.gz
│   ├── 8a1596d341298ca779e85fa4289328eadc4a6888.nq.gz
│   ├── 8b7c7e7247a98cedc37686b7ab98abf04e7c3f4a.nq.gz
│   ├── 8ba3e7355c9b468bc329b32ea101b0ab0ff9f4c7.nq.gz
│   ├── 8ba3fd36bcf038a2daf69c3faccc4e437ca3d530.nq.gz
│   ├── 92113ea622e846e8c2a3acf499e1fb94f437a409.nq.gz
│   ├── 97506450ef93bece4b73877c0f1b8c85b5b7bb26.nq.gz
│   ├── 9a101de91f51b75464077a0e14ffba716204dc3b.nq.gz
│   ├── 9c7909480f06b84412584fd69a5a3fb19ae96be5.nq.gz
│   ├── 9cc4dbabe660f4a0d24f027e8705fdc327a33b41.nq.gz
│   ├── 9f27e109c866fac1f3fe1044f514ccd09dcd7e41.nq.gz
│   ├── a4a2eddfb0164ea600eba241d80b820806eb04fa.nq.gz
│   ├── a68d29a76e7492cbbb930e284fc0625914ab904e.nq.gz
│   ├── aba00e3cabb48ab46185d9d0717c71d249360ca8.nq.gz
│   ├── ae60998e9ab949a83e2dfb1bcc97177a1d4c296a.nq.gz
│   ├── aea6eb5e76890f66ed345395ca40ccafc52c3b96.nq.gz
│   ├── af8c3eff14210e60b2c30631a39a1f2984235cb3.nq.gz
│   ├── b20ca0fc55dd3d1f35bc66e279642435c55de55b.nq.gz
│   ├── b215a7d4cb03ddd6246957e53e27d9122d06e006.nq.gz
│   ├── b498fd495d6c8b5f1448de6e0c6526b0e91efa55.nq.gz
│   ├── b6688dc2a459d3ca0c4b4ba8aafd9fc8707b5b16.nq.gz
│   ├── b76f4c3da1f13f598f4ba4b112458fd91796087a.nq.gz
│   ├── b7c2181aa0e0b1cbc338202df7038e3ab3d44c02.nq.gz
│   ├── bb07c2b1e5e3195c1b677134eb0ac4a8129302f1.nq.gz
│   ├── bd1c3076eec2e7389c80bdcae1876b80f685c809.nq.gz
│   ├── bf6be479b6a9460bb7f0711463cb560192e03a47.nq.gz
│   ├── bf74e2c5ad34e8b6b2a8cfcbf4de62229ee3654d.nq.gz
│   ├── c0b2e88a342b859178f124b184b010fbafd4d5ff.nq.gz
│   ├── c0d1d9c4d177a80cc88ddee6b03f028ae6ca109f.nq.gz
│   ├── c30b88242ff6e9dbd81d9a279f40741a527e56f9.nq.gz
│   ├── c5cf4967b756f4478d38db02806d225a5c435d78.nq.gz
│   ├── c5d6676734a731bd28f6565be07c1f3c353ccb88.nq.gz
│   ├── cca1c81d677a2f55532ee01a48c0634f654c18f5.nq.gz
│   ├── ce260d0d2728a455d7f369061fa9c4b7ce89b226.nq.gz
│   ├── d011290f1a5f41981d259cdcdf39ea9bf03c3e08.nq.gz
│   ├── d54bf263ba8908aa5d48f4d2ca3dc2290a0865db.nq.gz
│   ├── d572d909d527ddfe8219755457ab145c45be16f7.nq.gz
│   ├── d78aafa5399eb7840996521788de1f1629853e3e.nq.gz
│   ├── d82086c80e71030872ea5598f93bfa3b37e439e7.nq.gz
│   ├── d823972abcb7ff6ac0df52a8b55ff51ce1b5f09c.nq.gz
│   ├── daeee883c95adc3596314e81e36b2ba64163b3eb.nq.gz
│   ├── dcf8d2051d39e18ab281b48f9c50a05a6299a69b.nq.gz
│   ├── e1bfd93791f37271f4cba48bc8a3765185b9920f.nq.gz
│   ├── e339d89c69280d35639e962045fffb22f0e36732.nq.gz
│   ├── e364a9c8df1e7be5cb417cfe5c1bfee1776cc19a.nq.gz
│   ├── e40f92771a792b5c29d2f36665409ca2f4f712d5.nq.gz
│   ├── e454a52586f29b8ce8a6799163eac1f875e9ac01.nq.gz
│   ├── e4a3cae581d503f610a6e600260bec8e9e7f4c6f.nq.gz
│   ├── e8a3a31c36b6181c63ca55b43ca12f44aa0feb98.nq.gz
│   ├── e8a5aefd442afb83d103c30e22cb00a207d3d87a.nq.gz
│   ├── e9a59fdc6066f2c1eb88de09c051266c363351aa.nq.gz
│   ├── ea67bad1b817e036b936f3866e5015cac6a338ac.nq.gz
│   ├── ea88e4f9168676c3d3cb013590086135bd284a10.nq.gz
│   ├── ebdcfa91fc6df396e6bf5aff8f9b6fec9ef1271a.nq.gz
│   ├── ec41c3242fafe5cbec617bc55dedc52ef76ef509.nq.gz
│   ├── eca2cd9709fa6b48b45a56d631f063573ca05fa3.nq.gz
│   ├── eec8c23ee0562436f7d101a26a912965bc6cab31.nq.gz
│   ├── f03225418ba1fd6b5e1f81410e360d6ec36560c4.nq.gz
│   ├── f64abecb40c71197197991602e8f9506f32a2711.nq.gz
│   ├── f806159c2f7cf7ce09c65afe2f57bc06cfb51f61.nq.gz
│   ├── f947210bdae319265676bdab78439858918164a8.nq.gz
│   ├── fad3b511fb2c8ee83d4d6b8b18a10b8562d3fa46.nq.gz
│   ├── fc5e0bec787662421047f05123aeca07bc4af420.nq.gz
│   ├── fe21e02e30c28078eda7264eba34aa45c1666788.nq.gz
│   └── ff118159c37a8eaf4c2cdcf8874c45d2cf48edc7.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 019a4adfbfa913e6307cdc5a589089e95cfb6285.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 132 files
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

[twitter-archive/iago](https://github.com/twitter-archive/iago)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
