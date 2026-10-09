# Repolex Knowledge Graph of NousResearch/NemoClaw

RDF knowledge graph data for [NousResearch/NemoClaw](https://github.com/NousResearch/NemoClaw), parsed by [repolex](https://repolex.ai).

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
rlex download NousResearch/NemoClaw
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 59107b0e7b1f2f2a5ece0a7d9fb853e83d36d6c4
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 59107b0e7b1f2f2a5ece0a7d9fb853e83d36d6c4
│           └── chunk-001.nq.gz
└── blob
    ├── 0027a2351e78f078c230673a5625a60c1c976938.nq.gz
    ├── 008a960617d4b4d9228b67376356b5a14a5fca94.nq.gz
    ├── 00b63c217eedb88851491f5004fd49c477b5bde8.nq.gz
    ├── 017bb7ad7d0b762b334540e07b68c0f7e7f9704c.nq.gz
    ├── 0221f6eb4210ac0baedfaa0d7cf4fa4f7702c477.nq.gz
    ├── 0236c08055eb8c916d9d3ba7f86ba35ff2202e27.nq.gz
    ├── 0252de1567b97e9cfc944c0e0642942e33f6596a.nq.gz
    ├── 02775908dc208f69899bff1f6d6a939c79921073.nq.gz
    ├── 0306ba20ece19a84af81735a51fd10fe8bcc5d8c.nq.gz
    ├── 031a979e77b0c7a4436fce091cfc1820f37f93f6.nq.gz
    ├── 03320c90bbfe6666a3effae7b9c6e46e2d4c0b0a.nq.gz
    ├── 034d5e3a6e7ea880194779f3efb9d3fc3439f37d.nq.gz
    ├── 03ada15300a4b219a11a0f6357a57c66c9969fff.nq.gz
    ├── 03c70d34efb5de119afd440fd837f1c21df0091c.nq.gz
    ├── 03c794cf0ab1db429fa359c7cf3de9cfa640abeb.nq.gz
    ├── 04543e62d164fea19f7b3be976322bc81e05cb4d.nq.gz
    ├── 0511b1565b0e096ebdd70a31d6dc7167127e27b7.nq.gz
    ├── 070a434f7eacc23063ccce87585528e635dbccb2.nq.gz
    ├── 071b74b3091007b78fc39ffcd6ba6577fc5195dc.nq.gz
    ├── 08245571d1b9a63c2b055112a133fcd664f70fab.nq.gz
    ├── 0872700536fafe99a0401d72e95fbaaae07efa22.nq.gz
    ├── 09a3b9979ce3ac8bab5bb127c7326e83493ea231.nq.gz
    ├── 0a28cfb438ab75274bdf4af72f7c072c685aa79f.nq.gz
    ├── 0a3807d9e8e6b49179c46303c4019bcb4bef0888.nq.gz
    ├── 0bb5f67663903cd8f65299778c3d3845eec71a92.nq.gz
    ├── 0bc30f18300c9d060f987dd08fbac4b29a211cb7.nq.gz
    ├── 0d58de7a593eea096ff3260f31d2bdeb7a354c9a.nq.gz
    ├── 0d8bb5587cd63348919f661a7cc37afde8a6a8d5.nq.gz
    ├── 0e53ea62914806a4097659dd480f7a59506c9d77.nq.gz
    ├── 0ef15457ff9051279a70279b1571b915d2f5e9f2.nq.gz
    ├── 0f589ce37e9a1043c71c01af98345c6383ca306b.nq.gz
    ├── 0fff0fd9ab9f7f1f75adf0a474375d1667d0b3b1.nq.gz
    ├── 1064c83e3f1191f4a0b9bffdbd68112ab9e65c39.nq.gz
    ├── 107b16e1b194b48e6fad383bd07abc1d8635ee0e.nq.gz
    ├── 10e99b7bccb289704551a42abe3595a9f9b66012.nq.gz
    ├── 1106e4fff24926aee53cb9d5aa55ebb4d332f9bc.nq.gz
    ├── 1121f2522e236d525cb064635ad181df319d8b4f.nq.gz
    ├── 12441dfbb636d003f7d920fe6aa164d7c2e2be4a.nq.gz
    ├── 129f121e530dac899255112c384897f92f89a717.nq.gz
    ├── 12cf4884342181d31377188404e0ec9888961768.nq.gz
    ├── 139b643cf220c084c0b2e168da3693a0789b38d0.nq.gz
    ├── 147658fd9f7fda128ae73d076cf733dd38785440.nq.gz
    ├── 15384cd6973e7f35d4cd012edd200c7007856729.nq.gz
    ├── 172ce6a2fb2dea050e8136ae9fdd61c30f2b03ac.nq.gz
    ├── 176fd84795240b46d9e9a088ed017781d86ce793.nq.gz
    ├── 17b9160550305872a352b95d5af3aa936d8c7948.nq.gz
    ├── 17ead7346286a2e2e39eb2dc127ebf41ff2862f1.nq.gz
    ├── 17ee4b57778e81da5930a4b2ec171d39b354477d.nq.gz
    ├── 18472e01888374db680f83f74b7626a518a7893d.nq.gz
    ├── 188c2a15fcdd5b4699b9887e78f29478a1618c0d.nq.gz
    ├── 19587937c10c5895c6897749e3ce8d732551427b.nq.gz
    ├── 19e9f168897589bc2b5a30afa551afc68535a6bb.nq.gz
    ├── 1a068de178bb11668d977e892307e46818311b31.nq.gz
    ├── 1a1f58996916fd43772eae021a1aeceee872006e.nq.gz
    ├── 1ab1cff9d9ff79d407c879832bc9d9fd3ea8da9b.nq.gz
    ├── 1bbb8679fc7841d3e5df1531aef698cfd81602fa.nq.gz
    ├── 1c3fe83fa9533e6baaa61b4b7bf8d3c550149ecc.nq.gz
    ├── 1d33a7e988029e2852adc1c8c9ef2bd6a4fdc489.nq.gz
    ├── 1d87d896a98280ca110559243ee4c17c2651405d.nq.gz
    ├── 1dcda82ba803e7245672aea23faa0abac1753fed.nq.gz
    ├── 1ec2294cd6e33e0cf5051f5f16157243887db850.nq.gz
    ├── 1ed177e66bd2e625825f95c8f3f0726568b49e5c.nq.gz
    ├── 1f3a0d4b96727e13a0c6715ee5460ee6c9d7a58e.nq.gz
    ├── 1fc525c64b61adc54a9b1bfe1c8fd1ec04032575.nq.gz
    ├── 207fba2746e312b3856f6bf6176ad3cd4ec63076.nq.gz
    ├── 20a4a0cf3e0db55d678e74906ff0f49aff37550d.nq.gz
    ├── 20bdde44a0f137dba952024105425bd0e0e2d069.nq.gz
    ├── 20f176221d87dc98bb4a85e563ec6b794f71dcdf.nq.gz
    ├── 20f5cfff8af5518c14323991e24bf7420d76d83e.nq.gz
    ├── 21194202011686c1e1bc52d962bb04975ff9322c.nq.gz
    ├── 2138e53df724ffcd35c23535440b6b24563440bf.nq.gz
    ├── 21d82312ca2ddba8333d34a423f0e4db1a0b6dc6.nq.gz
    ├── 224871b0b36363faeb041d4ba5fa1bf95b604e5b.nq.gz
    ├── 22487517f0396d69a06ee831f58fc125ad13982f.nq.gz
    ├── 231988663da8f748d538d436ef31488cb48bea51.nq.gz
    ├── 235754ac6a9c8e90e599e94c54a68b306e4ce42c.nq.gz
    ├── 23680cb3c3163c551ef0ed5388fab77aa49b287b.nq.gz
    ├── 23feeae400df76eecf93b798d53e5013563c26c7.nq.gz
    ├── 2428382cb44c8ea066fca0faef5acce3120ca810.nq.gz
    ├── 2477ea8f3a4a84a65e6967032ac4a6655e285c41.nq.gz
    ├── 256482e16caf6d6f169f71230603d3141e8fca82.nq.gz
    ├── 25c5370d77d50a256bde9ca1699c292a409a0ff1.nq.gz
    ├── 25ce2678a6808415026b708ea2e0139880f4af9c.nq.gz
    ├── 25f5d58db4b75de2b949dbd5a81bd65a4d1f0e65.nq.gz
    ├── 260a8e0aa66392fb11811dd31921e3e5263d2eb5.nq.gz
    ├── 263aef4fe84fb95bd6bc216a4fc253b942d5a3f0.nq.gz
    ├── 2652b9493cc7f722d10e560443edfae3c399ae49.nq.gz
    ├── 26a9cbe026a60de7d4288594142e03d89a9582e8.nq.gz
    ├── 26cbf08353999c22e215f9be7bc041e4081d4ca1.nq.gz
    ├── 2835d6e2d9386e33472b7c422cdf58610271de0f.nq.gz
    ├── 2a09a10ffa7c47a27a7b77dd7a47b57e1c07f83b.nq.gz
    ├── 2b5480f862a304fa9e8a81047b86afedb5e779e0.nq.gz
    ├── 2b8650af546169ba9d07c42c859831ccf199206b.nq.gz
    ├── 2c8168cf420c2409744d40615e34d08fa4562533.nq.gz
    ├── 2c96efff9f025e77cf85618a8034629cc2b88149.nq.gz
    ├── 2d958f4fe9f2522cf21114807dedf7fa1a02ac13.nq.gz
    ├── 2e5d584f3b2ca7874f328534cd0dd7a87ad98fb0.nq.gz
    ├── 31653f65688fc8462732d40dde049f5fd96d0157.nq.gz
    ├── 31b646f577e2e8483e1583fe7bcd9fa7017f847c.nq.gz
    ├── 325d8626df005596930de4ce448a5f8394983bd3.nq.gz
    ├── 337cee70eb4b4ffcbe97ed49deb89586b1c970a2.nq.gz
    ├── 34eac39f32b13ea5bcc387dbff0dbd761deecc6a.nq.gz
    ├── 34eb9882a45a4b14bda235d1586683e8b2224f26.nq.gz
    ├── 35a9fe8d4e4086149803cb4b23dbd5814e60a641.nq.gz
    ├── 3646e860ac43e899f95f3c2c3af7093e56f11ea6.nq.gz
    ├── 36bbfb517f49a307a7e421a7d471e0a7efa0c9bb.nq.gz
    ├── 36c855bb1bbea5549cecccec1baf3dfdbd8322b6.nq.gz
    ├── 3808c823b67b71166292b421f58561a9685917e9.nq.gz
    ├── 39baa0df2d4b321ce4eff925350b0cf131869fc3.nq.gz
    ├── 3a1a4cc299f4c107de2ad5d80f1b27ea8c7288b4.nq.gz
    ├── 3a401327628ecfca84aff8bd4a6142cb96fad0d6.nq.gz
    ├── 3a5c29410ddadca3c6b9e1a6c9f1262464394658.nq.gz
    ├── 3b0e0d498b71e435c3e5d1dacebf19a38e2f3cb9.nq.gz
    ├── 3c40f579619a05bdadbfa88aa4bde1a562b81056.nq.gz
    ├── 3c556208a20c9a61b7d868a0ef6a165a70ae597f.nq.gz
    ├── 3d922857c3532dde941445d8675ae3c1420b488f.nq.gz
    ├── 3e9cd696bb7da45ede784c09f28a7eadd9f187ef.nq.gz
    ├── 3f38593aeea8db48e7984d3b3df660ad2c5c9269.nq.gz
    ├── 405f391bc094191009f1034de65461e5233294e6.nq.gz
    ├── 40c8644e1a634a7fc23614d625f6eaf43d924c82.nq.gz
    ├── 413810fc57a6d801c3b404eaec9ca0efa9cc6a92.nq.gz
    ├── 414fb8287238ac4e41227b5660dd901eafd1af26.nq.gz
    ├── 417aada56e074ca28d6997ea38f85baf53b96694.nq.gz
    ├── 4270d615a1996776428f2fe48e47aa296e4c6abe.nq.gz
    ├── 42dec0b51182b40bd0cad334e408eb3562d41aea.nq.gz
    ├── 432f726a4b995df4756142a6befc613708b589ec.nq.gz
    ├── 43c94835cf24bdd1f1e6f614eeb7abec808f861a.nq.gz
    ├── 43fbc044b1103c81f8a11d4a906378ba92fd7761.nq.gz
    ├── 442dd41e7b8ec30863be8474b160e0439c250754.nq.gz
    ├── 4642ba96471fc479a76fec34627283d0a7fe6f54.nq.gz
    ├── 4660e50c45f2ce97f6fad968797a5972c56a1fd0.nq.gz
    ├── 46748382fa1f165270d187831591c5dfcd215684.nq.gz
    ├── 46f523f60be36512335bf643686835ee43366063.nq.gz
    ├── 472f1e26e528d72d00188259d096c29067da3c7d.nq.gz
    ├── 478b4dfa46955344cfea06bdf9369c2c925bc847.nq.gz
    ├── 47ab375167117fffe9d1da59e614dc192c8c380c.nq.gz
    ├── 47e9f1fd4306d513f74b93d1fceb1125402f8b02.nq.gz
    ├── 483c9a7c412f33053121c503e352e6cf96f5f4e5.nq.gz
    ├── 49175ee0ea396681eb2e6b9ea789ff415d488496.nq.gz
    ├── 494166857821eccdfce62e7f27b3853c011a15c2.nq.gz
    ├── 49468b91886c1c8f5e707cb79a66ed336537dfe0.nq.gz
    ├── 4a7a9777c882cdd4d0191cb34e3a81dc5b2d75bf.nq.gz
    ├── 4aa7887a557a10d560b9ad1c368984628f5a18f3.nq.gz
    ├── 4bf46857b5847f72416c6d52548222ac95f5e38a.nq.gz
    ├── 4cf7a0d2a432eb0a1ada54bdf3ec5480ac918a0d.nq.gz
    ├── 4d6a62beb6f909734917ff42150e825fbf3344fa.nq.gz
    ├── 4ed31d9afdc1f2f69e718748bd0f5ae0299d19b2.nq.gz
    ├── 502e2f3143749c9b24b474c3b675a1e3e7de01bf.nq.gz
    ├── 50c97513249abefe73c739a52bf6310a779fcbb6.nq.gz
    ├── 518d43e307e18acb08714bde4c375ad33f81ca1c.nq.gz
    ├── 52cf8a6db2d2d21511b4048f2f5aa8548c9a34a5.nq.gz
    ├── 536c0797a374635921d6c2c4cb3208c9d8d68e2a.nq.gz
    ├── 5382aaeb9b573e0eca53864d9c9a09f2ab44ace9.nq.gz
    ├── 53a539fa2fa3cc16098228dd473be0c9a084c607.nq.gz
    ├── 53a6f4ba48319a41b5b613f5aeebb032de40708f.nq.gz
    ├── 53ed30427d7e35ea3a40428d994362b135192e31.nq.gz
    ├── 548859d436e3fd6fe4625cf03b020ab616fccf3d.nq.gz
    ├── 54edab75337b436d6d64235d5ea7752e87e5d350.nq.gz
    ├── 54f500342bf20e1e6e8640d59dbca26b3c410769.nq.gz
    ├── 550f6d2096b108a7b13fc8fb641a4205e4e48695.nq.gz
    ├── 551d6643bff7e8b9c8e7a17bb0e74854e2a70dde.nq.gz
    ├── 552cae248484394db2a8e0044d4824d6aa1702cf.nq.gz
    ├── 55304d8c3da302203a0d4931c8bac7497a48411b.nq.gz
    ├── 56350c876c2ab77e092d00bccd52d51c815b29ae.nq.gz
    ├── 56d3d1f7be6f65fac0c55872ce899e5fb60987c4.nq.gz
    ├── 58e2db49b364d22d1f175cff41a57ca10ea1f7dc.nq.gz
    ├── 59c5aa338e51da2fb158033c6aafbb701d051b0c.nq.gz
    ├── 59eaf0100672e9eb6d1aeb8d04fdf76b6757e75f.nq.gz
    ├── 5a4c06e1e5f155e93c50109f52e7d56404951b97.nq.gz
    ├── 5aa89ab2f9fd204e2cd43a5764a7c70109927d58.nq.gz
    ├── 5baae0d308bd51bdd47499ee662d01aedc69c490.nq.gz
    ├── 5bec08d1bbe9083fd4fe6a3e2828d7c44b4b91dc.nq.gz
    ├── 5c5be2ac763b60b3b07b3c9352686484735646b5.nq.gz
    ├── 5da780affd78d36a72040868d8e3ded735f48061.nq.gz
    ├── 5e1328acf78cc45b6d23f3be6a9dad74a1fbf9c5.nq.gz
    ├── 5e57aa126648b9595920366a30fb361f78adb364.nq.gz
    ├── 5eb8358f5d8459ded06b24a7d6dbb2a32ccb8969.nq.gz
    ├── 5f17d1197229e87c0de5927786cfba2e627d97d4.nq.gz
    ├── 5f70c317b5f27f228918027c292c560c8376acbf.nq.gz
    ├── 5ffd9800b97cf26f3962c0fcda77cdb56cb946a8.nq.gz
    ├── 6086b799d07b30ad41d2eec6d11bea3fccae2915.nq.gz
    ├── 61f19b0cfea66b6a72e36cb1bce0fdd485f08578.nq.gz
    ├── 6247be0254d5019144c80c741f09e1cd96fd7322.nq.gz
    ├── 628a37daa41e9249ad289957547dee4462ce01b1.nq.gz
    ├── 628f4923c95cec554148046dbfbff2667fb3ba6c.nq.gz
    ├── 641651b1c7a73bea56762e876b4f2cea21387d7e.nq.gz
    ├── 64215d1cb4842fcb282cc2e37bb93f4df77ea903.nq.gz
    ├── 64304f5d55c6fb4857c489b033f0814c2b2d954d.nq.gz
    ├── 64e1b086fcb0844f322c6d67d0f4349816a52ae9.nq.gz
    ├── 65bfd674b3260dc42d0bc8bdc2d68b25f0fe897f.nq.gz
    ├── 6680bbc017ee008be7ec73ad5fc54d647c8ec4d5.nq.gz
    ├── 675b8f8624a82b5e50abca9b9315fa2868e8c4c9.nq.gz
    ├── 67a316da6d3b32c8911cae48dc6e5f601719b307.nq.gz
    ├── 6871dfe5d0e16f0f066444fc52eb634308f518f0.nq.gz
    ├── 68ef0257e34ee8182e154a52b86792a4335efe5e.nq.gz
    ├── 6ac6f4c15b4a8a592f1178e1609c24bfd1a6371c.nq.gz
    ├── 6b46f5d27c938121d4b026cf60cc10091469b09c.nq.gz
    └── 6b53fbda158b3b6e8da7633cd19c8d22ee4e4279.nq.gz

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

[NousResearch/NemoClaw](https://github.com/NousResearch/NemoClaw)

---
*Parsed on 2026-10-09 by [repolex](https://repolex.ai)*
