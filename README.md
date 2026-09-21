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
│   │   ├── 1ff655110b93994d3835b3f5bcfb0eb04d2124d9
│   │   │   └── chunk-001.nq.gz
│   │   ├── 2d816ff79fdd1e973f580c29321fdb22fce9de6b
│   │   │   └── chunk-001.nq.gz
│   │   ├── 435bd99cf2abb229c13d5b1106467c7f6af599ed
│   │   │   └── chunk-001.nq.gz
│   │   ├── 4432d6233fd8e0efba5920a9650e515f54a20300
│   │   │   └── chunk-001.nq.gz
│   │   ├── 490cf900188df357611cdc9358256be0e5ce2e16
│   │   │   └── chunk-001.nq.gz
│   │   ├── 5e11c13f37be3e3e6397fa1aadcf8d397dacd8ee
│   │   │   └── chunk-001.nq.gz
│   │   ├── 669541123c9a72da1fda662cbd0a18ffe9e6d113
│   │   │   └── chunk-001.nq.gz
│   │   ├── 6a58564f6a201f1234733f726d866a64e95b6ba3
│   │   │   └── chunk-001.nq.gz
│   │   ├── 6bdcb9d7e33ab25b665ea9b5ba373471737b1db2
│   │   │   └── chunk-001.nq.gz
│   │   ├── 81dcfdafb8be17bb471ce979e870bd3220844390
│   │   │   └── chunk-001.nq.gz
│   │   ├── 87d01078cae7f560b241af7cc0b50cc72dfacd26
│   │   │   └── chunk-001.nq.gz
│   │   ├── 960df477c31adf53a3fff98a5c212c71fbfd7a3e
│   │   │   └── chunk-001.nq.gz
│   │   ├── 98659afe4de61732caa6987c3b6d7935235a0fad
│   │   │   └── chunk-001.nq.gz
│   │   ├── 9a2a550f4537f2d11cac7b902ec36e376c4131bd
│   │   │   └── chunk-001.nq.gz
│   │   ├── ace74dbc7b0c1e3e6fb4f3a238ed0b7f120f2c06
│   │   │   └── chunk-001.nq.gz
│   │   ├── b1cb8fad68844495a219afc8747a1efc89eb17dc
│   │   │   └── chunk-001.nq.gz
│   │   ├── b6a9f05f9a71f82785a4d2ba99bd12a7072744e1
│   │   │   └── chunk-001.nq.gz
│   │   ├── d8adbe9bfcf5f7e95b015d8ab12e2985b9a7822b
│   │   │   └── chunk-001.nq.gz
│   │   ├── d997aab538e434a6ca07d6bee226fd5b0628262f
│   │   │   └── chunk-001.nq.gz
│   │   ├── da05f669d00817655f76b82972272d4d5f4d4225
│   │   │   └── chunk-001.nq.gz
│   │   ├── e64c7409d7c1c667cfaafc9976bff2ade6d514f4
│   │   │   └── chunk-001.nq.gz
│   │   ├── f07b6a0673c198588fa06edf9d0ae1b6d81cd233
│   │   │   └── chunk-001.nq.gz
│   │   └── f3088dc4b19148f378e458249a50b020d4fe7a04
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 165258d2f3ae594b50f16c7b50ffb06627476269.nq.gz
│   │   ├── 1ff655110b93994d3835b3f5bcfb0eb04d2124d9.nq.gz
│   │   ├── 2d816ff79fdd1e973f580c29321fdb22fce9de6b.nq.gz
│   │   ├── 435bd99cf2abb229c13d5b1106467c7f6af599ed.nq.gz
│   │   ├── 4432d6233fd8e0efba5920a9650e515f54a20300.nq.gz
│   │   ├── 490cf900188df357611cdc9358256be0e5ce2e16.nq.gz
│   │   ├── 5e11c13f37be3e3e6397fa1aadcf8d397dacd8ee.nq.gz
│   │   ├── 669541123c9a72da1fda662cbd0a18ffe9e6d113.nq.gz
│   │   ├── 6a58564f6a201f1234733f726d866a64e95b6ba3.nq.gz
│   │   ├── 6bdcb9d7e33ab25b665ea9b5ba373471737b1db2.nq.gz
│   │   ├── 81dcfdafb8be17bb471ce979e870bd3220844390.nq.gz
│   │   ├── 87d01078cae7f560b241af7cc0b50cc72dfacd26.nq.gz
│   │   ├── 960df477c31adf53a3fff98a5c212c71fbfd7a3e.nq.gz
│   │   ├── 98659afe4de61732caa6987c3b6d7935235a0fad.nq.gz
│   │   ├── 9a2a550f4537f2d11cac7b902ec36e376c4131bd.nq.gz
│   │   ├── ace74dbc7b0c1e3e6fb4f3a238ed0b7f120f2c06.nq.gz
│   │   ├── b1cb8fad68844495a219afc8747a1efc89eb17dc.nq.gz
│   │   ├── b6a9f05f9a71f82785a4d2ba99bd12a7072744e1.nq.gz
│   │   ├── d8adbe9bfcf5f7e95b015d8ab12e2985b9a7822b.nq.gz
│   │   ├── d997aab538e434a6ca07d6bee226fd5b0628262f.nq.gz
│   │   ├── da05f669d00817655f76b82972272d4d5f4d4225.nq.gz
│   │   ├── e64c7409d7c1c667cfaafc9976bff2ade6d514f4.nq.gz
│   │   ├── f07b6a0673c198588fa06edf9d0ae1b6d81cd233.nq.gz
│   │   └── f3088dc4b19148f378e458249a50b020d4fe7a04.nq.gz
│   └── repolex
│       ├── 165258d2f3ae594b50f16c7b50ffb06627476269
│       │   └── chunk-001.nq.gz
│       ├── 1ff655110b93994d3835b3f5bcfb0eb04d2124d9
│       │   └── chunk-001.nq.gz
│       ├── 2d816ff79fdd1e973f580c29321fdb22fce9de6b
│       │   └── chunk-001.nq.gz
│       ├── 435bd99cf2abb229c13d5b1106467c7f6af599ed
│       │   └── chunk-001.nq.gz
│       ├── 4432d6233fd8e0efba5920a9650e515f54a20300
│       │   └── chunk-001.nq.gz
│       ├── 490cf900188df357611cdc9358256be0e5ce2e16
│       │   └── chunk-001.nq.gz
│       ├── 5e11c13f37be3e3e6397fa1aadcf8d397dacd8ee
│       │   └── chunk-001.nq.gz
│       ├── 669541123c9a72da1fda662cbd0a18ffe9e6d113
│       │   └── chunk-001.nq.gz
│       ├── 6a58564f6a201f1234733f726d866a64e95b6ba3
│       │   └── chunk-001.nq.gz
│       ├── 6bdcb9d7e33ab25b665ea9b5ba373471737b1db2
│       │   └── chunk-001.nq.gz
│       ├── 81dcfdafb8be17bb471ce979e870bd3220844390
│       │   └── chunk-001.nq.gz
│       ├── 87d01078cae7f560b241af7cc0b50cc72dfacd26
│       │   └── chunk-001.nq.gz
│       ├── 960df477c31adf53a3fff98a5c212c71fbfd7a3e
│       │   └── chunk-001.nq.gz
│       ├── 98659afe4de61732caa6987c3b6d7935235a0fad
│       │   └── chunk-001.nq.gz
│       ├── 9a2a550f4537f2d11cac7b902ec36e376c4131bd
│       │   └── chunk-001.nq.gz
│       ├── ace74dbc7b0c1e3e6fb4f3a238ed0b7f120f2c06
│       │   └── chunk-001.nq.gz
│       ├── b1cb8fad68844495a219afc8747a1efc89eb17dc
│       │   └── chunk-001.nq.gz
│       ├── b6a9f05f9a71f82785a4d2ba99bd12a7072744e1
│       │   └── chunk-001.nq.gz
│       ├── d8adbe9bfcf5f7e95b015d8ab12e2985b9a7822b
│       │   └── chunk-001.nq.gz
│       ├── d997aab538e434a6ca07d6bee226fd5b0628262f
│       │   └── chunk-001.nq.gz
│       ├── da05f669d00817655f76b82972272d4d5f4d4225
│       │   └── chunk-001.nq.gz
│       ├── e64c7409d7c1c667cfaafc9976bff2ade6d514f4
│       │   └── chunk-001.nq.gz
│       ├── f07b6a0673c198588fa06edf9d0ae1b6d81cd233
│       │   └── chunk-001.nq.gz
│       └── f3088dc4b19148f378e458249a50b020d4fe7a04
│           └── chunk-001.nq.gz
└── blob
    ├── 006baccd15fbd149e37b80d8d316f8f24ee69a48.nq.gz
    ├── 007bdb6ff9462afecc9009dfffb591bd5a354c34.nq.gz
    ├── 0091119f15efe3aa63dc9bc53c982c0fae6f28fb.nq.gz
    ├── 01498c986305b5e720f131d1cdc5962426ce7563.nq.gz
    ├── 016821f492e91608b5f7e41b91129fd8c79e995c.nq.gz
    ├── 016beedb91e2b8f9cb32da8a0d56136b4b382bb9.nq.gz
    ├── 016d289466581e94a90b40487640e613eb527712.nq.gz
    ├── 01d10926a26bb5932e556aa9bc4766b5682ef9cf.nq.gz
    ├── 01dd1f79d6582442b0932a6a252585a5d85aa0a5.nq.gz
    ├── 02ca82d46ffaa67faa8581c16ac23cf71c40ce7d.nq.gz
    ├── 032fe5c6e033bcfb1bd12273bbf7685c2f7ae296.nq.gz
    ├── 038131ae3257d6b5c8216a3aa49393e41bf1f2bd.nq.gz
    ├── 038823a5c7bdfb00ef33549a1698dc88bf7b5877.nq.gz
    ├── 0395c8bc59d5b576dfe99eb5dc6edab82da99fe0.nq.gz
    ├── 03bc79ef01d058d54b2c70de34acff577c0a49b3.nq.gz
    ├── 03c81a1a74fdc90bb2f1f4c84a8b7aec83e20378.nq.gz
    ├── 03f9e7d248570248fe6dfc7449a54359d018b541.nq.gz
    ├── 0427e67afc8d689f423fee38114bb54015cfeba0.nq.gz
    ├── 04a712df7ede08d795c143869bc6c5c45af15a03.nq.gz
    ├── 04c21637cbd5ba974a8102dd1cd001e53b0803fd.nq.gz
    ├── 0511daa03ca3e2070fe3f1c9174895d2d00d8494.nq.gz
    ├── 0543911e3285ee7f9e0fd763b8e0a56566bb538e.nq.gz
    ├── 054aa4439afb2433a60e956cd102c7f0bdac680c.nq.gz
    ├── 054beb05147ad65606e965c1aeb18872d8859610.nq.gz
    ├── 0573ebef18ab795909dd9878396e5a1223509567.nq.gz
    ├── 057bc37f3779967caf7530c2b3a878c53815236c.nq.gz
    ├── 0586267286230d3ec16ff5c8686774572b3c82fd.nq.gz
    ├── 0590c815856a793c1cd4923ac036022ba2e58eea.nq.gz
    ├── 05a342312d3c922348f003b348f2cee5c355c22c.nq.gz
    ├── 05b222a2d6a910f92308dcf4eef0273f34126f2e.nq.gz
    ├── 05d298117e8ff52f0f5d9c3ea2c868e3ae4e78be.nq.gz
    ├── 06287a080783301e4d2854ee70f50c5b04e2ed6d.nq.gz
    ├── 063d1c898e4aba3d7488164b258d25a17d41d780.nq.gz
    ├── 0651e7fa8b8c8c7eb197c2107d84d870d6199ac7.nq.gz
    ├── 06572210a9ecd93b8fc7715523472dea1efa5400.nq.gz
    ├── 069636b8c30ebfe5ba9ee1140db3b04c9613aa35.nq.gz
    ├── 06a047e4cd14873d58f85b900e41e9cbd717a352.nq.gz
    ├── 075288ed621cc5b4643654a50e0d2edce84dbcfd.nq.gz
    ├── 07b0fa752732f8c888b2dbc20656106b33cb0d5f.nq.gz
    ├── 07b81d5ec142613572be36100d4968023e833f38.nq.gz
    ├── 07d1c0cd0d937455d4a2efb5d7070bb600d908ba.nq.gz
    ├── 07db8117e60cbdf66ab46cbb8045497a1538819f.nq.gz
    ├── 084548d6669c195c27eab74b6d7e6361384b997d.nq.gz
    ├── 08b32215e3f7b18618d2f9f58243a2a3c5db15b2.nq.gz
    ├── 08bb76287db45ea5d1dc00d656c0414578ae0d36.nq.gz
    ├── 08ec0b322eb2061214fc7e8d103e82fed6a1f657.nq.gz
    ├── 0915a9ef0ff7345ec2623d8ec68573e90294b650.nq.gz
    ├── 093bbe0d020be667763a9f11fff019a0457c1689.nq.gz
    ├── 093e69ed18120c792363d36fe801bf38a944c98d.nq.gz
    ├── 09dc43f854b3d87f5d95eac7900957c956f2015f.nq.gz
    ├── 0a0f016ffcedbaea75ac466b37d2c244438108cd.nq.gz
    ├── 0a212a96e21b27178213ac47aab5b05f7b743883.nq.gz
    ├── 0abbcdb84784a41ab35e408db6e6125ade5b6a00.nq.gz
    ├── 0af2b18b57a187669a1b8ad5f57e5fe8b2592f4e.nq.gz
    ├── 0b09f2bc44096309539e6a60677960234f676dc9.nq.gz
    ├── 0b5e73a225ab5d6e3fac32876e08908a86e0ce99.nq.gz
    ├── 0b63c971f314be79afc09f52f1c01f3d23806e84.nq.gz
    ├── 0b9136b9bdcb8f3bcd52ae357663090a4520871b.nq.gz
    ├── 0bafa49eab71547708feaf1bc8ee41e061c52340.nq.gz
    ├── 0bb3f75154752510e213e04449575cc26a92c9e6.nq.gz
    ├── 0bc70ba25b18a2f989c6bb8755a3a5cdac491548.nq.gz
    ├── 0c31220cc4eae23ed8d6a89796f640e6fa36e471.nq.gz
    ├── 0c83d1e246db3bfadb6529a0ac40df639c93a34b.nq.gz
    ├── 0c9cc11bb3964834b787d2e262979519bff4f8c2.nq.gz
    ├── 0cd12c707e1bcc9eda099ee7c3ea77a75eb75049.nq.gz
    ├── 0cd6a849a9e5d4bfbe70b0110f42e0d0a45c2490.nq.gz
    ├── 0d45be9e5e2b3059275927aa1f719b109dcac907.nq.gz
    ├── 0d4ad130dd71174bfe5868d8af1e81719d28bcad.nq.gz
    ├── 0dcbc93db9152efbdcf0458b380a85d016a23e61.nq.gz
    ├── 0e52bd854f8e9f35e57676a7733bf63c27c4eab0.nq.gz
    ├── 0e66e9007392afa9ec8361fca98a8d551c6118b1.nq.gz
    ├── 0e8bdd80d3c23656f5837ac38f58c901e4733431.nq.gz
    ├── 0ea059ebecc91f9bd5c2ba9d812ecd27ed52ba39.nq.gz
    ├── 0ea0e7e533f7b46ad3f9a1d5f5172ec6aa56fa43.nq.gz
    ├── 0ef45d986d85745cf338c7c6ee700180a115c8ca.nq.gz
    ├── 0f19f52a8d5ea5a63ea824ec0735f9da53036f02.nq.gz
    ├── 0f4ebc23045d61b9b63c1c283a9dff6b8b39e739.nq.gz
    ├── 0f750704594d34ea8de2ab0915edf3b493ebbfed.nq.gz
    ├── 0f78f3713c497cbc5cb16333ba0fbbd3e04b1270.nq.gz
    ├── 0fce32cee219d21698a280c3095a2113ae9bcad9.nq.gz
    ├── 0fdce146c6f6beaeaf91570c63466ec17c3176f0.nq.gz
    ├── 0fe843375c053db6e7ee8b8e9469b7ec06f79a46.nq.gz
    ├── 100ca78d7b0c79d7c1e91b84928ae7c54a9c36ed.nq.gz
    ├── 100d4aaebca8ccc1a413c65c08cbd9f90cdfce1f.nq.gz
    ├── 1044fb0f8539d5946826460d27cc06990fecef50.nq.gz
    ├── 1049d1a4512c856394fed8c8882de2713df2e650.nq.gz
    ├── 10593a82e6288ad9a157bba04e72661e880d3e25.nq.gz
    ├── 10a8044c501b6681f980fe8382edf6f249cb0dd9.nq.gz
    ├── 10ad31483ed91cda645386f68e283f45d47d0def.nq.gz
    ├── 10e2f7ca6951ce20d8e7cbe20e48a87fe8e2c748.nq.gz
    ├── 10e45921e207e2ec3da2222c46c4f69f4cb5005f.nq.gz
    ├── 10ee73a20ea4d91636e865bfd35538a243ed0892.nq.gz
    ├── 115d890075212dd19c69098e85cd6efa5501c43e.nq.gz
    ├── 11695470cb19df24ec5ec40bf164f8875256361c.nq.gz
    ├── 1193649e346cd0b2400b8471b03356f2181c71a4.nq.gz
    ├── 11e4e0cc510d0df51aaa5d763f79b748f886255f.nq.gz
    ├── 1255d9f3f932d314c485ea301403920cfa9f7a30.nq.gz
    ├── 126e02752322cafc1c7c25a686a786eddc001cb9.nq.gz
    ├── 127445e86e03807c596e96a4cd06c202656dcd41.nq.gz
    ├── 1295e7d44d5f1626ef42a0fcd076a8fb87d9b035.nq.gz
    ├── 12cf2571cc44ac0c5f167dc728f044e14f7145d6.nq.gz
    ├── 1383d7a6b5b601f6c5e9e26a18c1052ed89b176f.nq.gz
    ├── 1391c55b16aef8a16885a46774217c7b236e3dd9.nq.gz
    ├── 139f31157900d4c9e3bce28cd459a374f2e168a0.nq.gz
    ├── 13b85048e50e89d3bfaa4076cb84bcf0f2261eee.nq.gz
    ├── 13e44ed4dc947fe7878731fd5063682bac46b281.nq.gz
    ├── 142deab0774c277d021e939e1d2770a19c45dcb3.nq.gz
    ├── 1475d71228043cbdc4b36b1223161a826b493b45.nq.gz
    ├── 14e3f311beeaae1c80e7c60495fa80482508cd27.nq.gz
    ├── 14f945999c6bf5ecd404a98d7e5eefa722275011.nq.gz
    ├── 15c57d435584f9f25a473370fe3050c484850c71.nq.gz
    ├── 160b50aca5e8084a19425c1ab1a9c249d37dfd8b.nq.gz
    ├── 166da8d4accd2ec690fc92252530ee296b4394e8.nq.gz
    ├── 166dc551e6177de1d77969000dbdc7df3b28b532.nq.gz
    ├── 16bf8b0d7e0268b9b1c55ace3eadb0b01f57f4e2.nq.gz
    ├── 16c1bf55852f6498c84a7a1b179968b7952b1110.nq.gz
    ├── 16ed29a287a12bda18b1af5d716f7b344f0ce156.nq.gz
    ├── 170e7d53c813f7a006f0de75545152f60c5f0db1.nq.gz
    ├── 1724eae5da762e9dd753eda663e27b69a2515443.nq.gz
    ├── 172fe6f56774ae85437722ce1002f9b92e7089ea.nq.gz
    ├── 17330283d51c2662c876f7075efd4e755ca10923.nq.gz
    ├── 1743af4e74da76576216b1ad587dbd5f701caf94.nq.gz
    ├── 17e69c9e64ce5f9ebeb41fc4c853572c026a0c5b.nq.gz
    ├── 17e7e1f92543e5ffa12e3538058d2fe78cf139e4.nq.gz
    ├── 184b9973902f004682361b54e1379ac0095f8812.nq.gz
    ├── 18687fe6c4117695e8921cd948934196d0c6d01c.nq.gz
    ├── 1880a362b91cbf1dbe8956f1a8fb378ab15b071d.nq.gz
    └── 18a3dadeb9cce29a5ec42617e27f644c610db30c.nq.gz

54 directories, 200 files
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
*Parsed on 2026-09-21 by [repolex](https://repolex.ai)*
