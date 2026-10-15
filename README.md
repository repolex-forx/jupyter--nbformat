# Repolex Knowledge Graph of jupyter/nbformat

RDF knowledge graph data for [jupyter/nbformat](https://github.com/jupyter/nbformat), parsed by [repolex](https://repolex.ai).

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
rlex download jupyter/nbformat
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── cfb73afdd2a7f358953f2a34f747fd0d0e9d6288
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── cfb73afdd2a7f358953f2a34f747fd0d0e9d6288
│           └── chunk-001.nq.gz
├── blob
│   ├── 00223432ae2f3ec8ce1c2344fdd2aabcfa5b03e6.nq.gz
│   ├── 022b92b32b5f04be750020d45b8e34036997d98b.nq.gz
│   ├── 02a7028132a7461b9a4202f1afeba852f725c412.nq.gz
│   ├── 043bbbe0ab8b804e6883bc984456aa735f34b551.nq.gz
│   ├── 076177a497fae1482179137af028465c4f6b9c94.nq.gz
│   ├── 079d6f1ed71dec72884e1e48e05b3d1d4f44c0b9.nq.gz
│   ├── 0b5db2190fdcdf97fc39450ad89c53ddaf35bfe9.nq.gz
│   ├── 0e46393367c9189c3a5ecd06d5573b75a7f355c6.nq.gz
│   ├── 0f2f830c6e4f91973ffc4754c36f9c166fba4954.nq.gz
│   ├── 121804fe8ecb60a38bc1a51c2540ea9bef1bf806.nq.gz
│   ├── 18dc13d149eed8c8ee8f05fec42570b3b8b6d823.nq.gz
│   ├── 19fc5a703669fce6a275f49964c7a008f1d712e2.nq.gz
│   ├── 1b9f9c6c504ca5b16825089df3a6df6f8701e7f7.nq.gz
│   ├── 1e85fba0e447f4cdd560d193a69e75f08d4ca1fd.nq.gz
│   ├── 1ffbcb7ad73087f145431a16bde9b65b5f4674df.nq.gz
│   ├── 20978753c50226536968b90141c6a48d183b435c.nq.gz
│   ├── 22bcce0c528ea77fbff294bb0a00227aa4775010.nq.gz
│   ├── 2435c06eabb39409237bddf8362ed340bb0dac79.nq.gz
│   ├── 2a89d18e1c5f1f0560adbf6cc2f9735a5dbab7f9.nq.gz
│   ├── 2b61a123ce9dc05a26ed5797f7e81d194d6cadf6.nq.gz
│   ├── 2dd5f95510ffa4bd21c06da3c82fc90cda4ed516.nq.gz
│   ├── 3465d4eb20430bcc91dae2a19ad13210f6267dd7.nq.gz
│   ├── 349295035ef64ba06f6ce075ffed23333c8905d3.nq.gz
│   ├── 34bd3f600fb4692d946e3af6607277f44efb6758.nq.gz
│   ├── 38c65286629af2da5f65064e831a2717a939ca07.nq.gz
│   ├── 3c44a80fd414021d11f66400473ad7ac18b88590.nq.gz
│   ├── 405ea98aae5c4fab6651927ae8cac70471f48741.nq.gz
│   ├── 40968460ca59d730ae309e794176348754daae85.nq.gz
│   ├── 446e9b4729ed03ab4a485552485a562127793536.nq.gz
│   ├── 45ad68e3fa717550a5ad24208cc0efd3c6c9613f.nq.gz
│   ├── 479976abae77f8c9510cc086be156b8ba533e587.nq.gz
│   ├── 4992ec8a240b32d3b528a17501414dc3df1ab30d.nq.gz
│   ├── 4b3d422aa14ff5203e4d281c584ae92791ab6d78.nq.gz
│   ├── 542b039f73cb70d177a31b1fe080faf555cada8f.nq.gz
│   ├── 54cc205d76ed3621a29f9556b52a99beb1e7fb8f.nq.gz
│   ├── 5885656a12c6ce1c5085dd523f7e522ca3fdc9b2.nq.gz
│   ├── 5f4502f209f5f5a27a287b41f09c8c4fa7db0fa0.nq.gz
│   ├── 63455576371993fc5a45f49619f665c9e43c3d83.nq.gz
│   ├── 670bbd35f343f0d1324b8e6056ba42420f7ec6aa.nq.gz
│   ├── 67716be3c386c6e84968439cfd9900598835981e.nq.gz
│   ├── 67dc56c5201ce1c35a9a61671ef56905d604eb1b.nq.gz
│   ├── 6803b0fc7969abc5c20b2657f4d630d7f60d0906.nq.gz
│   ├── 6b03af2268039753425bc2881a4365dcad251794.nq.gz
│   ├── 6be2aeaaa49b780699b740db0c556a51d684f9f7.nq.gz
│   ├── 6e23b4e83174e9a9d2707c134d11641af64cd37f.nq.gz
│   ├── 6ecac1824062b0a88929609b5490135af12b2337.nq.gz
│   ├── 70efff3e58666d6d394ceaa2162913d47fcad9c1.nq.gz
│   ├── 72484378cfd6c66c4fd39f97b801c24856cc9f62.nq.gz
│   ├── 760d82f9915ea50ebe0e232a0ac95effb89522c1.nq.gz
│   ├── 7b358399dc7a28258139d54cbc1d8f7b3c5b7483.nq.gz
│   ├── 7c44f9a8a8f8b58940bc7b6c20557d9ec1544708.nq.gz
│   ├── 7e5b865e54b91ffa7813e9703ae487493ac96bb4.nq.gz
│   ├── 7e8bc3a489fc0e8c126199ceee85943ee179facb.nq.gz
│   ├── 83b01394abcf8187e28d3f17974e9eb9bb62f5a4.nq.gz
│   ├── 8b7d69b57716a849dd3f26fc2619622a9c674145.nq.gz
│   ├── 8ed1f23cb620236dad2219bb8e83fb30b6afc3f3.nq.gz
│   ├── 8eed353ef78c0cba453bd8d7837002c718d38ae8.nq.gz
│   ├── 8fd2aabc8ca4a753cda35b59e048cc5435629483.nq.gz
│   ├── 912961c19c3b56c3e77daa2615013ca4ee3f6a6e.nq.gz
│   ├── 98a32383515e971110b90b5a898c49630d0efd72.nq.gz
│   ├── 9a824dbc604aa760fa8bb73ca25d6c4c14a25be9.nq.gz
│   ├── 9b4d8bc1c5da6022cb6123d72b20f5ed7c611bc3.nq.gz
│   ├── 9be986d98d535b13ab4625b52f78d7f536d53e97.nq.gz
│   ├── 9c28d2f374514b0da3316c307f6f9e1bba2b27a7.nq.gz
│   ├── 9c96a01b830064e6be75fd17e9b5f94e0f1716d5.nq.gz
│   ├── 9d380d6d1efd506438fbca301c95812f40bcb2c1.nq.gz
│   ├── 9da3b55e6b11b80cbae7c5ac2e28b0310d60e30e.nq.gz
│   ├── 9ecad4295c22b59adafdcf8e1b3fe47474716c5d.nq.gz
│   ├── 9ed340601f7da83f471eb3a8d1852e7b88340fd8.nq.gz
│   ├── 9ee23f5718fc443174094478a7c46507487b8e86.nq.gz
│   ├── 9fd3e6703af5da0057446e51efacea307bde9872.nq.gz
│   ├── 9ff57dd6a5a32fd6d30dee782437fdfbd22c2d7a.nq.gz
│   ├── a0b02e4549320dbb8b2328e7357a991bcbb4f967.nq.gz
│   ├── a37eda86130c66f486523b2a53ce0f8ee4695ceb.nq.gz
│   ├── a3dab5c52765950292bcf732d20eda4656bf329b.nq.gz
│   ├── a6ba2066c5fb981632ff57972aa368f9bb8dedef.nq.gz
│   ├── a806d073246187b1157e154eb0f2fefdefca3adb.nq.gz
│   ├── ab0ddca518df98edda3d24dee57453e2fb37fbe5.nq.gz
│   ├── abe368a1ee1754da8036aaf5b3e87087cfd27ab8.nq.gz
│   ├── accd3e92abf976efa560388038c707b1533c0e1b.nq.gz
│   ├── ae2b26a5c1dec1ef3c673764bf0b0bce3361ac6e.nq.gz
│   ├── aeebce8eeafcb18ebba90b9b99a633191f171b60.nq.gz
│   ├── b4994eb4f4d129a25829ac8999b4102809bed532.nq.gz
│   ├── b655927ca764f08cb272dfec73236a8ef8541125.nq.gz
│   ├── ba26d7532b52be044e039feb4e5e8e9bfd19e5b2.nq.gz
│   ├── ba544a4388d369247f5981203daf45c13eef037c.nq.gz
│   ├── bb65967daf03fd792fe885b26612eae8efa5837e.nq.gz
│   ├── be510b28e8c6a9d8826ebd49b72b379f633969ab.nq.gz
│   ├── c109ee3e60b164e171f6e324b7852aab7fd1c608.nq.gz
│   ├── c20e1608a60a3f8195749107e5981d4f9240a0a8.nq.gz
│   ├── c63a73d7e827486bb3eb58a24d57e340ea53857e.nq.gz
│   ├── c7bd07cc0a08135c388a84ee0b43653f7d9876ef.nq.gz
│   ├── c7d97312a88f04da1b312b73778d5ae716bcf701.nq.gz
│   ├── c8cee6c7b0df1e196ddaed59c89bbfd9a45ffb0a.nq.gz
│   ├── cbf2fe24575a6fc82cfacdd17557fb9317a39712.nq.gz
│   ├── ccadeb9f9bace87705e5e97e160c4bc0c93c7720.nq.gz
│   ├── cd8b9ddf59b09a56604ad47942656bdd9981810f.nq.gz
│   ├── cf87477e186f180fe5a5ec8be08ba3f968ac40ba.nq.gz
│   ├── d0eeeb4185eb94623beb1ecef0533802f9ae00dc.nq.gz
│   ├── d0f50fd77ba4a0b7d393bcfb396f8af2fe5f5ea7.nq.gz
│   ├── d8546b4caad9aaedc6cb6f60c8d59224c3060e4e.nq.gz
│   ├── d90d273496d2b1f7fc02387029af559f219d726d.nq.gz
│   ├── d96de05106d9edbf5dd0f5dfc8659409fc23e6fc.nq.gz
│   ├── df21df85c15e934fbe34b628b5a075c43d9dfe89.nq.gz
│   ├── e0518fa615b1955ea54106733f8150ca5e5967c4.nq.gz
│   ├── e062401e462eec0e679c32c46fe976b86a7cfaf0.nq.gz
│   ├── e0b2a0ada7c55fb77d245d3f7f10252f8443bf9b.nq.gz
│   ├── e360d6cfc82b0eefaba4171a1975129c24866d55.nq.gz
│   ├── e39230250aaf9cbe0edfe2fe6f0d8172fd58c8fc.nq.gz
│   ├── e538e70c43500ee37c860ac01dff5b42d63cc818.nq.gz
│   ├── e66a6a9825c7321ca97bb4375bef6a20b80479cb.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── f1f18423e177874825431869c5a7d8d522e0e077.nq.gz
│   ├── f2abef13d2a0be852fee10b6773141d550c6e414.nq.gz
│   ├── f344ed9134f7c2d05d017bda6e9daf26e98dcaf7.nq.gz
│   ├── f5902652c703570ed55e923d19e15ac59c277971.nq.gz
│   ├── f86c59187665bb00837ab12e60937522997ae8c0.nq.gz
│   ├── f9271609804bc84d14e619c77510b332753f8152.nq.gz
│   ├── fb434b257b389150c00a0553887034b4e9353610.nq.gz
│   ├── fb7028f82e4f782149e35be39193f7e2cc1c7230.nq.gz
│   └── ff9d7b8d2d26199db52dfe220c0f649783245b41.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── cfb73afdd2a7f358953f2a34f747fd0d0e9d6288.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 129 files
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

[jupyter/nbformat](https://github.com/jupyter/nbformat)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
