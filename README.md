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
│   │   ├── 0938c82334383783f7600d39f90d5de50ccd0754
│   │   │   └── chunk-001.nq.gz
│   │   └── ad4fcb0478e98c57b7eaeb8463f13a22c0ba2c65
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── ad4fcb0478e98c57b7eaeb8463f13a22c0ba2c65.nq.gz
│   └── repolex
│       ├── 0938c82334383783f7600d39f90d5de50ccd0754
│       │   └── chunk-001.nq.gz
│       └── ad4fcb0478e98c57b7eaeb8463f13a22c0ba2c65
│           └── chunk-001.nq.gz
├── blob
│   ├── 0164467585f21d8946d35e8743535cdb3f3b21bb.nq.gz
│   ├── 02f0338f77ad0def38e74c4cd8c28a04ced3b547.nq.gz
│   ├── 06d29765b868973bf9b245f9b8490ae61ee610e3.nq.gz
│   ├── 090b2fd23b0607aeb95f958f6be4dfe5bc090740.nq.gz
│   ├── 09ce2c449c7df4828387d95f423b99e25d3ebba1.nq.gz
│   ├── 0a5cd1e9db1c321b75fa20b3ffa7125e986f499c.nq.gz
│   ├── 0afad7ed6a81aa249fcb954460d2cd1c9e7f870f.nq.gz
│   ├── 0e15cd5f684f46eb6f812ed00ca050b3610043fb.nq.gz
│   ├── 0eebe1304bbb2cb9153dd4a46b8e0a8004fdfed5.nq.gz
│   ├── 115598d6ba9f1cf9eec95bd1b96e18ee6ea936b5.nq.gz
│   ├── 122616f73f1e6be33d1b9171933f917103e86ecc.nq.gz
│   ├── 1445aa1fc279cd981f3ff2203890870f95862db0.nq.gz
│   ├── 153611f487e609423b74c4d0a3b4ce51e6e68a9f.nq.gz
│   ├── 169b8e5abc71446b6c06c853d9db1d875c0fae0c.nq.gz
│   ├── 1734acb66ed46e84bfa4c8cbdcfbbc36c3565db4.nq.gz
│   ├── 17edf74f24dcc630c0a56271575523c72f758270.nq.gz
│   ├── 188cd9db401238265fb6b6da9b82374e45611823.nq.gz
│   ├── 1c45117c10d7acb3b1da540018f8758b1aed5f3f.nq.gz
│   ├── 1d93e6c69501518dddf71a086f4368bb8e8b7161.nq.gz
│   ├── 21c8a79e789c198d07796a2e3659197f497f9514.nq.gz
│   ├── 25a9fb36658fbf0775c8787bc812d3a802c44b11.nq.gz
│   ├── 2630f893414413f8840ecc0db47a58b8dc4b3779.nq.gz
│   ├── 2846ffabeddee112212836032180c8b6102acd52.nq.gz
│   ├── 28ee315d3fbde2b9efef43db2fe793c2b5290182.nq.gz
│   ├── 2bc1e0eddb57736aec3e806febd881ca666fbdfb.nq.gz
│   ├── 2beab406058a0dc5b821674b4b50506e7ec6b2ed.nq.gz
│   ├── 2c9fd0a4361b61590978c9eab788be927475e5d4.nq.gz
│   ├── 2cd7e9f2bc9dfe822c7ce2c2199fe85926c745c1.nq.gz
│   ├── 347cc52048f725ac9d1075fae5b21d73c4096adb.nq.gz
│   ├── 34a519bc2d893a725035229e865d17088829913a.nq.gz
│   ├── 40a5f6d86d9145704810f07d4fa0567d33b60abd.nq.gz
│   ├── 413a1c41038e5ed5323bf0b4b59a401b3f9f63ab.nq.gz
│   ├── 4365c5e21df8bfa6af725bcf0a357b2a379f9e48.nq.gz
│   ├── 43955ad71c0d386169ece3066cfe92e6b59ab523.nq.gz
│   ├── 43a2bf84e83389cc41dc2a8e4471d03778b14a53.nq.gz
│   ├── 44150a6416fd2f8fd7e6022bb5cf2e7bff05d305.nq.gz
│   ├── 49ff65280c2bb6d235636536385f408e1cfc9fed.nq.gz
│   ├── 4ecafda6c9ca5087a2bd3f9794ec9ff300acd0c6.nq.gz
│   ├── 50fb429a84bf91b7aaf9ae0aad5ef51168bfaa97.nq.gz
│   ├── 52230fd0eab530a81c6b795f1024c07d8aa2b42a.nq.gz
│   ├── 5363f161a2a404f263e6cb02e415f01cb3c1399f.nq.gz
│   ├── 5424338ceaf0a90217e89c40479f4970cbd60530.nq.gz
│   ├── 5892fdc91f5a2b08cdb1b68e2b0e3f07df2698bf.nq.gz
│   ├── 59d96c8b40cb0f836d3f2d37f873d9539e76de28.nq.gz
│   ├── 5e43b65efedd4d6f4f2300e5f0adf8bacf0aab42.nq.gz
│   ├── 5fbdb9686a65a863ba1b4cd3e1a198b787c200cc.nq.gz
│   ├── 600a1473de0434ce02f8b8a61e7fc53dba2dac08.nq.gz
│   ├── 6208a703250d90982e5cb95ceb9512afa6462b78.nq.gz
│   ├── 6e3b7afadb4fe2055b6fc53b4a3d003e7f6533f0.nq.gz
│   ├── 6f4f65daefd8479529db13b566ce9cc8021ea5b1.nq.gz
│   ├── 70647f18c343e2af42840b479ec77aa97a27a0cf.nq.gz
│   ├── 71087f48b450e6fdf93c7303c253fb1a8386b2a9.nq.gz
│   ├── 728936251e419019da0937f06b49093b0da03dbe.nq.gz
│   ├── 736aa7308671ab80b8953fc44a522ce1d834bd54.nq.gz
│   ├── 737680d1cf86b5c7c49656c538d996b2f6acdc07.nq.gz
│   ├── 73c6d40cfb20f35fa4d62df71cedbb6d19004c59.nq.gz
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
│   ├── 8dad3f8a0d3dbfe4a6bec160de106373f411238c.nq.gz
│   ├── 90eb3c84e9d10bc3cf455ed2fd252df39cddd807.nq.gz
│   ├── 913030587f5b0e46aa8636c784579695d19de090.nq.gz
│   ├── 93642823637ff0b9de431d60db533a05a5ff3c79.nq.gz
│   ├── 94f3501fc61a0d9dc53bcc85f15dd40392b5cdd4.nq.gz
│   ├── 98d032d356fb43e56ce7a8012ea2192a7037c59c.nq.gz
│   ├── 9a8e8a264baece5e05dc44b929543ffcc201940b.nq.gz
│   ├── 9ae8f4dbceabeed6c04b72d800c8f3b2c546275a.nq.gz
│   ├── 9b183f4d5134072edd1dd6741d99ae9a216c46b4.nq.gz
│   ├── 9b3fb09fc946df670f3026b6fdd29c39efc743d9.nq.gz
│   ├── a1b9cfffe21b981ad550fbe3acf349690274d6bb.nq.gz
│   ├── a4fcd194076d99f975ad6dc3ac924826d0dc8040.nq.gz
│   ├── a5f962e7171ff3571e110f0a56cbec16065d72fa.nq.gz
│   ├── a70575bf5153a4623c02d8411588a46a0054a183.nq.gz
│   ├── a7369483c6fdaf5ca08bf041dd190db7c62fa661.nq.gz
│   ├── a73868ae7a8de8948e5047f8110776ca627c7e7e.nq.gz
│   ├── a8d66ae5059dd4409d3b62081b8ce08115a34ae1.nq.gz
│   ├── aaa23a84c282870422b571933bf0d0c08d785ac6.nq.gz
│   ├── ad56ae92ed2bfd33dbd3b5d8032196c2a5a7a0e0.nq.gz
│   ├── aebdffdffb79f73ee5827c90c8c089e54d9975de.nq.gz
│   ├── b1d0f0e5173b95f16a0d377e9921cb6c307fba6e.nq.gz
│   ├── b2d010d3eb4f210a739c5408a69f6c8392c66975.nq.gz
│   ├── b44c7f73084e2574f696e5fd4f9aa96746a0a883.nq.gz
│   ├── b5b9c133752ba6bc45dc1e8b92d874296e560f2b.nq.gz
│   ├── b711d3609fdefd7664f2982d225d96f5e53be9c0.nq.gz
│   ├── b7f51269a3b4e74bf6f74ef36215f4e23e33d796.nq.gz
│   ├── b8581dd898cbb33e63961b4d181ff0ffbe5d03ee.nq.gz
│   ├── ba7c1ab1fe2d7560ca01d43c9f37a85bd46f2247.nq.gz
│   ├── bc3f9aef0ebd983bcc75528aaf2e0dd54f5463f5.nq.gz
│   ├── bfb245b7c46fde33843b9ba29a1aec30e8908a56.nq.gz
│   ├── bfbdd6f004444731106be901f57c17865c046cf2.nq.gz
│   ├── c058a61cfcd79092c08ef7db033a28d9bcb799c9.nq.gz
│   ├── c3c516fc5dfe37644c00e33b481e44e899e42a8a.nq.gz
│   ├── ca517f4eb0cec1c691c0c2b54cd5eb85e906f11b.nq.gz
│   ├── cb1cb6abf3334a82aa239fe99521b8449b4e326f.nq.gz
│   ├── cb975436fb482786fe1023bd3720ccdae2ee68b8.nq.gz
│   ├── cc34292c38f5ee1a91802e32275b8f55ea911c17.nq.gz
│   ├── ce78cb9c0ac065fe0e7cbd6b5be0cea1f8d1e4a7.nq.gz
│   ├── cfc4203bf8f6bbd855fb3dc4c7e8da780b58a0d2.nq.gz
│   ├── d03595ed727ec2a4ee25003f2628e50543b611e4.nq.gz
│   ├── d2031110ddcdd734572a7c0b403664984402f54b.nq.gz
│   ├── d22352dabd89769555d44540a690f59ba3d6bda5.nq.gz
│   ├── d4fb4b56b0e00e2047b7cf4881cbb171554760df.nq.gz
│   ├── d5b2b218fda4ea80520c5712b702ed6ba691d815.nq.gz
│   ├── d6b96595223667934d6e166f5935f9c696787664.nq.gz
│   ├── d73771c91caa10ee44983f309eefc07f4bb1b246.nq.gz
│   ├── d7b06e5f6c9469ed4c04e6c189356f20940d9afc.nq.gz
│   ├── d9a1005de525a99d7149ae38092c76b0d36dcff3.nq.gz
│   ├── d9e113ec685b92b018297dd2f200341d1fba01f9.nq.gz
│   ├── dbac3f0e219ec4e03367611c555f9e722b6a0814.nq.gz
│   ├── de40ea7ca058e07a399acf61529d418c07eeee61.nq.gz
│   ├── e049448ed4a365b777bfcec98a629958f1e8d8cf.nq.gz
│   ├── e184fd8f41cbc229060cf69967d916bf6e2ddf2a.nq.gz
│   ├── e1af185b0048d05f250e1e3005ee80154aa832fb.nq.gz
│   ├── e1f9ad7b3b48377bfbfaa1b380c384ddea24060f.nq.gz
│   ├── e4b867329e05886a4818f86b117fca2102bc84bf.nq.gz
│   ├── e54195aa6afe78a9473f34bb4f558ed8ae660821.nq.gz
│   ├── e556b6779bd5c94d7d78348b226cb3631deef729.nq.gz
│   ├── e5ad47f6ace62627d1c2383c97861734cc10a9da.nq.gz
│   ├── e5dbb3c6397003f1f52bc10e8baafe699e50e6ff.nq.gz
│   ├── e6477f664376be077b046d2a1b0db5522f57667b.nq.gz
│   ├── e75f35cf541a6e8502e5df7b2f1529963958660f.nq.gz
│   ├── e86242136912ba46283c26c925976a3eb48a01eb.nq.gz
│   ├── e992a3e36f8059a9f1e640c6cfb9c66a9c004793.nq.gz
│   ├── eb2d4e86a4722c7fd9daa770f6b19eed34c639bb.nq.gz
│   ├── ec5c5a08fd3f45f8a498a78649cc9f4cf857aff1.nq.gz
│   ├── ecf0ca62c4442a2b7a79d1849b209a2cc9b2f3b5.nq.gz
│   ├── eee03f3a4991b06e3ce8d136dbe5fb9f48ac0639.nq.gz
│   ├── eefbfcc2cd894adb30dce8614ffc6181401c3071.nq.gz
│   ├── efe42c15e74e492592cbeb7d370226a789a1bfdd.nq.gz
│   ├── f06fdccb1e36d4be3518bcb73d3813d84b2fe0bf.nq.gz
│   ├── f283c4b3cc41b7f5d50d587c35ff3bc4333d12e1.nq.gz
│   ├── f4d6102b3c49102490cdfc9a78be3e66ac887707.nq.gz
│   ├── f507feda73c43de02c9268ef502bc4c3a2ebf32d.nq.gz
│   ├── f6c3a84d10222d79693aa5988000bba328a5322d.nq.gz
│   ├── f6cd60b80b618af1df984960f8763b7e5622eed8.nq.gz
│   ├── f81cabf053fb4487bb3496afbc276556076bc3f2.nq.gz
│   ├── f8ed54d158570c5d011b57c4c19b24180a00bca5.nq.gz
│   ├── fb2b20d8e96590e3a657eefab80b2db8951d8105.nq.gz
│   ├── fe143546d60344be882e96fb29cdf5f9d38558f5.nq.gz
│   └── ff15cd89957f75e58011070946a23fcb3a61bda1.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── ad4fcb0478e98c57b7eaeb8463f13a22c0ba2c65.nq.gz
├── filetree
│   ├── 0938c82334383783f7600d39f90d5de50ccd0754.nq.gz
│   └── ad4fcb0478e98c57b7eaeb8463f13a22c0ba2c65.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

17 directories, 160 files
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
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
