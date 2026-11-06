# Repolex Knowledge Graph of zopefoundation/zope.publisher

RDF knowledge graph data for [zopefoundation/zope.publisher](https://github.com/zopefoundation/zope.publisher), parsed by [repolex](https://repolex.ai).

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
rlex download zopefoundation/zope.publisher
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0938c82334383783f7600d39f90d5de50ccd0754
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 0938c82334383783f7600d39f90d5de50ccd0754
│           └── chunk-001.nq.gz
├── blob
│   ├── 06d29765b868973bf9b245f9b8490ae61ee610e3.nq.gz
│   ├── 09ce2c449c7df4828387d95f423b99e25d3ebba1.nq.gz
│   ├── 0afad7ed6a81aa249fcb954460d2cd1c9e7f870f.nq.gz
│   ├── 0eebe1304bbb2cb9153dd4a46b8e0a8004fdfed5.nq.gz
│   ├── 115598d6ba9f1cf9eec95bd1b96e18ee6ea936b5.nq.gz
│   ├── 122616f73f1e6be33d1b9171933f917103e86ecc.nq.gz
│   ├── 1445aa1fc279cd981f3ff2203890870f95862db0.nq.gz
│   ├── 153611f487e609423b74c4d0a3b4ce51e6e68a9f.nq.gz
│   ├── 169b8e5abc71446b6c06c853d9db1d875c0fae0c.nq.gz
│   ├── 17edf74f24dcc630c0a56271575523c72f758270.nq.gz
│   ├── 188cd9db401238265fb6b6da9b82374e45611823.nq.gz
│   ├── 2630f893414413f8840ecc0db47a58b8dc4b3779.nq.gz
│   ├── 2846ffabeddee112212836032180c8b6102acd52.nq.gz
│   ├── 28ee315d3fbde2b9efef43db2fe793c2b5290182.nq.gz
│   ├── 2beab406058a0dc5b821674b4b50506e7ec6b2ed.nq.gz
│   ├── 2c9fd0a4361b61590978c9eab788be927475e5d4.nq.gz
│   ├── 2cd7e9f2bc9dfe822c7ce2c2199fe85926c745c1.nq.gz
│   ├── 347cc52048f725ac9d1075fae5b21d73c4096adb.nq.gz
│   ├── 4365c5e21df8bfa6af725bcf0a357b2a379f9e48.nq.gz
│   ├── 43955ad71c0d386169ece3066cfe92e6b59ab523.nq.gz
│   ├── 49ff65280c2bb6d235636536385f408e1cfc9fed.nq.gz
│   ├── 5363f161a2a404f263e6cb02e415f01cb3c1399f.nq.gz
│   ├── 5892fdc91f5a2b08cdb1b68e2b0e3f07df2698bf.nq.gz
│   ├── 59d96c8b40cb0f836d3f2d37f873d9539e76de28.nq.gz
│   ├── 5e43b65efedd4d6f4f2300e5f0adf8bacf0aab42.nq.gz
│   ├── 5fbdb9686a65a863ba1b4cd3e1a198b787c200cc.nq.gz
│   ├── 6208a703250d90982e5cb95ceb9512afa6462b78.nq.gz
│   ├── 6f4f65daefd8479529db13b566ce9cc8021ea5b1.nq.gz
│   ├── 70647f18c343e2af42840b479ec77aa97a27a0cf.nq.gz
│   ├── 736aa7308671ab80b8953fc44a522ce1d834bd54.nq.gz
│   ├── 75649814859e3debbb992db36e48ee22583d25ad.nq.gz
│   ├── 7765ffae084e73ee40c840d64d9e90dd9700416e.nq.gz
│   ├── 7769623fc9cd16e98d7c58bf05352f56d6a20fc9.nq.gz
│   ├── 7dbf5b7c8a196618a83563707247ef1a48b791c4.nq.gz
│   ├── 7e309394204cdbd2da3ac749f1d7921d2dcf8af3.nq.gz
│   ├── 7f2d0fa03862d73f89b5303494fba9e9bc2e65e1.nq.gz
│   ├── 827302166885cdbe55eebbadc631139995166b7e.nq.gz
│   ├── 83fa95aa8b5db8263fc2d8e23e99372a370a97a8.nq.gz
│   ├── 8606c4ecfb3fb6074861439d41930dc670cf7cf1.nq.gz
│   ├── 862662e191901ad1f3c00bcba54ad177ede12ff1.nq.gz
│   ├── 90eb3c84e9d10bc3cf455ed2fd252df39cddd807.nq.gz
│   ├── 93642823637ff0b9de431d60db533a05a5ff3c79.nq.gz
│   ├── 94f3501fc61a0d9dc53bcc85f15dd40392b5cdd4.nq.gz
│   ├── 9a8e8a264baece5e05dc44b929543ffcc201940b.nq.gz
│   ├── 9ae8f4dbceabeed6c04b72d800c8f3b2c546275a.nq.gz
│   ├── a1b9cfffe21b981ad550fbe3acf349690274d6bb.nq.gz
│   ├── a5f962e7171ff3571e110f0a56cbec16065d72fa.nq.gz
│   ├── a70575bf5153a4623c02d8411588a46a0054a183.nq.gz
│   ├── a7369483c6fdaf5ca08bf041dd190db7c62fa661.nq.gz
│   ├── ad56ae92ed2bfd33dbd3b5d8032196c2a5a7a0e0.nq.gz
│   ├── aebdffdffb79f73ee5827c90c8c089e54d9975de.nq.gz
│   ├── b44c7f73084e2574f696e5fd4f9aa96746a0a883.nq.gz
│   ├── b711d3609fdefd7664f2982d225d96f5e53be9c0.nq.gz
│   ├── b8581dd898cbb33e63961b4d181ff0ffbe5d03ee.nq.gz
│   ├── ba7c1ab1fe2d7560ca01d43c9f37a85bd46f2247.nq.gz
│   ├── bfb245b7c46fde33843b9ba29a1aec30e8908a56.nq.gz
│   ├── bfbdd6f004444731106be901f57c17865c046cf2.nq.gz
│   ├── ca517f4eb0cec1c691c0c2b54cd5eb85e906f11b.nq.gz
│   ├── cb975436fb482786fe1023bd3720ccdae2ee68b8.nq.gz
│   ├── ce78cb9c0ac065fe0e7cbd6b5be0cea1f8d1e4a7.nq.gz
│   ├── d03595ed727ec2a4ee25003f2628e50543b611e4.nq.gz
│   ├── d2031110ddcdd734572a7c0b403664984402f54b.nq.gz
│   ├── d22352dabd89769555d44540a690f59ba3d6bda5.nq.gz
│   ├── d5b2b218fda4ea80520c5712b702ed6ba691d815.nq.gz
│   ├── d73771c91caa10ee44983f309eefc07f4bb1b246.nq.gz
│   ├── d7b06e5f6c9469ed4c04e6c189356f20940d9afc.nq.gz
│   ├── d9a1005de525a99d7149ae38092c76b0d36dcff3.nq.gz
│   ├── d9e113ec685b92b018297dd2f200341d1fba01f9.nq.gz
│   ├── dbac3f0e219ec4e03367611c555f9e722b6a0814.nq.gz
│   ├── e184fd8f41cbc229060cf69967d916bf6e2ddf2a.nq.gz
│   ├── e1f9ad7b3b48377bfbfaa1b380c384ddea24060f.nq.gz
│   ├── e4b867329e05886a4818f86b117fca2102bc84bf.nq.gz
│   ├── e54195aa6afe78a9473f34bb4f558ed8ae660821.nq.gz
│   ├── e556b6779bd5c94d7d78348b226cb3631deef729.nq.gz
│   ├── e5dbb3c6397003f1f52bc10e8baafe699e50e6ff.nq.gz
│   ├── e75f35cf541a6e8502e5df7b2f1529963958660f.nq.gz
│   ├── e992a3e36f8059a9f1e640c6cfb9c66a9c004793.nq.gz
│   ├── ec5c5a08fd3f45f8a498a78649cc9f4cf857aff1.nq.gz
│   ├── ecf0ca62c4442a2b7a79d1849b209a2cc9b2f3b5.nq.gz
│   ├── efe42c15e74e492592cbeb7d370226a789a1bfdd.nq.gz
│   ├── f06fdccb1e36d4be3518bcb73d3813d84b2fe0bf.nq.gz
│   ├── f507feda73c43de02c9268ef502bc4c3a2ebf32d.nq.gz
│   ├── f6cd60b80b618af1df984960f8763b7e5622eed8.nq.gz
│   ├── f81cabf053fb4487bb3496afbc276556076bc3f2.nq.gz
│   ├── f8ed54d158570c5d011b57c4c19b24180a00bca5.nq.gz
│   ├── fb2b20d8e96590e3a657eefab80b2db8951d8105.nq.gz
│   └── fe143546d60344be882e96fb29cdf5f9d38558f5.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 0938c82334383783f7600d39f90d5de50ccd0754.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 95 files
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

[zopefoundation/zope.publisher](https://github.com/zopefoundation/zope.publisher)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
