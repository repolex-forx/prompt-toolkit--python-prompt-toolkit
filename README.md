# Repolex Knowledge Graph of prompt-toolkit/python-prompt-toolkit

RDF knowledge graph data for [prompt-toolkit/python-prompt-toolkit](https://github.com/prompt-toolkit/python-prompt-toolkit), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download prompt-toolkit/python-prompt-toolkit
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 165258d2f3ae594b50f16c7b50ffb06627476269
│   │   │   └── chunk-001.nq.gz
│   │   ├── 435bd99cf2abb229c13d5b1106467c7f6af599ed
│   │   │   └── chunk-001.nq.gz
│   │   ├── 4432d6233fd8e0efba5920a9650e515f54a20300
│   │   │   └── chunk-001.nq.gz
│   │   ├── 669541123c9a72da1fda662cbd0a18ffe9e6d113
│   │   │   └── chunk-001.nq.gz
│   │   ├── 6a58564f6a201f1234733f726d866a64e95b6ba3
│   │   │   └── chunk-001.nq.gz
│   │   ├── 81dcfdafb8be17bb471ce979e870bd3220844390
│   │   │   └── chunk-001.nq.gz
│   │   ├── 87d01078cae7f560b241af7cc0b50cc72dfacd26
│   │   │   └── chunk-001.nq.gz
│   │   ├── 98659afe4de61732caa6987c3b6d7935235a0fad
│   │   │   └── chunk-001.nq.gz
│   │   ├── ace74dbc7b0c1e3e6fb4f3a238ed0b7f120f2c06
│   │   │   └── chunk-001.nq.gz
│   │   ├── d8adbe9bfcf5f7e95b015d8ab12e2985b9a7822b
│   │   │   └── chunk-001.nq.gz
│   │   └── d997aab538e434a6ca07d6bee226fd5b0628262f
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 165258d2f3ae594b50f16c7b50ffb06627476269.nq.gz
│   │   ├── 435bd99cf2abb229c13d5b1106467c7f6af599ed.nq.gz
│   │   ├── 4432d6233fd8e0efba5920a9650e515f54a20300.nq.gz
│   │   ├── 669541123c9a72da1fda662cbd0a18ffe9e6d113.nq.gz
│   │   ├── 6a58564f6a201f1234733f726d866a64e95b6ba3.nq.gz
│   │   ├── 81dcfdafb8be17bb471ce979e870bd3220844390.nq.gz
│   │   ├── 87d01078cae7f560b241af7cc0b50cc72dfacd26.nq.gz
│   │   ├── 98659afe4de61732caa6987c3b6d7935235a0fad.nq.gz
│   │   ├── ace74dbc7b0c1e3e6fb4f3a238ed0b7f120f2c06.nq.gz
│   │   ├── d8adbe9bfcf5f7e95b015d8ab12e2985b9a7822b.nq.gz
│   │   └── d997aab538e434a6ca07d6bee226fd5b0628262f.nq.gz
│   └── repolex
│       ├── 165258d2f3ae594b50f16c7b50ffb06627476269
│       │   └── chunk-001.nq.gz
│       ├── 435bd99cf2abb229c13d5b1106467c7f6af599ed
│       │   └── chunk-001.nq.gz
│       ├── 4432d6233fd8e0efba5920a9650e515f54a20300
│       │   └── chunk-001.nq.gz
│       ├── 669541123c9a72da1fda662cbd0a18ffe9e6d113
│       │   └── chunk-001.nq.gz
│       ├── 6a58564f6a201f1234733f726d866a64e95b6ba3
│       │   └── chunk-001.nq.gz
│       ├── 81dcfdafb8be17bb471ce979e870bd3220844390
│       │   └── chunk-001.nq.gz
│       ├── 87d01078cae7f560b241af7cc0b50cc72dfacd26
│       │   └── chunk-001.nq.gz
│       ├── 98659afe4de61732caa6987c3b6d7935235a0fad
│       │   └── chunk-001.nq.gz
│       ├── ace74dbc7b0c1e3e6fb4f3a238ed0b7f120f2c06
│       │   └── chunk-001.nq.gz
│       ├── d8adbe9bfcf5f7e95b015d8ab12e2985b9a7822b
│       │   └── chunk-001.nq.gz
│       └── d997aab538e434a6ca07d6bee226fd5b0628262f
│           └── chunk-001.nq.gz
└── blob
    ├── 006baccd15fbd149e37b80d8d316f8f24ee69a48.nq.gz
    ├── 007bdb6ff9462afecc9009dfffb591bd5a354c34.nq.gz
    ├── 016821f492e91608b5f7e41b91129fd8c79e995c.nq.gz
    ├── 01d10926a26bb5932e556aa9bc4766b5682ef9cf.nq.gz
    ├── 01dd1f79d6582442b0932a6a252585a5d85aa0a5.nq.gz
    ├── 02ca82d46ffaa67faa8581c16ac23cf71c40ce7d.nq.gz
    ├── 038823a5c7bdfb00ef33549a1698dc88bf7b5877.nq.gz
    ├── 0395c8bc59d5b576dfe99eb5dc6edab82da99fe0.nq.gz
    ├── 0427e67afc8d689f423fee38114bb54015cfeba0.nq.gz
    ├── 04a712df7ede08d795c143869bc6c5c45af15a03.nq.gz
    ├── 0511daa03ca3e2070fe3f1c9174895d2d00d8494.nq.gz
    ├── 0543911e3285ee7f9e0fd763b8e0a56566bb538e.nq.gz
    ├── 054aa4439afb2433a60e956cd102c7f0bdac680c.nq.gz
    ├── 054beb05147ad65606e965c1aeb18872d8859610.nq.gz
    ├── 0573ebef18ab795909dd9878396e5a1223509567.nq.gz
    ├── 057bc37f3779967caf7530c2b3a878c53815236c.nq.gz
    ├── 0590c815856a793c1cd4923ac036022ba2e58eea.nq.gz
    ├── 06287a080783301e4d2854ee70f50c5b04e2ed6d.nq.gz
    ├── 0651e7fa8b8c8c7eb197c2107d84d870d6199ac7.nq.gz
    ├── 06572210a9ecd93b8fc7715523472dea1efa5400.nq.gz
    ├── 069636b8c30ebfe5ba9ee1140db3b04c9613aa35.nq.gz
    ├── 084548d6669c195c27eab74b6d7e6361384b997d.nq.gz
    ├── 08bb76287db45ea5d1dc00d656c0414578ae0d36.nq.gz
    ├── 08ec0b322eb2061214fc7e8d103e82fed6a1f657.nq.gz
    ├── 093bbe0d020be667763a9f11fff019a0457c1689.nq.gz
    ├── 09dc43f854b3d87f5d95eac7900957c956f2015f.nq.gz
    ├── 0a0f016ffcedbaea75ac466b37d2c244438108cd.nq.gz
    ├── 0a212a96e21b27178213ac47aab5b05f7b743883.nq.gz
    ├── 0b09f2bc44096309539e6a60677960234f676dc9.nq.gz
    ├── 0b5e73a225ab5d6e3fac32876e08908a86e0ce99.nq.gz
    ├── 0b63c971f314be79afc09f52f1c01f3d23806e84.nq.gz
    ├── 0b9136b9bdcb8f3bcd52ae357663090a4520871b.nq.gz
    ├── 0bafa49eab71547708feaf1bc8ee41e061c52340.nq.gz
    ├── 0bb3f75154752510e213e04449575cc26a92c9e6.nq.gz
    ├── 0bc70ba25b18a2f989c6bb8755a3a5cdac491548.nq.gz
    ├── 0c9cc11bb3964834b787d2e262979519bff4f8c2.nq.gz
    ├── 0cd12c707e1bcc9eda099ee7c3ea77a75eb75049.nq.gz
    ├── 0d45be9e5e2b3059275927aa1f719b109dcac907.nq.gz
    ├── 0e66e9007392afa9ec8361fca98a8d551c6118b1.nq.gz
    ├── 0ea059ebecc91f9bd5c2ba9d812ecd27ed52ba39.nq.gz
    ├── 0ef45d986d85745cf338c7c6ee700180a115c8ca.nq.gz
    ├── 0f19f52a8d5ea5a63ea824ec0735f9da53036f02.nq.gz
    ├── 0f78f3713c497cbc5cb16333ba0fbbd3e04b1270.nq.gz
    ├── 0fce32cee219d21698a280c3095a2113ae9bcad9.nq.gz
    ├── 0fe843375c053db6e7ee8b8e9469b7ec06f79a46.nq.gz
    ├── 100ca78d7b0c79d7c1e91b84928ae7c54a9c36ed.nq.gz
    ├── 100d4aaebca8ccc1a413c65c08cbd9f90cdfce1f.nq.gz
    ├── 1044fb0f8539d5946826460d27cc06990fecef50.nq.gz
    ├── 10a8044c501b6681f980fe8382edf6f249cb0dd9.nq.gz
    ├── 10e45921e207e2ec3da2222c46c4f69f4cb5005f.nq.gz
    ├── 115d890075212dd19c69098e85cd6efa5501c43e.nq.gz
    ├── 126e02752322cafc1c7c25a686a786eddc001cb9.nq.gz
    ├── 127445e86e03807c596e96a4cd06c202656dcd41.nq.gz
    ├── 1295e7d44d5f1626ef42a0fcd076a8fb87d9b035.nq.gz
    ├── 12cf2571cc44ac0c5f167dc728f044e14f7145d6.nq.gz
    ├── 1391c55b16aef8a16885a46774217c7b236e3dd9.nq.gz
    ├── 139f31157900d4c9e3bce28cd459a374f2e168a0.nq.gz
    ├── 13b85048e50e89d3bfaa4076cb84bcf0f2261eee.nq.gz
    ├── 13e44ed4dc947fe7878731fd5063682bac46b281.nq.gz
    ├── 142deab0774c277d021e939e1d2770a19c45dcb3.nq.gz
    ├── 1475d71228043cbdc4b36b1223161a826b493b45.nq.gz
    ├── 14e3f311beeaae1c80e7c60495fa80482508cd27.nq.gz
    ├── 14f945999c6bf5ecd404a98d7e5eefa722275011.nq.gz
    ├── 15c57d435584f9f25a473370fe3050c484850c71.nq.gz
    ├── 166da8d4accd2ec690fc92252530ee296b4394e8.nq.gz
    ├── 16c1bf55852f6498c84a7a1b179968b7952b1110.nq.gz
    ├── 170e7d53c813f7a006f0de75545152f60c5f0db1.nq.gz
    ├── 172fe6f56774ae85437722ce1002f9b92e7089ea.nq.gz
    ├── 17e69c9e64ce5f9ebeb41fc4c853572c026a0c5b.nq.gz
    ├── 17e7e1f92543e5ffa12e3538058d2fe78cf139e4.nq.gz
    ├── 184b9973902f004682361b54e1379ac0095f8812.nq.gz
    ├── 18687fe6c4117695e8921cd948934196d0c6d01c.nq.gz
    ├── 18a3dadeb9cce29a5ec42617e27f644c610db30c.nq.gz
    ├── 18ae02283279ecd9f01ff1902ff13acbeaeb7098.nq.gz
    ├── 19ebaad9389064dec387d0b325f4a310aee21c8f.nq.gz
    ├── 1a1e70615ad7835281e9a291ddbf90467141e04b.nq.gz
    ├── 1a616a636ce772a82eccd2e5ffd9691c90b5f453.nq.gz
    ├── 1a99a2868a759f4bcff5abea34eac87abcef1e84.nq.gz
    ├── 1abee0f53bd469fa998e6457ffe62b89c4dc40f6.nq.gz
    ├── 1b7d9ec0205ed99528188c80cfaec034738c0aee.nq.gz
    ├── 1bff4baec22886c1a229b42326ffed15e2f8ab6f.nq.gz
    ├── 1c0cc4eec85384f555afd1163ed0922ef86b1129.nq.gz
    ├── 1c60880af917c3858afdb71b5f8b451bbba1f075.nq.gz
    ├── 1c6bb576ddb3432d0698ea7929a264e23c18fd11.nq.gz
    ├── 1c83524d8dd1d65148d028161693e73212105b11.nq.gz
    ├── 1c9517c60f033995da6078eba13f5b20a24322fa.nq.gz
    ├── 1cb513fc6adb56defe398823b736fe6dff297a5f.nq.gz
    ├── 1e044679f0f0c19bb4aa8c1c605ebe8f58d6b95c.nq.gz
    ├── 1e4da2d9cb270f675bf25d17a8559c56c7002433.nq.gz
    ├── 1e4ee76005b8fbb6d6d37525976360d5e1c56260.nq.gz
    ├── 1e63e296b1e9b16de650a8f20bd9f69e953f93c1.nq.gz
    ├── 1e8a43266b2fd7987f0a685770a8fd633dc49d22.nq.gz
    ├── 1ee3e6c9bdd3474a2135522acd8e62b55d2bcfa1.nq.gz
    ├── 1f2b32979e4452f77c9fa317efed5133ca0f9bc8.nq.gz
    ├── 1f395cf435e7438795ebbc5b8372464812e12883.nq.gz
    ├── 1f4b11bdc0a3b1a54baabde80cb57e5bf70541f8.nq.gz
    ├── 1f5e18ea7867c0e07951ab4f53d8894db7f7c344.nq.gz
    ├── 1fba418b7376be59854f931babefbf2922e0e8c3.nq.gz
    ├── 1fd3ffbadbe4d8a39c8764776c1f18a77f430e3e.nq.gz
    ├── 1ff3234a398b581f0390c50dd8053aad9227f3b8.nq.gz
    ├── 202949ca07c96dfaff51884480d67ab769668389.nq.gz
    ├── 20619ac1fdd44ea923357f55266eba8c71b00e30.nq.gz
    ├── 207afba7ac6d0033e71877794ffcbb276a4e2ba3.nq.gz
    ├── 20c6caa0dc67d7f0dc0ad11811f4da329018faf8.nq.gz
    ├── 20e00ee09e3becc6d1e39621e63c1fac86ebe130.nq.gz
    ├── 21062a7d600a037e322f85cc1df0afa9d9484f1b.nq.gz
    ├── 21516718157ce2afc9378932204af72d7e33c32e.nq.gz
    ├── 2158fa92a2baa8b00e21646c97902c9256dbcffb.nq.gz
    ├── 21aa1bece5aa19f0b3ff6a042b28ad8e30a09bed.nq.gz
    ├── 22080c95b372e616726a53d0cd27bed7dbc86931.nq.gz
    ├── 2224bfcba94ab8c9b1c677d88eb055c69eda50a7.nq.gz
    ├── 222e471c5722e6d1d9df685e27dd18814df3e347.nq.gz
    ├── 224b195c57ca58befcbcf90a712c886430b35955.nq.gz
    ├── 2261a5b6e750f40401ceb3aeb8f6649265bb8396.nq.gz
    ├── 238f9084bee357b24cf384b0c66642f2d0fef8f9.nq.gz
    ├── 23f61bb0f6564db70895bd423fe06b3d24c487c3.nq.gz
    ├── 249c7efd573cf948800db0e585dc83ee4744361c.nq.gz
    ├── 24aa3ce39ba798d47668212fa1c6a7afed069032.nq.gz
    ├── 24e1a479ce5ef164953a2212c8d8af790628d201.nq.gz
    ├── 254d226d9d9d6f2ffa608872f89bb0e41defe1a0.nq.gz
    ├── 25ea8923a30332ef835555a58914048c5377b685.nq.gz
    ├── 2699554d01ad6b9c6bd8e0aa27de61175b398293.nq.gz
    ├── 26b8685b0ae75d7ac05bf4d99be4c44e91a51de1.nq.gz
    ├── 26c72651518b0a4781c68a3cef3b5c7f99c3da2f.nq.gz
    ├── 272823232b4ec2e036b8025b748a19c3257223f9.nq.gz
    ├── 277f428ee9b16db8aafe23db1ef74783716b13c3.nq.gz
    ├── 27d0dd22cc9deecf1b6ca84c039d96f98014b83e.nq.gz
    ├── 27dd4585438eab2a684375604db6a765617b03b4.nq.gz
    ├── 285357927ad9eb15e753bbe90445e798e94f7b99.nq.gz
    ├── 287c6d33a606ed26ece5b4906ce5654ea60db625.nq.gz
    ├── 28cfdcd7664253af28c10d0388acd2a60b7f7950.nq.gz
    ├── 2ac30b538e4fe6ef94e5e21ad7ea9ed398ffc14d.nq.gz
    ├── 2b35d1fcc91873a9b8242495301854b0cb81e6a4.nq.gz
    ├── 2b7e596e468a63b8a763716a2472560466faf74a.nq.gz
    ├── 2bdb7587f425c41d27054391cb00a6b8fe024e7e.nq.gz
    ├── 2c2ccb6436e93a6450e32303f59a9ed895ec3917.nq.gz
    ├── 2c3b6028b7c60ad8b4c2873956b2c469b41579ce.nq.gz
    ├── 2c7bcc15d34c9d841458fd02668e0d30ffd46ac9.nq.gz
    ├── 2d497a0209c4047ef2170ab992d8c299f7267822.nq.gz
    ├── 2e124056ba211e0252cd44e2d16691487b04e398.nq.gz
    ├── 2e3508d44e4de08b8a178c04e06969d4715b7870.nq.gz
    ├── 2e353e8d5aac180808fd5f3951081bc8833a2e36.nq.gz
    ├── 2e6f5dd4eb1f55ed3fd0ab9821e6d6e60e380a07.nq.gz
    ├── 2f4b66f399adaece1b455b081932f457033c2e7a.nq.gz
    ├── 2faba94378ef30cb47781ccaa6176992361b8d58.nq.gz
    ├── 2febdf1de5a3d74b90a9e933e8eed74a27801bd8.nq.gz
    ├── 30106153e4a5dfc44df91864d38328a79cc88b1e.nq.gz
    ├── 3040b5f2e7f9b5c35a405a6c1cb132eda86defc8.nq.gz
    ├── 30c7a7fb33e98ea2396aff8393e6c39a283ec773.nq.gz
    ├── 310f0761ecc6a988cf4b11f41e7a8f70f2736c44.nq.gz
    ├── 31110ac096f5c5d9c5e5606996a808e1bb4c3e1b.nq.gz
    ├── 311ef46c96fc694cfdc51aa5185b3134d5773368.nq.gz
    ├── 3126d268655536a7f5d0773e5f69d9c2dd6877d9.nq.gz
    ├── 313836137c939febd86fdf710935850f4e03de4c.nq.gz
    ├── 31ea7c8ce82fe3e7112ec575ef7eadebc2588dc0.nq.gz
    ├── 322d7c0d72fe8d516775ecc21a1c92110727228d.nq.gz
    ├── 329c0c1e367f62b6eb7ecc081672fa116dfa38dd.nq.gz
    ├── 32a1481d99659a2594267fad65532acca1e9bf25.nq.gz
    ├── 32d889ede04786c3788a3cdb6465e26b02676018.nq.gz
    ├── 32e5f88247ea7a5654419719a9af81f506f29399.nq.gz
    ├── 337ddba0f51ea66d83657cfcf4dc1c4e69b21fce.nq.gz
    ├── 3470e8ee0013eade448c4c14fa99d84204e69919.nq.gz
    ├── 353e54ff726e7a5d16bec7a0d50d828eb7880b1e.nq.gz
    ├── 35e1c6c5c9d2d1f12d7aa19745d592cf9f239f45.nq.gz
    ├── 35e8948d2289c31aa076e8ccae6c7e7fb68bb809.nq.gz
    ├── 36bdf6a14dc820f727ec637bb40ff0a925466e06.nq.gz
    └── 371486ea66e13243e6c3095a6e64a275820f9bd7.nq.gz

28 directories, 200 files
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

## Source repository

[prompt-toolkit/python-prompt-toolkit](https://github.com/prompt-toolkit/python-prompt-toolkit)

---
*Parsed on 2026-09-19 by [repolex](https://repolex.ai)*
