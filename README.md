# Repolex Knowledge Graph of canonical/hockeypuck-k8s-operator

RDF knowledge graph data for [canonical/hockeypuck-k8s-operator](https://github.com/canonical/hockeypuck-k8s-operator), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/hockeypuck-k8s-operator
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── dba7df50ed0ba3b107bb0fbb16197fade03b8d0d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── dba7df50ed0ba3b107bb0fbb16197fade03b8d0d
│           └── chunk-001.nq.gz
├── blob
│   ├── 00b1348acebaa3d4141adb226ca166f74eec5e77.nq.gz
│   ├── 05bc8ccab38d8b422aa47c92d93626cf1896e6db.nq.gz
│   ├── 0b17293d8a881e12fcb4a75c4a39f1a8e991adc0.nq.gz
│   ├── 19576945f484d080836ef39ff9ff29ee45a1a740.nq.gz
│   ├── 1ca663b152a21d19ae2f47adf2685731a3a074c3.nq.gz
│   ├── 23ff3d7df60f2228820b1973032ca62aa7b707e0.nq.gz
│   ├── 2674db1ff8634283e3b39b1841c9fae4fe8fadb3.nq.gz
│   ├── 26ac226df88c6bc3785214f437d30606702a7736.nq.gz
│   ├── 28b808c88154e25c9bd10ea556f7a373dddeff53.nq.gz
│   ├── 299395136bd92a0000b94f4688d021d993763979.nq.gz
│   ├── 2a220ee7476c9461cec28e8ac45da83fd9ce82e7.nq.gz
│   ├── 2b815caa715f4c3ea524c575e19392244f21784b.nq.gz
│   ├── 2ba2d8b512a148eb1bb3118769d25c15a15f67fa.nq.gz
│   ├── 3090862409ff609aead826d3e561892560efece8.nq.gz
│   ├── 3372cdf832ee05e9662c2b38bd09673703f18820.nq.gz
│   ├── 37955f6e62dab9b51707631f93eb72f3b327418b.nq.gz
│   ├── 3ceff84eb8395fe31398e57b1ec19edb27de467d.nq.gz
│   ├── 3fc8d9fd2699f4d0296e827ea48e41d66e7d0a8c.nq.gz
│   ├── 41796523f6f8c84c9b39eee18a1f6eb5c456756a.nq.gz
│   ├── 425a4313d8554bfeff443b8d00416586c9cfb5fd.nq.gz
│   ├── 451487e5b9854a660fc5fe76fa0f5e52a29b2397.nq.gz
│   ├── 484e6266657ecadba5d364822058029d90196423.nq.gz
│   ├── 4a5363d4af5bbb3bb2b63c9c5dbfaf98b33b8cfb.nq.gz
│   ├── 4b1f6fba5f977983181a3ea0ef63312a299550ed.nq.gz
│   ├── 4b8b005b4221683de826805b12bff5b94c2d0264.nq.gz
│   ├── 4d615dad8be6d52054222689c377cc4a5d764145.nq.gz
│   ├── 51c3a380f5aa6f43d6b466a713597367c8da6d37.nq.gz
│   ├── 532d77c956de659e8bfd7ff28458eb901586d9e0.nq.gz
│   ├── 55969d643048afbcfabdfa8a3314e271294fff2f.nq.gz
│   ├── 5b0d5c1534448be3d207461c32f54506c9a20699.nq.gz
│   ├── 5b8a9ed6586b2d331aea2dbd398cb33d1e797ed8.nq.gz
│   ├── 5e7dec278cc49f31853d5c49bd898a155bf26f9b.nq.gz
│   ├── 64034644ca5133b72769d8aebf127b61d16ffe32.nq.gz
│   ├── 66a02f06c1a6c88ade98f5832047f1fca4a1d786.nq.gz
│   ├── 6879e8e0fdc08418d43b4555f45622d5754711e1.nq.gz
│   ├── 689362fd4638c73dc1e6888c56eb01ebe7d849fa.nq.gz
│   ├── 6d910a6a1f8fcc51d83cbb89ed031ad0db2bee33.nq.gz
│   ├── 6f94cded4fec60283aa42d48789f2f779e32bb9a.nq.gz
│   ├── 7150d8d17d00facd49c4588e1438a4e002764a96.nq.gz
│   ├── 719a18b96b5e7e43a1249501af15ec0037fb4281.nq.gz
│   ├── 72602ccf127ad496695537859825405c6c80c6f1.nq.gz
│   ├── 746511ae0e0f622d464165d07adf3a1fd8fab1d8.nq.gz
│   ├── 768452f2d5878505d26cc2a9d17effe326ca3738.nq.gz
│   ├── 796af49cacd8489a3b79be969f4487558ca44335.nq.gz
│   ├── 7a275ff70d7c31d56b5975b539c5d4b45b7e746b.nq.gz
│   ├── 7be90cb98b729be6da076436ffa6c646b9ff1971.nq.gz
│   ├── 8012bee3e1b1f0119bd77ca68238fda930f77d3e.nq.gz
│   ├── 80bb14749d79f1c0cd444852accbb17553cf924f.nq.gz
│   ├── 89264becb7fdcc03229951bc39de33cac3d69c1a.nq.gz
│   ├── 8ab7f285e27e818741f688c454c3fada4f29649d.nq.gz
│   ├── 8fd0d23ed045eac23dd08e82b7ea0e7a756c0f2c.nq.gz
│   ├── 914876b7a65ef605ec17d06c1fbe128adb22fa50.nq.gz
│   ├── 91be23e1d251c11b057f1a83ce03e663b6a4f61c.nq.gz
│   ├── 9277ab07126bf399ff27a0e20229ef60b8a9cec5.nq.gz
│   ├── 95f34072e4cf06fcf8c209c1342fd93d9ec47d30.nq.gz
│   ├── 973c169554e2647fa4450476b06470d4c0ae35a4.nq.gz
│   ├── 98a3b4995b145ab3e3f18a548947eee6618573d7.nq.gz
│   ├── 9ebb19162b10275e0c41594168237fc8ebdc60c3.nq.gz
│   ├── a1ab4396ec346189b907be3d21193e77e327a66c.nq.gz
│   ├── a66ea292faff539d6f05833db1ed277f76d2445b.nq.gz
│   ├── ab590921632f78ab7947d81c2cbf18a0367836c7.nq.gz
│   ├── ac503be223330fc3036dd797c308c28b6c682210.nq.gz
│   ├── ad60b546623c02340f4e7eb19bf83031a47b2ea1.nq.gz
│   ├── addf81f56cdb6858a00debf4f49b0676b2605629.nq.gz
│   ├── b845a37f5520e5747ea34a81bfc3669bf7b62266.nq.gz
│   ├── baaa1c1de60592d0a662baca06d2a276cd59d307.nq.gz
│   ├── c1cfb9f327e92af443d4c564e4f57bf9798ea4bf.nq.gz
│   ├── c3c4227739d07e108454368ceb6348a99a70ade8.nq.gz
│   ├── c54cfed20626946e9cd1b45630a17e0508f39b39.nq.gz
│   ├── c895d699692601fab2751d257451d7b51a5df0eb.nq.gz
│   ├── c8fa18574352e36aff2f88ae691ce4a70dd63b9d.nq.gz
│   ├── cb3779000b4f7267d244fcb0b7dd7e3b510664a7.nq.gz
│   ├── cbafb97811981a4803b5ddf812ced876be7850a8.nq.gz
│   ├── cd7c4c66eaa2e9de93723c9cb7d5b1a131ad17de.nq.gz
│   ├── d090eb41b81c966a03234d48d18b2bb72c5eed6b.nq.gz
│   ├── d548f13436f052ab10b74d823481cdbca2a01306.nq.gz
│   ├── d5eff4d0754cc78625d537ebf0aaa4f757ca11f2.nq.gz
│   ├── da1e2049eb420c5e26c46849af0ee747a58fabcb.nq.gz
│   ├── dbf4d5bb721e2c91fc81ad9e7bc352896740ad17.nq.gz
│   ├── dddb292a2c1698851f1fe7d4eae27a5c284b55e2.nq.gz
│   ├── de6e0dbfaf18615b8930d706251660b56f9fd902.nq.gz
│   ├── dea8064a82c4d6258a912f78818217bf0160d468.nq.gz
│   ├── df541556b4c8b8d1d2040a3acdf1aa8872e9c1a7.nq.gz
│   ├── e04400036c903eefe82da7a93f679f13f37bc75c.nq.gz
│   ├── e06d4c9f5ea64e2106020f584640369f54313f0f.nq.gz
│   ├── e2cb3cbe61d9f80bb630f9261f2d60e1047dde09.nq.gz
│   ├── e44ecd9e18bea79b9e6718901827a96a3a949fca.nq.gz
│   ├── e5472c1e1d800876c575abc592ad611dbea50bb7.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e84d7a1459134d71e9b08bd5b778b21f99e2b2ab.nq.gz
│   ├── e8872fbc3cbccd7b310f0cc5223a8e139d5afd40.nq.gz
│   ├── f32ca5d29ed641f2469590d819196c07e10b04fa.nq.gz
│   ├── f35143eb2ace2ec8c395b78e06459ca40e03caad.nq.gz
│   ├── f373ddade5df4d5f1e8403baeeb3b650af5277f7.nq.gz
│   ├── f41e62d33a735416cb51a48dcc46cb0af6101d9e.nq.gz
│   ├── f4a65fdd7c0714cb6e6d8696295f9c0110a5e870.nq.gz
│   ├── f4e30c56a97efe41bb7baa39ac822b3e4b4d694c.nq.gz
│   ├── f93b8632edcddcb5e23f05b83117b0b4d9d3e924.nq.gz
│   ├── fbc71d9c47e4ab3f1dae49583e1d26bf8ea7f5ea.nq.gz
│   ├── fd0d3c687feb8c92cb28e9ff0ba71bc3648dfedb.nq.gz
│   └── fe6468e8d0a1957aba024423c38b9eac57f996f6.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── dba7df50ed0ba3b107bb0fbb16197fade03b8d0d.nq.gz
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

[canonical/hockeypuck-k8s-operator](https://github.com/canonical/hockeypuck-k8s-operator)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
