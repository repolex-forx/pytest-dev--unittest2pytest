# Repolex Knowledge Graph of pytest-dev/unittest2pytest

RDF knowledge graph data for [pytest-dev/unittest2pytest](https://github.com/pytest-dev/unittest2pytest), parsed by [repolex](https://repolex.ai).

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
rlex download pytest-dev/unittest2pytest
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 53a3a774751303e3bd8df70eb22788ca7c79e2a8
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 53a3a774751303e3bd8df70eb22788ca7c79e2a8
│           └── chunk-001.nq.gz
├── blob
│   ├── 015887ff977a529ee51d4388427546ee98724bab.nq.gz
│   ├── 019c79322f9de9d39baa5df67e81d8f8b99845b4.nq.gz
│   ├── 05685a68518d2ca068150406f55d60aa06bd2e18.nq.gz
│   ├── 07e7f511f6c7862f583fa9633b0d338752f2e080.nq.gz
│   ├── 0f3ac5da57d094983c6bc31e5d34745b283de4eb.nq.gz
│   ├── 1678fb8838b75c4f391db4a53cda2bb494aa15a3.nq.gz
│   ├── 17c43b5907a1774ba8fad3d696bf17976796e650.nq.gz
│   ├── 1ac04f5b2fc4da7d9ccb29331d99a0bc0f4a2b31.nq.gz
│   ├── 1dc4475785fd0241e279c3a57df14884dd7e37a4.nq.gz
│   ├── 22239044c39359cd366b91582282c5cdac3c0e17.nq.gz
│   ├── 22e45fb8192bf3bb3f250f0d204670813bcf40fc.nq.gz
│   ├── 25d7cbaf4ec0a999953d4beb85c9d418d1ddedd7.nq.gz
│   ├── 2826b7966fab3722112be76c9a68ffd3448194e8.nq.gz
│   ├── 290e3bd9746ee3a99462ad492684d61cf8f4533f.nq.gz
│   ├── 30467b84a26261c691639bb808acc9491cd8d334.nq.gz
│   ├── 30bacbb1b729c064c502894ba40707d5d04155c3.nq.gz
│   ├── 320c62ff163cf1ef4c3e61c8dd2745af76188786.nq.gz
│   ├── 328ac0d68db181a1987377095db453f63f27d453.nq.gz
│   ├── 36d7e57cbcd6b76e2e42485bdf28d48c8ad8c7bc.nq.gz
│   ├── 3971317498e718f5a3e7c7e28fca9f3971e12b52.nq.gz
│   ├── 3b127a772aca4a99e7e992cf25b4cced56e4ac69.nq.gz
│   ├── 3e090ff141d1832cc1b45159f81cc984f508bb5e.nq.gz
│   ├── 43cf3f7ec34ed0fa0bda555f14969cc6de7b1127.nq.gz
│   ├── 448bff073d556a21b8b8112f784890b99e87503b.nq.gz
│   ├── 448ddf650b3903de48dcbc1114d03e52ae071bf9.nq.gz
│   ├── 47a96beddbd9463d376f9e982f05bcd56f7eba73.nq.gz
│   ├── 487cad383c63e24f75206b0c17f20064d98134ec.nq.gz
│   ├── 4cc752c8d4e000d7675aae916f7bcab40872ce23.nq.gz
│   ├── 509f30288e45493d73ff7fcfc7f52c9d8df61554.nq.gz
│   ├── 513bcad2912f4db3065feed16ff7dba60606a7c9.nq.gz
│   ├── 51b4419088477408b31c7a17d5d27fc0a864bf10.nq.gz
│   ├── 5294606f3c58b90a9d7edea83249ead25d8b9b5c.nq.gz
│   ├── 52d3be60b677796341c3a65e1ef5ba02a1598129.nq.gz
│   ├── 582f442d729ac1894784438a598a907a1330993f.nq.gz
│   ├── 58e904a839dc61f8d0efbed376aec56338a618ec.nq.gz
│   ├── 59c7df14ecefb29dc0b2d55815f2ea8f82c503c3.nq.gz
│   ├── 5bd3ff48f07f389a1abdeba42fd515e457ab83b3.nq.gz
│   ├── 5c5190c9feb9e97311b6dbe1a7202995e13b4e23.nq.gz
│   ├── 6a5681dfc8a5e6d2bda8d19eca87066f7c274828.nq.gz
│   ├── 6ae47a544b73abb7b95dd74c2978a33b0ded82f8.nq.gz
│   ├── 72aef32bdd8710248f48bd8a0686f403b84fed59.nq.gz
│   ├── 753d58a60f1888252cd0facbf0f5197faf7ed530.nq.gz
│   ├── 76954b91b562d8125548d8a30d687edb575f015c.nq.gz
│   ├── 792d6005489ebee62cde02066f19c5521e620451.nq.gz
│   ├── 80c741e502a16d0baff5e25c3fa38f326c66ae6e.nq.gz
│   ├── 80d6b7d3f3e261b3dc92a41a0aa01315eae29592.nq.gz
│   ├── 820848dcef0e4cbfec1c7a22811d3c744d17735a.nq.gz
│   ├── 833d980f281b14ade7b1993783d6c45be7517828.nq.gz
│   ├── 845aa747861277d77da9e7aacf7e73071e95b9e1.nq.gz
│   ├── 8c726337b9f3230ea34403ccee4f899f55de3118.nq.gz
│   ├── 8db1823562520313551edfb5cca85866b25e369d.nq.gz
│   ├── 9142c861c34a35f3b6b6a495e77698b241f3a239.nq.gz
│   ├── 92190295fff37c9a7b122b5de8bcd87d44ce1de3.nq.gz
│   ├── 944fbdba46aeb0ce5f5a79c66da1a3a98d64e160.nq.gz
│   ├── 94a9ed024d3859793618152ea559a168bbcbb5e2.nq.gz
│   ├── 96166b9abbecab09f4a179ab3085e25fdea40012.nq.gz
│   ├── 9926b83d76dd9b9c6ddd165108991d635e2c384d.nq.gz
│   ├── 9c658f81b91c477ec8c69efa5f7dc9239395acee.nq.gz
│   ├── 9f29b17a540e2667f044c40bf3925cab784b3e48.nq.gz
│   ├── a18e24bdf9e9f941995cdc4ff6c49e20fd0b0402.nq.gz
│   ├── a2bee47ade4651e2be48168a3baeb0097ca36807.nq.gz
│   ├── a2f231da913067270c6606792a95e630df812700.nq.gz
│   ├── a358632cab98a78c9d9b1ea4b5348e3a3be8c6d4.nq.gz
│   ├── a3a79cb07459a136e2d3705132d52c12430adf8f.nq.gz
│   ├── a84867bdf67e054d85d4a0ec05f6cc300b41f9d6.nq.gz
│   ├── aac2c6b3c99f994e0841b056eecd03b6aaf236c9.nq.gz
│   ├── ac25665823565da408479d0c8070282bdd341bdd.nq.gz
│   ├── b01a649bece8b1b38ff17a49b303b6cfcb80812f.nq.gz
│   ├── b1d54ce532f7d7d41e8fc2d2ad9cbf5d4d367c8d.nq.gz
│   ├── bb0ee0e570612915d4bc08c6aad3b83fd324aeff.nq.gz
│   ├── bcc58617b67f921156fb72c6e9aafb9d6c48d725.nq.gz
│   ├── c15e5b359b238beec06ddd1e9c6cfb8b697ec9a0.nq.gz
│   ├── c1975443d07c31b1f6c8206d73f933da85b925e8.nq.gz
│   ├── c486d6dc47a48ffba24842f59c3be7cd5fc2172c.nq.gz
│   ├── c4e82fa46bfddb38b759b4020b4d92bf27fb8984.nq.gz
│   ├── c4e8cc13f212cdc1f264928113b09051f1462b0f.nq.gz
│   ├── d524d9446010cafa99d20d1b09a9d3f0abbea1f6.nq.gz
│   ├── d5505e151f4e67e2cf0c777a9fa0c6da638daed5.nq.gz
│   ├── d6948ef114d73a16a93820f9a6ac95d7ccae65bc.nq.gz
│   ├── d8c3103f39a97a6fb4941166504fe70ac08ca680.nq.gz
│   ├── d960b6461aecbae3f3718f35d80c5fd0aabc7b48.nq.gz
│   ├── e4c9992b451d075b51a89c8c141801fd6dcaeedd.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e823c2699ca738b5dac144af36deb10ee318e968.nq.gz
│   ├── eaace0ec1943156de0709d20644b2c38ecdf434b.nq.gz
│   ├── eaf9c2599eed13418902bd684f7adc4aed0ef0a6.nq.gz
│   ├── eca7be707ac15483721e70cfbb3139af4666f8f5.nq.gz
│   ├── ed277e750c64555e7a818b1de551e2ea576c3e5a.nq.gz
│   ├── eea8ef5afb622c27f14dd13a7d2ef4fe33082bcf.nq.gz
│   ├── f2d641881b8b3afcc0878f5016763b6726d8522a.nq.gz
│   ├── f8f3389f1258d7810e48e76b98ec3ecaf1cf50bf.nq.gz
│   ├── f8f6879afc71a8ecfa8b719668cc79b658ace169.nq.gz
│   ├── fb60301d2c6bbd7a107198a61aec639fe30a7779.nq.gz
│   ├── fe31234931295d991209824e2760fc9ee494038b.nq.gz
│   └── fef8a978281eb9b9abc7e89b946deee57759e55c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 53a3a774751303e3bd8df70eb22788ca7c79e2a8.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 103 files
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

[pytest-dev/unittest2pytest](https://github.com/pytest-dev/unittest2pytest)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
