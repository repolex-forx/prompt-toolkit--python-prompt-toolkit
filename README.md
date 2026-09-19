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
│   │   ├── 669541123c9a72da1fda662cbd0a18ffe9e6d113
│   │   │   └── chunk-001.nq.gz
│   │   ├── 6a58564f6a201f1234733f726d866a64e95b6ba3
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
│   │   ├── 669541123c9a72da1fda662cbd0a18ffe9e6d113.nq.gz
│   │   ├── 6a58564f6a201f1234733f726d866a64e95b6ba3.nq.gz
│   │   ├── 98659afe4de61732caa6987c3b6d7935235a0fad.nq.gz
│   │   ├── ace74dbc7b0c1e3e6fb4f3a238ed0b7f120f2c06.nq.gz
│   │   ├── d8adbe9bfcf5f7e95b015d8ab12e2985b9a7822b.nq.gz
│   │   └── d997aab538e434a6ca07d6bee226fd5b0628262f.nq.gz
│   └── repolex
│       ├── 165258d2f3ae594b50f16c7b50ffb06627476269
│       │   └── chunk-001.nq.gz
│       ├── 435bd99cf2abb229c13d5b1106467c7f6af599ed
│       │   └── chunk-001.nq.gz
│       ├── 669541123c9a72da1fda662cbd0a18ffe9e6d113
│       │   └── chunk-001.nq.gz
│       ├── 6a58564f6a201f1234733f726d866a64e95b6ba3
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
    ├── 01d10926a26bb5932e556aa9bc4766b5682ef9cf.nq.gz
    ├── 01dd1f79d6582442b0932a6a252585a5d85aa0a5.nq.gz
    ├── 02ca82d46ffaa67faa8581c16ac23cf71c40ce7d.nq.gz
    ├── 038823a5c7bdfb00ef33549a1698dc88bf7b5877.nq.gz
    ├── 0511daa03ca3e2070fe3f1c9174895d2d00d8494.nq.gz
    ├── 0543911e3285ee7f9e0fd763b8e0a56566bb538e.nq.gz
    ├── 054beb05147ad65606e965c1aeb18872d8859610.nq.gz
    ├── 0573ebef18ab795909dd9878396e5a1223509567.nq.gz
    ├── 057bc37f3779967caf7530c2b3a878c53815236c.nq.gz
    ├── 0590c815856a793c1cd4923ac036022ba2e58eea.nq.gz
    ├── 06287a080783301e4d2854ee70f50c5b04e2ed6d.nq.gz
    ├── 0651e7fa8b8c8c7eb197c2107d84d870d6199ac7.nq.gz
    ├── 06572210a9ecd93b8fc7715523472dea1efa5400.nq.gz
    ├── 069636b8c30ebfe5ba9ee1140db3b04c9613aa35.nq.gz
    ├── 08bb76287db45ea5d1dc00d656c0414578ae0d36.nq.gz
    ├── 093bbe0d020be667763a9f11fff019a0457c1689.nq.gz
    ├── 09dc43f854b3d87f5d95eac7900957c956f2015f.nq.gz
    ├── 0a0f016ffcedbaea75ac466b37d2c244438108cd.nq.gz
    ├── 0a212a96e21b27178213ac47aab5b05f7b743883.nq.gz
    ├── 0b09f2bc44096309539e6a60677960234f676dc9.nq.gz
    ├── 0b63c971f314be79afc09f52f1c01f3d23806e84.nq.gz
    ├── 0b9136b9bdcb8f3bcd52ae357663090a4520871b.nq.gz
    ├── 0bafa49eab71547708feaf1bc8ee41e061c52340.nq.gz
    ├── 0bb3f75154752510e213e04449575cc26a92c9e6.nq.gz
    ├── 0bc70ba25b18a2f989c6bb8755a3a5cdac491548.nq.gz
    ├── 0c9cc11bb3964834b787d2e262979519bff4f8c2.nq.gz
    ├── 0cd12c707e1bcc9eda099ee7c3ea77a75eb75049.nq.gz
    ├── 0ea059ebecc91f9bd5c2ba9d812ecd27ed52ba39.nq.gz
    ├── 0ef45d986d85745cf338c7c6ee700180a115c8ca.nq.gz
    ├── 0f19f52a8d5ea5a63ea824ec0735f9da53036f02.nq.gz
    ├── 0fce32cee219d21698a280c3095a2113ae9bcad9.nq.gz
    ├── 1044fb0f8539d5946826460d27cc06990fecef50.nq.gz
    ├── 10a8044c501b6681f980fe8382edf6f249cb0dd9.nq.gz
    ├── 10e45921e207e2ec3da2222c46c4f69f4cb5005f.nq.gz
    ├── 115d890075212dd19c69098e85cd6efa5501c43e.nq.gz
    ├── 1295e7d44d5f1626ef42a0fcd076a8fb87d9b035.nq.gz
    ├── 12cf2571cc44ac0c5f167dc728f044e14f7145d6.nq.gz
    ├── 1391c55b16aef8a16885a46774217c7b236e3dd9.nq.gz
    ├── 13b85048e50e89d3bfaa4076cb84bcf0f2261eee.nq.gz
    ├── 13e44ed4dc947fe7878731fd5063682bac46b281.nq.gz
    ├── 14e3f311beeaae1c80e7c60495fa80482508cd27.nq.gz
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
    ├── 1a99a2868a759f4bcff5abea34eac87abcef1e84.nq.gz
    ├── 1b7d9ec0205ed99528188c80cfaec034738c0aee.nq.gz
    ├── 1bff4baec22886c1a229b42326ffed15e2f8ab6f.nq.gz
    ├── 1c0cc4eec85384f555afd1163ed0922ef86b1129.nq.gz
    ├── 1c60880af917c3858afdb71b5f8b451bbba1f075.nq.gz
    ├── 1c6bb576ddb3432d0698ea7929a264e23c18fd11.nq.gz
    ├── 1e044679f0f0c19bb4aa8c1c605ebe8f58d6b95c.nq.gz
    ├── 1ee3e6c9bdd3474a2135522acd8e62b55d2bcfa1.nq.gz
    ├── 1f2b32979e4452f77c9fa317efed5133ca0f9bc8.nq.gz
    ├── 1f395cf435e7438795ebbc5b8372464812e12883.nq.gz
    ├── 1f4b11bdc0a3b1a54baabde80cb57e5bf70541f8.nq.gz
    ├── 1f5e18ea7867c0e07951ab4f53d8894db7f7c344.nq.gz
    ├── 1fba418b7376be59854f931babefbf2922e0e8c3.nq.gz
    ├── 1ff3234a398b581f0390c50dd8053aad9227f3b8.nq.gz
    ├── 202949ca07c96dfaff51884480d67ab769668389.nq.gz
    ├── 20619ac1fdd44ea923357f55266eba8c71b00e30.nq.gz
    ├── 207afba7ac6d0033e71877794ffcbb276a4e2ba3.nq.gz
    ├── 20c6caa0dc67d7f0dc0ad11811f4da329018faf8.nq.gz
    ├── 20e00ee09e3becc6d1e39621e63c1fac86ebe130.nq.gz
    ├── 21062a7d600a037e322f85cc1df0afa9d9484f1b.nq.gz
    ├── 21516718157ce2afc9378932204af72d7e33c32e.nq.gz
    ├── 22080c95b372e616726a53d0cd27bed7dbc86931.nq.gz
    ├── 2224bfcba94ab8c9b1c677d88eb055c69eda50a7.nq.gz
    ├── 222e471c5722e6d1d9df685e27dd18814df3e347.nq.gz
    ├── 2261a5b6e750f40401ceb3aeb8f6649265bb8396.nq.gz
    ├── 238f9084bee357b24cf384b0c66642f2d0fef8f9.nq.gz
    ├── 24aa3ce39ba798d47668212fa1c6a7afed069032.nq.gz
    ├── 24e1a479ce5ef164953a2212c8d8af790628d201.nq.gz
    ├── 254d226d9d9d6f2ffa608872f89bb0e41defe1a0.nq.gz
    ├── 25ea8923a30332ef835555a58914048c5377b685.nq.gz
    ├── 2699554d01ad6b9c6bd8e0aa27de61175b398293.nq.gz
    ├── 26b8685b0ae75d7ac05bf4d99be4c44e91a51de1.nq.gz
    ├── 272823232b4ec2e036b8025b748a19c3257223f9.nq.gz
    ├── 27dd4585438eab2a684375604db6a765617b03b4.nq.gz
    ├── 285357927ad9eb15e753bbe90445e798e94f7b99.nq.gz
    ├── 287c6d33a606ed26ece5b4906ce5654ea60db625.nq.gz
    ├── 28cfdcd7664253af28c10d0388acd2a60b7f7950.nq.gz
    ├── 2ac30b538e4fe6ef94e5e21ad7ea9ed398ffc14d.nq.gz
    ├── 2b35d1fcc91873a9b8242495301854b0cb81e6a4.nq.gz
    ├── 2b7e596e468a63b8a763716a2472560466faf74a.nq.gz
    ├── 2c3b6028b7c60ad8b4c2873956b2c469b41579ce.nq.gz
    ├── 2c7bcc15d34c9d841458fd02668e0d30ffd46ac9.nq.gz
    ├── 2d497a0209c4047ef2170ab992d8c299f7267822.nq.gz
    ├── 2e124056ba211e0252cd44e2d16691487b04e398.nq.gz
    ├── 2e6f5dd4eb1f55ed3fd0ab9821e6d6e60e380a07.nq.gz
    ├── 2f4b66f399adaece1b455b081932f457033c2e7a.nq.gz
    ├── 2faba94378ef30cb47781ccaa6176992361b8d58.nq.gz
    ├── 2febdf1de5a3d74b90a9e933e8eed74a27801bd8.nq.gz
    ├── 3040b5f2e7f9b5c35a405a6c1cb132eda86defc8.nq.gz
    ├── 310f0761ecc6a988cf4b11f41e7a8f70f2736c44.nq.gz
    ├── 3126d268655536a7f5d0773e5f69d9c2dd6877d9.nq.gz
    ├── 313836137c939febd86fdf710935850f4e03de4c.nq.gz
    ├── 31ea7c8ce82fe3e7112ec575ef7eadebc2588dc0.nq.gz
    ├── 322d7c0d72fe8d516775ecc21a1c92110727228d.nq.gz
    ├── 32a1481d99659a2594267fad65532acca1e9bf25.nq.gz
    ├── 32e5f88247ea7a5654419719a9af81f506f29399.nq.gz
    ├── 337ddba0f51ea66d83657cfcf4dc1c4e69b21fce.nq.gz
    ├── 353e54ff726e7a5d16bec7a0d50d828eb7880b1e.nq.gz
    ├── 36bdf6a14dc820f727ec637bb40ff0a925466e06.nq.gz
    ├── 373fe52a5ae5ab927faad014cfcdeb50b401ffae.nq.gz
    ├── 3846ef756264eccd0c35e79e42cbf2a7662d5129.nq.gz
    ├── 38b027cd16f7a230b56a3375d70351ace31b6b9b.nq.gz
    ├── 39e97cac8ef0099f7beb9f408c2404ed8da4a8f7.nq.gz
    ├── 3a89f36508ceb02f1a21fed481df8ce6bae16367.nq.gz
    ├── 3aa5f70d69a228ceee99a0310dd005a64b2b5129.nq.gz
    ├── 3ac08c017216d4f35ac4ffc3b81a3cedf7215056.nq.gz
    ├── 3c692440143c9fc315b7e7940ae546c54b3914c9.nq.gz
    ├── 3d5227bc6d6d751cd44a1d4c225cb8811838ea45.nq.gz
    ├── 3d55dbc514dbfb3a3f18645377261cf7e9688ce4.nq.gz
    ├── 3dcb994bd95b4e7ed333374364e37cc7c0793110.nq.gz
    ├── 3f7eb4bd46c9905fd5f001b99321cc9436d7895f.nq.gz
    ├── 3f92303a819ce65535c8b7ff80d7993145c78d3d.nq.gz
    ├── 40016e87f6b5e5f0210c5c5c3eee198909bfaaee.nq.gz
    ├── 4009d54f2dc27e36bdd4d7469c0b368f19257c7b.nq.gz
    ├── 4073bcdd2bc1e3163c1dc0c377db4ca17b4bca32.nq.gz
    ├── 40b6917f764c52bb56e0a58f938a9f07e0b442bc.nq.gz
    ├── 40ffd9df2083e98550a675c05e49583897b7a98b.nq.gz
    ├── 410749db47532ed81b04d798e3b8e9e0163e8aca.nq.gz
    ├── 4237d73212da8539be874fdc9b49fe2692174818.nq.gz
    ├── 428ff1dd0c1f031e099e892f47601d5b2bf9a3bc.nq.gz
    ├── 43228c3cda170e0eef6d7ac7f4b976152a5b5b3c.nq.gz
    ├── 43603eba1071793b9b0b545fe8420863373de8ed.nq.gz
    ├── 43819e1e71cafc0ed18740b9d6472bd6d187eeba.nq.gz
    ├── 453b72c3cb9f33e47b9f196c72dc2f87a6c9d313.nq.gz
    ├── 475f540d11d8e5b8ff1567d5120e25c9667cc33e.nq.gz
    ├── 4761982ab38ade4de833bd69998e07aaff1abdf6.nq.gz
    ├── 476dffc677489ca02d63ffbc2743f451cce44dc2.nq.gz
    ├── 4788769f96b7f0593b694db47c08baa972deb6cf.nq.gz
    ├── 47b023826c7fd9102ce1c41c4cc6b941dc9d8520.nq.gz
    ├── 483eeb2092e48119776b341da92d66e2f549abbf.nq.gz
    ├── 4958e9d2e4fc9a19ca37701e6acbf3484b64e744.nq.gz
    ├── 49e5ac4ea9b3a7080f99c2bbccf0aafb552c743b.nq.gz
    ├── 4a78dc421b75620c1ed8ae9f0aba254555535a8c.nq.gz
    ├── 4b24ad960e4f2359e0363a216ad91a00d2910d24.nq.gz
    ├── 4badc6cad04b6144b7ff32a1f88b54b9e4bbedd4.nq.gz
    ├── 4c4fcc9cac4b726de95438c95592a7a8423c713f.nq.gz
    ├── 4d79c2b8069879c6dd6dd1f51a39c1caf4ff8471.nq.gz
    ├── 4debd27ce97b36b2c6a044f17e269e7440b84512.nq.gz
    ├── 4edb74d6cfda45d42fd15f0be96bf8f0958e6d1d.nq.gz
    ├── 500b7f119a7f857d53e4c48091902567d02fdcdd.nq.gz
    ├── 5083c8286d4cb5b204a6ca92d10a5aadcda1fec7.nq.gz
    ├── 50b69359cc7d1372c9289d69f256540d37f8a8f8.nq.gz
    ├── 5248f984361e941b11fba13c124f7231113ba871.nq.gz
    ├── 52deac14560168f53d11d0af39dc1d1f93fb3724.nq.gz
    ├── 53cc3e1394544e614cf1f930844c3e1267f8d221.nq.gz
    ├── 5531ace4d504630e4251e36a0ec97a7bc7c6809c.nq.gz
    ├── 556ed8846b84ad636e58e26621b24e98a103e685.nq.gz
    ├── 55cf6ee0eae7a7db1cbac1847056608f2599953f.nq.gz
    ├── 569d8c094aa692fcf22fb3acf0d477c39b7c1e70.nq.gz
    ├── 569e14ccfee04929f33d7a7e7b0154f9b64d687e.nq.gz
    ├── 56a0c7da409dbd9a3f5fa7878e6f574192c4b36a.nq.gz
    ├── 56a9dc69b3c089b8923c153d7eb76c4f04b89d4f.nq.gz
    ├── 56c27487b401e29573d9a2d5d8949a3648499970.nq.gz
    ├── 57826b9409fcf3691a6191b803ef519ec0351ed9.nq.gz
    ├── 58286e23e77b2dead0081c938fe813dcbd7aaa70.nq.gz
    ├── 588791fe176e3e06946917e8cde5e5102f473009.nq.gz
    ├── 5a12c897744cc203a7da316b61c74054e779d8b0.nq.gz
    ├── 5aaf98361c65ca693bb7c00b8861e44d6b7b00e8.nq.gz
    ├── 5be702a1e58fc887cb2cd3da6d04c7e03646b196.nq.gz
    ├── 5c24cf287b6cdda563201567002ea1af4c447aa0.nq.gz
    ├── 5ca197f5c8acd826b3a67d4dd331a8396c7cfd47.nq.gz
    ├── 5d2d06fdc07df40dc8c51cdc8cced66e272e285e.nq.gz
    └── 5d90d444d87e8058c6dd0155c76ced4cf5a35a1d.nq.gz

22 directories, 200 files
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
