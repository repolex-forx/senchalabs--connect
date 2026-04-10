# Repolex Knowledge Graph of senchalabs/connect

RDF knowledge graph data for [senchalabs/connect](https://github.com/senchalabs/connect), parsed by [repolex](https://repolex.ai).

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
lexq download senchalabs/connect
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 80fd58aa15531d9217781bb11ddb5336ff04b69f
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 80fd58aa15531d9217781bb11ddb5336ff04b69f.nq.gz
│   └── repolex
│       └── 80fd58aa15531d9217781bb11ddb5336ff04b69f
│           └── chunk-001.nq.gz
├── blob
│   ├── 03ddd799fa0a3aec561c75d4221f195db65d6eb9.nq.gz
│   ├── 046811ed7a6ef16be1a54bb860e1f22c6dacdacf.nq.gz
│   ├── 052fcdb3d5c29e375913b597852580a5b57a45fd.nq.gz
│   ├── 05978f84891509028454e84be03184df688a4d20.nq.gz
│   ├── 05da397bdb06fe265806c3bab365613c2a177ee2.nq.gz
│   ├── 0924e6837ace7e889104de986bf890fe76283a87.nq.gz
│   ├── 0a7d6f4a6f6d864d0118209b5cb64a456e83b095.nq.gz
│   ├── 0b18247da5850f3c2486373a3e179acd2772e8aa.nq.gz
│   ├── 0c5d22d96dfa665f16fc3a06d1f81a71300a70bd.nq.gz
│   ├── 0c76bd1297751b66230f74719504b2adb02b1615.nq.gz
│   ├── 0d61e3461891a09c17ec95fc7329cda68db85ab9.nq.gz
│   ├── 0dd4b400726bccfed3ecf9c7cac99604574e7132.nq.gz
│   ├── 0e615b0ccce483930cd7a6f00b4dfd6726a969cb.nq.gz
│   ├── 0e79b76aff99f1fae581d6c075009a547c86bf1a.nq.gz
│   ├── 106f5aa3611a4807ec8c21701c631730275089a4.nq.gz
│   ├── 134b6693687b2fa5fe36d48a9c0b8001f937c741.nq.gz
│   ├── 142fa72bf683528d32767314481eaf0cfa5ae4b2.nq.gz
│   ├── 159b24075191fc259cfd80c797a1b0d74c168422.nq.gz
│   ├── 15bd758f39213f99fc45ff0a4a438d0a73487b9f.nq.gz
│   ├── 17f79a8878c2dbdf519a2571c463737617c255c8.nq.gz
│   ├── 195dc6d6c365d298e466026b37c1959d96119ea7.nq.gz
│   ├── 1c4e6296a0ce09be8f53468ce3978219be38520b.nq.gz
│   ├── 1cb6cdc25af680e404fd7f96775f156578ce987a.nq.gz
│   ├── 1d2d0a498708bfba992434ac7f614b37b836577b.nq.gz
│   ├── 1de666fceff7bd9b6a15d8f6086a4744c0d00b3c.nq.gz
│   ├── 1eb880947ddf3e745c29e8d9dc90f09c7e6e323c.nq.gz
│   ├── 23240eedaa54b603fc9402ef1ca4c169566ff6eb.nq.gz
│   ├── 23a37b891c2f5faa3b8128d45373ceab794ca609.nq.gz
│   ├── 246a2f0b426faa0c7f5ba009e32b1deaf88d1288.nq.gz
│   ├── 28610f778c505ee6cfb6962744fb408bb9ff446a.nq.gz
│   ├── 2b6b1007f33dceb8fefd5ef0aa8fb5aeba0ea3a5.nq.gz
│   ├── 2f193889f7ea091c292acdd684c595dcb206b5c4.nq.gz
│   ├── 3025a85f357b728493900e4133986d8302cc6cf3.nq.gz
│   ├── 312eab0914ab59271384686255d1be913a6b3add.nq.gz
│   ├── 3141467c678d2b53f79deb22086a9cb3a576a08d.nq.gz
│   ├── 32b65071036121bf60a251a8c9b4911204619e0a.nq.gz
│   ├── 33df13066dd9d43a389801e960765913dd3d4a4f.nq.gz
│   ├── 34a05cccf064b35701b61ba1d395048873d7b48e.nq.gz
│   ├── 3506bf7ff11490ddb146d3fa7e3dca53632432c7.nq.gz
│   ├── 3a0240c05aa88f72a9d0fcf97b1d707965167355.nq.gz
│   ├── 3a1441c9a12062a4bb3d706000d3ca14399aebca.nq.gz
│   ├── 3ddb7c8d64ce68c6044dacbafd6fe8d9ef16762a.nq.gz
│   ├── 3f9538666251333f5fa519e01eb267d371ca9c78.nq.gz
│   ├── 413e1528af02665bedc8d0fc094567c0ca81d67a.nq.gz
│   ├── 44084add79b9a0fc3354d16bbd4b4b5ff8095da7.nq.gz
│   ├── 4a05955b33794e29097726af19f1742d9cc95b4d.nq.gz
│   ├── 4c8c54f70706145bafca26d824f66f01f2584a26.nq.gz
│   ├── 4cc537af0b31b5559cc645a8894f2cd65c8f7daf.nq.gz
│   ├── 5069b4c011431b8f4fca4e31bab7186d78324c38.nq.gz
│   ├── 514407bc186f733b8f58827b9beda1d51524d80f.nq.gz
│   ├── 52699bfee0ce434356c6a9576f32fb6633b01866.nq.gz
│   ├── 54ccc98ca6fe2bd1fa73df59001e0cd43316da1d.nq.gz
│   ├── 5565744b206fa3198153b85f33007965aa34094c.nq.gz
│   ├── 5769120b1b6d38019b505c9167498ea199212cc1.nq.gz
│   ├── 57858f6f5ecdeef8ef9677c63257da993270df41.nq.gz
│   ├── 581843637079359a6a58fcdccf0763690c67b063.nq.gz
│   ├── 5b2cbb3fd02a5e708d9f9de4ea118965972a02b0.nq.gz
│   ├── 5b475e1a1936dd01fe720c12f14125560d5c6032.nq.gz
│   ├── 5c77fbba649fed4c9ba88960206c925d5f34a8c7.nq.gz
│   ├── 5e5803aef884a549437e4d245f2438753b8b4245.nq.gz
│   ├── 6305b2021310fad9b26281fcd4e2b01c90f421d5.nq.gz
│   ├── 6532eb9d7c14b78b51594e14ebb2e6cdf239a651.nq.gz
│   ├── 65aa960b26688a42359cd8697cecad5dbbbe2b98.nq.gz
│   ├── 66eb8b4706d1a6e4643e3798ad2da901f9ed9d02.nq.gz
│   ├── 67df82222dbb37fb1f14dc74e6d9a261af3f202a.nq.gz
│   ├── 69ab1e35299ba51371d945e204d4ad59aaf8310d.nq.gz
│   ├── 69d083a94ea77660d12b331fdbf8783da7fc812e.nq.gz
│   ├── 6ddeafcd6ea07cb947d6a1c94f51b9b637b6d322.nq.gz
│   ├── 6ed2490ed1432d5d667a76235360824a1088e928.nq.gz
│   ├── 7215d1e8b0604a904ae4a217708ebce05c3b9bd8.nq.gz
│   ├── 76ed8a119ae1f1222bb5a6f9f337e91f27143c97.nq.gz
│   ├── 7868a25945cd5e5cb7daaca9591927511ca65c0f.nq.gz
│   ├── 78f5622a02edd09801e174616b1dc5a4d20288d4.nq.gz
│   ├── 7b2c3baf18fff915208a2cb11f960c1d0d524276.nq.gz
│   ├── 7cf001255d51e34d129c1c69cfdde4a7fa161b0f.nq.gz
│   ├── 7d6f1cb054ec2e5d963ada3cc5502cc6468f1021.nq.gz
│   ├── 7dcfb3cfbc3b9263d8d5f0ce54e1ed9b6d226816.nq.gz
│   ├── 7e568703d6432c530224e443771a04fc1e2e59c6.nq.gz
│   ├── 7e62a924bc57bc306a6017dd37eab38f23388c8f.nq.gz
│   ├── 80fe1ed0cc75fbb67e9398ae686641f8fb287238.nq.gz
│   ├── 813f712f726c935f9adf8d2f2dd0d7683791ef11.nq.gz
│   ├── 8233b4df31aa165f794336620de3960d36b137ad.nq.gz
│   ├── 834cdfaf48a509ca51d93250fb28dd12e5ea0a13.nq.gz
│   ├── 838e7a4170073e5b636515d1f66de4ac8130878e.nq.gz
│   ├── 848bdaf3f152ed114e5e2150a8e022c8097c0a80.nq.gz
│   ├── 86cc2dd7b3819c405989b3dc5d74b81277084c83.nq.gz
│   ├── 876b5d2739b06f11c5d13d8d1bec9b9a95598c34.nq.gz
│   ├── 87a69145075afd8f8fd8b391c5da1249ec8b2889.nq.gz
│   ├── 884ffd6f0aaf4fa8b1e47f085c5c6b1f81e8926b.nq.gz
│   ├── 895fc96a76b68b4924f1c51d022e1b82fa0f461f.nq.gz
│   ├── 897a9d89a968add3669af14c225a634984781efd.nq.gz
│   ├── 89ee2da0753040d1ba0a3487473a715a8fe89322.nq.gz
│   ├── 8a17aef5f7d1e0e1771440d63a4f961b1e813305.nq.gz
│   ├── 8a45872fe86c03768a4843d5950618fe2d825450.nq.gz
│   ├── 8b8b1ca0000bc8fa8d0379926736029f8fabe364.nq.gz
│   ├── 8c3539d9461bd1c31c660541ecbad2ad489d08d1.nq.gz
│   ├── 8d719df5205f7415ce657e5c277db4533c82f346.nq.gz
│   ├── 8e83281c5f8f0381c43adab760e0b29d28f16629.nq.gz
│   ├── 8eeb1c05316c3e23bedda6d0ced61d81cfe7904e.nq.gz
│   ├── 8f498dee39978353a1cdd203137689616fb638a2.nq.gz
│   ├── 8f8095e46fa4965700afe1f9d065d8a37b101676.nq.gz
│   ├── 8fb27d348c794e9a03348cf8ee11895983cf1930.nq.gz
│   ├── 8fe7474f182197d4f59150422aaab1fb4b970ef9.nq.gz
│   ├── 9046dde51c696b328f3b96950ba38221664470da.nq.gz
│   ├── 93fc5d347ba281599c710ce6415b62ff6a245f20.nq.gz
│   ├── 968f073fdddc1cc0f0800b1ac4001cd9a55f053d.nq.gz
│   ├── 9d9529d47d7d688d0de99f5d4ce12a487d31c7f8.nq.gz
│   ├── 9f692cdcaacb26c07c8d95c06cc72e437b0fbc40.nq.gz
│   ├── 9fc5a0a103ddaa691a8396008ecdef1cb1f1f138.nq.gz
│   ├── a0a433dfbb66cc427904bafad4069a96ce2132ef.nq.gz
│   ├── a3a89d10b78849627c25906098b731d6dc428c86.nq.gz
│   ├── a65bcb3e1e9613cd9e4950850db43d7025a5fdf9.nq.gz
│   ├── a750c5e861238f2d39555c702e7522b0b3c6c1f6.nq.gz
│   ├── a87cf847cb768acb8c600759ce433ce1bad3cdc0.nq.gz
│   ├── a90569edd644e90689206915285c01ba11056e28.nq.gz
│   ├── a9f31a278e17993d8d4e13beac2f9d5f7b42d08f.nq.gz
│   ├── aa23dde3746373b393489bd56b486d59b0c0d124.nq.gz
│   ├── aaf4014f26f9d3ed4a690fd149658d4e2d37a31c.nq.gz
│   ├── ae8ecbf47672a874c0958d0d113a56162c2bd364.nq.gz
│   ├── af1ecaf2981fa37628c8b8b15ee389f9575e5f6b.nq.gz
│   ├── b344218a6b660d73713b26929bb45fb07861cd9c.nq.gz
│   ├── b62aab7117b5cceae49da77504a00ae1446b47c2.nq.gz
│   ├── b885243649b26a189abd3c99b0b4131b67a925b2.nq.gz
│   ├── b8895ddecf57c8ece24f566d9b4a9d803e5a11bb.nq.gz
│   ├── b93e77600def75c9a144d3d0a5088a62c02cbb0b.nq.gz
│   ├── b977d7e52e2446ea01201c5c7209ac3a05f12c9f.nq.gz
│   ├── bca6ec4911c0b53fbd4a1a5a85bb6f5d6315bf20.nq.gz
│   ├── bcd9ed5d66c82f09430a1ef21eca3f27ac79ed7d.nq.gz
│   ├── bd95e4641f13524441519b56b985b06d682c1dc9.nq.gz
│   ├── bddba1f98ca56f8cffa39d768f80a06361d8d218.nq.gz
│   ├── bf7bd1c9bfd78d689c73ba67cf914182933ee68c.nq.gz
│   ├── c30a484d42794edce90e781ab31f8026a3b2486c.nq.gz
│   ├── c36098a2a2ab70b1eade7f72705669d541beebb5.nq.gz
│   ├── c4eff0387d5888c638ba09473ba6d2369f7b56f0.nq.gz
│   ├── c66011fb0fbdcbf210483d676b7131542a0e282b.nq.gz
│   ├── caea546af549a0302848f4f478c5bd4aae15bc01.nq.gz
│   ├── cf347c7d4685128a4a447abb9fb8e939417644f4.nq.gz
│   ├── cf5c22528cfa87a642abf07e2fb9c7b605a5aa0b.nq.gz
│   ├── d09d5920732f4592b8af0ccc53477f6452ef9ef7.nq.gz
│   ├── d3fffb6d989b4e09dbb0fb3bca876e41f42c660c.nq.gz
│   ├── d5bfa0719bc3a2ce4fc529403f0acd6b6057c956.nq.gz
│   ├── d61648452284da1bc28b10385f95b5d2bf027901.nq.gz
│   ├── d6626cb09eb11a298b90a8a27b0d8eab41f49a82.nq.gz
│   ├── d7a5e05994d36004b9418bcc66b4a6ada444e986.nq.gz
│   ├── d9cf13256f44ae8092e07e88b0f4243a8efa9f0e.nq.gz
│   ├── de8e003f9fb8752c09e7f3655d5d8664b5c62fc3.nq.gz
│   ├── dfdc5933ba2a8e371c5208e12315d582d12503a7.nq.gz
│   ├── e2bba269f972c8751de086f9abf490479e941d8f.nq.gz
│   ├── e2e107ac61ac259b87c544f6e7a4eb03422c6c21.nq.gz
│   ├── e4a1ecba1b60e54f3777717ed105cdde745b7184.nq.gz
│   ├── e74aeef2a926d5c6e7f9318297097164a1d67b79.nq.gz
│   ├── e7708292adabf4821612bfca032cbd019c63180b.nq.gz
│   ├── e8ff862595fb338204582a8c760233f014a3b9fb.nq.gz
│   ├── e902abb07671254da98cd4eb0f7d21fab89d2332.nq.gz
│   ├── eb6158eb5ca9c4b64c81e70e0fd894dbc8e2bed9.nq.gz
│   ├── ec569f5c7523c762bc2d0430a14b88076ce7d738.nq.gz
│   ├── ed748670ca6a355b011e95ffe9b71de51a1c9348.nq.gz
│   ├── ee0233703da37c9cc42591620e0befa769cd6a2a.nq.gz
│   ├── f07f449a44ff2761bfc7b752db3d08d0e1238b02.nq.gz
│   ├── f171981434cd075259074a9a7797bf84892f1304.nq.gz
│   ├── f501a593a4e08356b0cb29b40612f8e60bbff625.nq.gz
│   ├── f59b7c4365fa1720af1aa04eb47167ddaa6eeed4.nq.gz
│   ├── f6b74cc40f82fc83e4dfa6e9647ccc1b34e6ed7e.nq.gz
│   ├── f6cddf60bac7e32470a9d91cf0f18208f09aad34.nq.gz
│   ├── f7ea90419d950f9e69d977a1f5847456d96a5f0b.nq.gz
│   ├── f907e44b3330e3ed1763e42746a2943234adb94d.nq.gz
│   ├── f9f469db93b515f81185d159083d9d0be8f1eaf6.nq.gz
│   ├── fad4339552a58801cddf9c7b22b419b7b80de79f.nq.gz
│   ├── fb70d95c477e885eabf0e6a860e2dcf756c9a334.nq.gz
│   ├── fd4bbccdf1643f4ff5022fbc59b82546e259317e.nq.gz
│   ├── fe1f6b347a79c2b871793d84f43bc0478a53ea43.nq.gz
│   ├── fecadd08afed92536be91ab12d8e37b6bf410d5d.nq.gz
│   └── ffb8fc932f321d19049a51e0134459e7d6549226.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 80fd58aa15531d9217781bb11ddb5336ff04b69f.nq.gz
├── filetree
│   └── 80fd58aa15531d9217781bb11ddb5336ff04b69f.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 183 files
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

[senchalabs/connect](https://github.com/senchalabs/connect)

---
*Parsed on 2026-04-10 by [repolex](https://repolex.ai)*
