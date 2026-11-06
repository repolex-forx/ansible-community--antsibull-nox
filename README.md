# Repolex Knowledge Graph of ansible-community/antsibull-nox

RDF knowledge graph data for [ansible-community/antsibull-nox](https://github.com/ansible-community/antsibull-nox), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-community/antsibull-nox
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4e731b2fc8dc4f2fe1e8f0f4bf816b8f5ffa85f1
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 4e731b2fc8dc4f2fe1e8f0f4bf816b8f5ffa85f1
│           └── chunk-001.nq.gz
└── blob
    ├── 00d7a3318ca1418c299a8d604996951d7ababa11.nq.gz
    ├── 01c2a66c802c228f69b3c58f19d59b831e6f3e30.nq.gz
    ├── 0505c03f746ec9582e7763434b5ec66699f4ad52.nq.gz
    ├── 05848f8b971da3195c9ec0b13e56e4cec04e0f9a.nq.gz
    ├── 0760cee515b441d5c553051df4a17eefce98b87d.nq.gz
    ├── 07ca8eb5974445ed32578d4a885f8b524baa83e6.nq.gz
    ├── 07d355feb1dc808f74d98a5f07bb487be3e1ee4b.nq.gz
    ├── 0c74e3202b1cac721f1cab94ffb3ec58f79ebb03.nq.gz
    ├── 0c76547a8f0d4b6d0e20e2fdeda3b2e3237f68e5.nq.gz
    ├── 0dcc5513dfdb02ecfc94e2d99bd9cc791bb6dde2.nq.gz
    ├── 1076ee27dad4d199293d5b5f302e9133d972c0dd.nq.gz
    ├── 12e59e31d61d8415e746e189aa71371e9d7a8357.nq.gz
    ├── 136b3bbc7ab7870cd478c0e8a875ee6bd909bf4a.nq.gz
    ├── 151aac3f07472e09997e07d1c909fe9f88c37d3b.nq.gz
    ├── 162c0e85e490eed7ea9bfc9d695e751b8f42b445.nq.gz
    ├── 177ca3eb54ba165bf962607bacdc06ec7d0ce428.nq.gz
    ├── 19817470d53ca1cc52e4e05f1037d7664be2ca28.nq.gz
    ├── 1a5b2b80358386c140d5db384b0955909d503ef2.nq.gz
    ├── 1aefc18a9b2ec64beb94ac24626482cf4521b96f.nq.gz
    ├── 1b264d4508ab6a0d2865d7833ce04e094cc68bf9.nq.gz
    ├── 1b5b2c4f0187717b7c3cac5bbff0190c874f712b.nq.gz
    ├── 1c4b059ae0367b93053d3eab42a27776ef6cec08.nq.gz
    ├── 1d63c67bf3f18179d42ff5136086e4aff1dc829d.nq.gz
    ├── 1d7c7da0119623f46fcd02bab89304678c82471c.nq.gz
    ├── 1f26de73240963e8d1361707c6c29d39a734a12f.nq.gz
    ├── 243da9537d80ce6ed0b27b95d5d022d52f9b1ca9.nq.gz
    ├── 25f8b0750f9495fe0413420d8c1c49123405d436.nq.gz
    ├── 26fda2e63ba6c0abd41b88b3a4b793a8a5c858ae.nq.gz
    ├── 27a0dfb4f4ba1a245cfd9838baa18a5b40fb7b37.nq.gz
    ├── 27f6a4b70e235a9411d4e7df6a12fb23a25581da.nq.gz
    ├── 282a1593cdc7befd1e69fd5fc02c9eba763c1401.nq.gz
    ├── 2a507c7d13d57f3e8736789fcc6013be92d82ddb.nq.gz
    ├── 2b74a866b35ea430912379fd265c6a75111d9087.nq.gz
    ├── 2e06d25ecbcdb51fbdb917bf927c5a63b244d748.nq.gz
    ├── 2f4fe4d3e9994aa65e9bcc63817d73a5b78e6f56.nq.gz
    ├── 301015eef82ab4f4088a8c1dd62a613e3692891d.nq.gz
    ├── 313ef243cced13486301b7427fe10b21b86cc308.nq.gz
    ├── 315104fe0bcdd098b03604c6f046c22f0f89eead.nq.gz
    ├── 35e564ef4d48e36c52374296a8d76d6bbef2b48c.nq.gz
    ├── 3640f9b5ce212f2dba2cc7446486d3a85717b81c.nq.gz
    ├── 36de93039ca732a3349eac663576c024a21e4f19.nq.gz
    ├── 36e287bc882daa7d288f38190bb9589b14148816.nq.gz
    ├── 3857a89713088cd5eeea13f6f0720c45a32820f8.nq.gz
    ├── 3906fda52d9f4472243949778853f74b1d28f37a.nq.gz
    ├── 3cde8fbbecec6b5e14416d166a0a9e5e8bf25f71.nq.gz
    ├── 3d7bd42f69407623a5f469c37a3caf2c986d342b.nq.gz
    ├── 3da5ab4c77285a43158ac02ab7748b6021f7049b.nq.gz
    ├── 3dba67b0e64828fe69e837603a442706c9991caf.nq.gz
    ├── 409ce7bd1934e44675e3ee30bb048ed2d777f234.nq.gz
    ├── 412d4f67720e8d7214e36f5ba50181b9bb3294ae.nq.gz
    ├── 424216cc2e0daa0acc3720a04e98a26eb43f9a5d.nq.gz
    ├── 42ba9fb4883ee60ce5199cbb4201e3f93e3695de.nq.gz
    ├── 443dd53b74a87a311e010c86d695d752c831ae4b.nq.gz
    ├── 444b0d8acbd294fb911a5ec6b137632d1b51a35a.nq.gz
    ├── 452b6f42f8b6be088f1fcc044c9594d4bbbdc4a4.nq.gz
    ├── 4575c2685755fec7c72c949bd5fc8fb337235dab.nq.gz
    ├── 46368cbe7ebbd3c98fcebc7697b9ffa852286e68.nq.gz
    ├── 4934b6f8e2c4a98bb037b78c38f0d2241a5c1727.nq.gz
    ├── 4a31b5395687f1e426be626fc7db3796c47befc9.nq.gz
    ├── 4db79c77e0cd1ea0b5359a3b242be775d3e17fba.nq.gz
    ├── 4dc0430567d3c9c1d64293a143496118cb300bd2.nq.gz
    ├── 4efc2731dbbe354b6d850531259231d45929ca94.nq.gz
    ├── 4fab1a804b2f02a647b9028fdad8f492b470ac77.nq.gz
    ├── 502b5908d35567f6de7c4b8ffd499f56779aaf2f.nq.gz
    ├── 50804672e0269f4e8b8d20cfc9ad7a1237607c31.nq.gz
    ├── 508243e8886e7807aa3a536c1b53d2a68769493a.nq.gz
    ├── 50db4d1a1f7291897f67cb88e16a31dc3c3b4680.nq.gz
    ├── 5383fb4999a3a042dafeb43fe1e2d07aca32f8ed.nq.gz
    ├── 53f5495f2692ca238735f85f43c47aedaf18e08c.nq.gz
    ├── 558b562404989a5d8e7b1f08cb369ca81bc8bea2.nq.gz
    ├── 566a45a213746a1276632f527845467c035e0793.nq.gz
    ├── 58ce7b080fa351eef60a741b435cc44e65ba8d9b.nq.gz
    ├── 5a2cf4d1d95c5adf54fc7e68e8dc69fdfeff41d7.nq.gz
    ├── 5a9f0c2985e4542f7cd52dc960c0f0265f5d4c29.nq.gz
    ├── 5afa9e4d8b2bafe36dc55b8482e1923bb306ef90.nq.gz
    ├── 5b33c74d5411769a3466207920bfa5b207990477.nq.gz
    ├── 5c556869138ef75a80ccbebb61d3baf9ec7180e1.nq.gz
    ├── 5dba1821519306412df0debe3ec0986424033216.nq.gz
    ├── 5ee7812edbb236187b2434d8d01342f71c10b922.nq.gz
    ├── 5f47795d767578dbb9f6fd2ecd6930ba7e292f2f.nq.gz
    ├── 5fbfdc0c34ef24f23829f72cc0f3ff71aa7a1c91.nq.gz
    ├── 606454ff08bbf49d0a2ff2248ea72e20e978c4d3.nq.gz
    ├── 6098dad63e88758bc6abe62a2fc3fc9f369fa9f9.nq.gz
    ├── 60e28bd4f0d5a727c99e908f05122dd3728ba91d.nq.gz
    ├── 626981d9f9d72717ebd489da3a2851b50030d49b.nq.gz
    ├── 68b03f504ac6d04ddb1c8273d62bf0d90dc843c4.nq.gz
    ├── 6aae55385fa2b5a716bc334b63e8bbad8e3dc35b.nq.gz
    ├── 6c4958feba8923b907f36c1bc80cc3f2c722ab99.nq.gz
    ├── 6c990fdba29474213160c69d9053c30eaabd3115.nq.gz
    ├── 6d6cf5675179015a9b7bf9f04967e95e3f5d39ba.nq.gz
    ├── 6e4074b867d7cecd9749e080b867bafa8989bca2.nq.gz
    ├── 6fe26dea99175a136dd103f5f990180937e2abbb.nq.gz
    ├── 73f54ea8f9cd53d259259225773176d4766ebf86.nq.gz
    ├── 751b331d7778cc1fb67fdd3a6cb164cf65208433.nq.gz
    ├── 7522bd8a95753a025b25c7978908ac3b4cb10de1.nq.gz
    ├── 771559befd76d55c43c4aae88b6d0c254b11d7d6.nq.gz
    ├── 7715cb4605617a18dae8ca0c6e0f702e709881f1.nq.gz
    ├── 787026288870f3ed6866f57e6d45670f6e0e6f03.nq.gz
    ├── 79c625b751fdd543fec1032d69c548950378e0ea.nq.gz
    ├── 79c8a02b8c7ef53b72d3ddea6eeaf8944d76b683.nq.gz
    ├── 7bb9d2119f64e2b9ca3492be3055d404c6bb2ce1.nq.gz
    ├── 7c53cab68f97d183dd82dd84d910dd1dae3b3598.nq.gz
    ├── 7cdb6c725610606493ca6e54882ba131c430ab04.nq.gz
    ├── 7f00d554b450ac8a2b3f1c759acfcba690eda45c.nq.gz
    ├── 7f5694b6d9a9fd7100ac6c329bf9b648b8f8b3d5.nq.gz
    ├── 7f8771b88ad37bbc1c6cbc5995327453c0388e36.nq.gz
    ├── 7fca980f9171bac3667ae3cc02568c34024423a8.nq.gz
    ├── 81f13ba2f180e10b9228426e84f597e258d584e1.nq.gz
    ├── 81ff793e3a166364606b1eef0efb1cade4e593bc.nq.gz
    ├── 826a6a3298bd12300a108f845501605e54c8a5ad.nq.gz
    ├── 863bdb3919d51b33463ae6bfba0beb3c32a18338.nq.gz
    ├── 86dd4ba4ffbc0c40c88f7066cf3966ad6aacadfd.nq.gz
    ├── 871ec8be2c0dfba25837672cae1603f129efd13e.nq.gz
    ├── 8977ff1ab42617f9fc31d602cfa99c00e430974d.nq.gz
    ├── 89c103807eb7cde45009546a7cc89bfa0025de02.nq.gz
    ├── 8b79f91d15a720e16465b1b94cfc579c3a3719dc.nq.gz
    ├── 8c9bbfbf6cc5ddb3b234ef7f68a444d3646ea7ff.nq.gz
    ├── 8cf583ffb458c496f9cb84e9be2d08d39daea750.nq.gz
    ├── 8e07af7f927e9ecd607342b7610a4addd83de6b3.nq.gz
    ├── 8ff66858b9be8a79211d3f57b56e34c1b4d358a2.nq.gz
    ├── 9171e258868033787a94ea96c9ff242f936d3a40.nq.gz
    ├── 917d7d26243675b88539735228fad3f60bc4aaa8.nq.gz
    ├── 91c1918e7f727f022e2b0b095832b7483a0e2068.nq.gz
    ├── 927693a8fc245dd673b4d22dee1455b377fdea2f.nq.gz
    ├── 92d54a0efd3b0e3a3315666b9d07c9665c9ab667.nq.gz
    ├── 92f78389b57d792858cc3ae80b6069338813cfa1.nq.gz
    ├── 951f23b02fb7101c216de6290491899c68aba91c.nq.gz
    ├── 96c976ef81d02d83f21f66ec7528fffbf9c6b13a.nq.gz
    ├── 9804fd7e89623ef1cd24b22d1fff2884a202ca99.nq.gz
    ├── 9836f141b66da27a868251cc647e6aff5d320409.nq.gz
    ├── 99178ced5aa6200093479cda0d1ab5ba113db39f.nq.gz
    ├── 993e4be9290d08c9382b879ff95789746a251688.nq.gz
    ├── 9b9f3318b68ec486854a1c2052ecb7f22bc0860d.nq.gz
    ├── 9c52acf30ab22f9dbb3ec736625173b609561aa2.nq.gz
    ├── 9c603482de96a296789f0b2b8f1f66309c0a94ae.nq.gz
    ├── 9d3290082d05a887792860004527cf96199b829f.nq.gz
    ├── 9e523e0f1867d61881f5ad51c861a8fe80ecb917.nq.gz
    ├── a02d6f8568a54e05b34aea8a2a60173d3a9a995e.nq.gz
    ├── a06fe955ac06d778beaf2b1d46dd93ee0582b98d.nq.gz
    ├── a1390a69ed92e252cc59a843354cd415822b0b05.nq.gz
    ├── a1ae265f0c1416229eac126e177318d317913a9a.nq.gz
    ├── a1c11be7ef1d862207f137651ec8fd579a4d37ef.nq.gz
    ├── a27704cbb1eafe46cad3ed89222d0a647942f23e.nq.gz
    ├── a2986dc81e9ab373ec1c6d5050140b9977b94983.nq.gz
    ├── a3588b2cca763484eb897d8ef9f298ed5062222a.nq.gz
    ├── a4224e9d8ca540a84f4b94c8b817aa8d92144f41.nq.gz
    ├── a43f35023d8df37ae67aa2b1f9ebb6a93a77c629.nq.gz
    ├── a6bcf7c477c98011af4c8723575dd139b2cb94b8.nq.gz
    ├── a8e840f023777b9b72871a87e52d08ba06da511d.nq.gz
    ├── ab7f51751d7d031221dbd7d07045c555880bc849.nq.gz
    ├── aba25dcd43f8ebbde21a1c42b985a5552eda0e01.nq.gz
    ├── aba596a3b908424da250c2952a93994786a2b2d1.nq.gz
    ├── ace004ad9e10738eac3d26e571ae15b57df39ce2.nq.gz
    ├── ace6bd6c0de9cf18594ddeb7d08b89618e9d6d6f.nq.gz
    ├── aed3e85a0061b9412c012046473c4a5ab721a1d9.nq.gz
    ├── afbf0b507958c9487ee5c84a7ca2403f2fa9396b.nq.gz
    ├── b4325c7a7a7183cabbdf8de8259d311e38565a59.nq.gz
    ├── b486022b192d113fdbb326968a13e45fafaea396.nq.gz
    ├── b4bd6d62443577704c66411da964a6a725fa620f.nq.gz
    ├── b77ad4761bcc2a3b33f6af3c410bdd563d95ab5b.nq.gz
    ├── b7c2b9a74ec533400c062ed73ac50a957359e5f6.nq.gz
    ├── b7fb6daff4fa209fd9a04b147cf4a483f5fd97e7.nq.gz
    ├── b8cf6b7c67a59db26321bc7f8afda0ed38e81865.nq.gz
    ├── b9376cab1f5c448fbcca34a6ef93f368ecee2160.nq.gz
    ├── ba3f8052c8fdc14f60988d5cb98a4d173dfe6297.nq.gz
    ├── bafff6db47b4b85464ea1dca8e1416b5667ff82d.nq.gz
    ├── bc6f545e81c5be3ca8164569b8f5266e436b4794.nq.gz
    ├── bd08d63adc0749f86b8029659ba7a7ffb2d3dce1.nq.gz
    ├── be90f074b0f3c19761629c64e0a6b7ff1e242318.nq.gz
    ├── c23113504ede5a1102a030c7642fec6f9bd0e008.nq.gz
    ├── c368657b6b6b6497a27424cae961996aac6643ce.nq.gz
    ├── c7b45a2918e4c53246c1f051c59c753efdf94063.nq.gz
    ├── c98aa9d7c347e71b8d9ed26da5f4dbccda97b3c3.nq.gz
    ├── cab4529c15104cb9e63de017414ffd1e9ff96feb.nq.gz
    ├── cdf05b191cb5569a8597ac2d802b6896d939e9df.nq.gz
    ├── cee49589c0158d7d2b8e1bc64b23c8c70f08b86e.nq.gz
    ├── cf8ab9b760d0931cb079827a36d6a9f8a83caeeb.nq.gz
    ├── d18aa13493b50483e2d56c6b685c48601f01fa5e.nq.gz
    ├── d1a5d12d44b39e3155fa8162f352044b6f1252ab.nq.gz
    ├── d1ca304adb8c062db384a6762722239cde90663d.nq.gz
    ├── d378a3269473ad3cc4bc868d556afff87494ab61.nq.gz
    ├── d5a7f53069c4e8f9660e95b4a62a6a63611ce532.nq.gz
    ├── d708eae0616fde6f68b868d5ddd1b0d5f9db103c.nq.gz
    ├── d7ee177ce2ce5edfdeec635384e3cde3b12f72b2.nq.gz
    ├── d86cd229fe818bee14c206ebdaca61a8761eacde.nq.gz
    ├── dc64cb2793686bdeadf356442b6d1744b51b719a.nq.gz
    ├── dc6dfe60ef71a4798c71e69b7c7b8951af218416.nq.gz
    ├── de3b1f849dace43302cc47f72f2feb330ec4c6c9.nq.gz
    ├── de3da53f670f2da4339f503a05b77ab5e459eb23.nq.gz
    ├── de6444a2f44d19243f881d4e0de59f3e75bff7b4.nq.gz
    ├── df01fcf820c34be6b9147f3054315ab162b5cb4c.nq.gz
    ├── e0aaeb90e2a00d49a498c76d8ee58c3695463de6.nq.gz
    ├── e29cb479b452393b6fd01e1bf60f8d55354a173d.nq.gz
    ├── e3f9569510ec3d51b7065e3d8f9566b9999056d0.nq.gz
    ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
    ├── e7971c0662887e4a3f939b7b40d3e23ed37396c4.nq.gz
    ├── e899b36356f627ff361c3be58a8398e0a6f180b1.nq.gz
    └── ea23da3eef427adaa1491d0c70df7bbeadbbd2c6.nq.gz

7 directories, 200 files
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

[ansible-community/antsibull-nox](https://github.com/ansible-community/antsibull-nox)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
