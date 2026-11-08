# Repolex Knowledge Graph of EleutherAI/cookbook

RDF knowledge graph data for [EleutherAI/cookbook](https://github.com/EleutherAI/cookbook), parsed by [repolex](https://repolex.ai).

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
rlex download EleutherAI/cookbook
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 827ee3b293a63f14403f1467d08c91fda213f4e6
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 827ee3b293a63f14403f1467d08c91fda213f4e6
│           └── chunk-001.nq.gz
├── blob
│   ├── 0223f3ae579fbbf2924263443c9b648d5bb501e3.nq.gz
│   ├── 025464cbfcd2aaff334f35d78367899cb1bbd8e2.nq.gz
│   ├── 0eb04c7451f10f011c22c94ea002ad17c48c47f7.nq.gz
│   ├── 0f3aebbb15302dfd8692eb43b6707a733a0b7a61.nq.gz
│   ├── 11bcdc310503a07880ee79aec437788a7f4bc360.nq.gz
│   ├── 1283314d05b2bac8eba73ed23ef6f7cb339538eb.nq.gz
│   ├── 141a6e4e9e50b01fb7d64ac0f336893a30968e3d.nq.gz
│   ├── 14a8e29348b141f29f0afe6e52fda46da5210b85.nq.gz
│   ├── 15b35e41163ec9989ea1919689040bcce69dee5f.nq.gz
│   ├── 16b660d6559b53ac07124d2811851a08f9ef8ccd.nq.gz
│   ├── 174ece5f0be106099f1a07c0462f0718dfe9ea93.nq.gz
│   ├── 1a3a3095392375d02b061807b55170da3076fb95.nq.gz
│   ├── 1b5c4b8a18b9bcb55f725afe246ca883581803e5.nq.gz
│   ├── 1d87938add0583caabbd40c80a4752a9e436fd3d.nq.gz
│   ├── 21ac734751433d2c7b79011ad1e65ba12b0e7679.nq.gz
│   ├── 22b0f7b9ec4263fc83bdde4957e076aed26be488.nq.gz
│   ├── 251337d6898ea783f7aeb4d1d9b6a8ae60b51d16.nq.gz
│   ├── 25dfab670a554006b82c57fee9ad26dd7b831e68.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 296149447c7ece7fd634d06f9c5eceb1b7ccae45.nq.gz
│   ├── 2d47f1d93584a8ea726cd554a9208c32aad2f6ac.nq.gz
│   ├── 30a9b45db134019e90a934500d38b0a2a7a92d30.nq.gz
│   ├── 325e46ba42cfccd74cdc8c50b82ae29231dd9639.nq.gz
│   ├── 368ba1e6971f73f1791876e6de2782922dfd0c4d.nq.gz
│   ├── 39fc56987d87755bda8eaf27f8128f91c5957a43.nq.gz
│   ├── 438e18c89b1b8d74fe5fd75c7224485f9f3e6592.nq.gz
│   ├── 4a9f98a317a855776e10ca41f523745dfecadb1b.nq.gz
│   ├── 52e354260e29c6e802fa7af874c23a22369fab6f.nq.gz
│   ├── 54134863568623bd1a4aacb059a5e760af99becf.nq.gz
│   ├── 5c4ba1d5a0b61bdbcb76bc235359f944f1eca0f6.nq.gz
│   ├── 5e14b4a78d54ccdf15fbaf3d089a7e61315653d9.nq.gz
│   ├── 5eb9823849c5eb3660e305d0abc42de655b75dc1.nq.gz
│   ├── 611d2adbfa3241d11ee0e2e619b8fa1bf235ee41.nq.gz
│   ├── 627770df4a44736bcd84a3a409884447ad993c9a.nq.gz
│   ├── 68815075a2e00257ac1d8121eebd997e46880221.nq.gz
│   ├── 6946598844c4742111a0c3e6c8cc44f83b42ab94.nq.gz
│   ├── 6b0d07e94ada9b64a0a054fa003f1e3c90a2bd07.nq.gz
│   ├── 731dd464199efffbcbad7b8ffc9666bbcd68d752.nq.gz
│   ├── 74f99e4744a1d4c72bdab40fefaaf99a21d6964f.nq.gz
│   ├── 757850d2bc054ff91a0eb81a2fec497115e2d64b.nq.gz
│   ├── 76d28d4d9284864f656753ce941d3fbd405da749.nq.gz
│   ├── 78f2992adb7b1c51f3531897dd569dd10cd8b0d1.nq.gz
│   ├── 7a6b7c68e301b9a389001a89302a3cc10c21f1f4.nq.gz
│   ├── 7b937053bcb0e3600a9add1b7c1d42661fe824ed.nq.gz
│   ├── 7ced78acd756c68d739160328bc42e0c8f15f20c.nq.gz
│   ├── 7ec73e712c9ca504603348aa99524359a0b61099.nq.gz
│   ├── 80caa2d9711e7b3a21edf2c982870547534e1262.nq.gz
│   ├── 830326c3f388e9ce609de7b580998b3d4648f2bd.nq.gz
│   ├── 8ad2a88c78ef7836f534f4097baee17b265c2c2c.nq.gz
│   ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
│   ├── 8dc1d3264ed02a3c665d99adde1f0b3d90093dfb.nq.gz
│   ├── 8f9db7686696fbea6c94b998db4b40ef426c748d.nq.gz
│   ├── 92edbd6eb1feb4d7731be3386207fa65b01ed543.nq.gz
│   ├── 943efdf1a56be54ed65ee843096caebf647c75c1.nq.gz
│   ├── 945c48c43455ed9b31e4faf9250af83e0684b8c9.nq.gz
│   ├── 9772bdaa8e123cac91038b1877201da13ca164b4.nq.gz
│   ├── 977e59481c5adfbd72c288655f4c36588397166d.nq.gz
│   ├── 9c43458d3ec0398bbe004a6a4c622a61fc57d334.nq.gz
│   ├── 9c518a9cd19e52f918e8f3224bcf419f48db1040.nq.gz
│   ├── 9edc4271d352a5bba8344323f2012815955c0655.nq.gz
│   ├── add548ea1028e56c29f3e51d2282aceb11f70fbb.nq.gz
│   ├── afe1f0719d59b665dddaf9472fd2f2d287fe68ec.nq.gz
│   ├── b0757196b2a5d6fc28e1976f2e6bc407db8494c0.nq.gz
│   ├── b55e96cba6f299788b738001f7e0be562d328840.nq.gz
│   ├── b6e690fd59145ce8900fd9ab8d8a996ee7d33834.nq.gz
│   ├── b7c162c784fc85dc22c748e53d1de6052cd64df2.nq.gz
│   ├── b85618da8b923d9c005db1dfb75b8fd3b63059d2.nq.gz
│   ├── bc4032649eb5cbad85f5a2d22050c210df160bed.nq.gz
│   ├── c14693a69dc60be551ddc2b07a1ea15f5d3d39cc.nq.gz
│   ├── c99da8cf9913551d3a0aadef7df4770cbde31d27.nq.gz
│   ├── cb12f2569f1a11e4e23556437dc9caebc54950e8.nq.gz
│   ├── cd6cf8676b0d4fbec8dfa19607e315fac408d2f5.nq.gz
│   ├── d0216459fbcc98a34bbf0d18dee479ec862714ab.nq.gz
│   ├── d28e0cc6baf83dabc22cbc1b9a844fbdcfa79be5.nq.gz
│   ├── d5488c11c39cf598e04504d4ab06956102e99127.nq.gz
│   ├── d57942af4c0f0f24a400c69b95e0d1284daf6b1e.nq.gz
│   ├── daed9b1c33e1474d68da9172850d60694a72cf7d.nq.gz
│   ├── dcfe50ac54fc6673ee9f30d33febedc3fb511562.nq.gz
│   ├── ddb45c3f3a8f2b36db1ecce4e349677fd3755600.nq.gz
│   ├── ddcb9f38dd2dc3bc350a108d534532b5791e7f45.nq.gz
│   ├── de092a321677533997de6c5a1a40a35b708cd502.nq.gz
│   ├── dee4d3109d946d0d8fbd3f8b7527a62c72785d25.nq.gz
│   ├── e05c584294f028944f017d4f5527ac7056b4dc6f.nq.gz
│   ├── e16a21589590b5429ab40c00cf81511bd500df48.nq.gz
│   ├── e4e29dad595ce952c47959afc6f55eb7c024a85a.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eb14337f12dd7e5cf1b2afd56a196695669a3cd6.nq.gz
│   ├── ebb08f962477407f017dc175badda6a0ee19c21d.nq.gz
│   ├── f2955f95a53a2132f503a08c748766986bf0c85d.nq.gz
│   ├── f6e72e905a1a751f464e836080cb558139b806e0.nq.gz
│   ├── f7325a07cb543f69bf5e770acf93c62403a13757.nq.gz
│   ├── f779a4a7970f0b413d4ce5ae38ffefb03aaf64ee.nq.gz
│   ├── f8a112880cd7a944eebbd7272ffac15b66d8f8fc.nq.gz
│   ├── f9063a313ef9ea41e17ce3d12984567b86af775e.nq.gz
│   ├── f93a912a82c33aa3b094f2ef506bc0de049dd9b3.nq.gz
│   ├── fa68c6a75f4c25c2d506f6cb8116ddb40775b313.nq.gz
│   └── fba34e51257602f92b41eb3f6a631968e341e68c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 827ee3b293a63f14403f1467d08c91fda213f4e6.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 105 files
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

[EleutherAI/cookbook](https://github.com/EleutherAI/cookbook)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
