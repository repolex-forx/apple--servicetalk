# Repolex Knowledge Graph of apple/servicetalk

RDF knowledge graph data for [apple/servicetalk](https://github.com/apple/servicetalk), parsed by [repolex](https://repolex.ai).

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
lexq download apple/servicetalk
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 0d10ab15e5401f900f1af4c27e620827b4a426c0
│   │   │   ├── chunk-001.nq.gz
│   │   │   ├── chunk-002.nq.gz
│   │   │   └── chunk-003.nq.gz
│   │   └── 1ba85e3ff538d862a7bd4389f8753a4f066d2642
│   │       ├── chunk-001.nq.gz
│   │       ├── chunk-002.nq.gz
│   │       └── chunk-003.nq.gz
│   ├── lsp
│   │   ├── 0d10ab15e5401f900f1af4c27e620827b4a426c0.nq.gz
│   │   └── 1ba85e3ff538d862a7bd4389f8753a4f066d2642.nq.gz
│   └── repolex
│       └── 1ba85e3ff538d862a7bd4389f8753a4f066d2642
│           └── chunk-001.nq.gz
└── blob
    ├── 000515e0d959b3ac827f6db359606d80387772ad.nq.gz
    ├── 000c515a51a8338012add90281ab74e56223ece7.nq.gz
    ├── 00124e653aae6630ed4da8b6e5e8d0f50eebf838.nq.gz
    ├── 0017870b9ad389a6bb1c45b3a32a31d5458d4bc8.nq.gz
    ├── 001ea4a3d007f10bfd97bf7c977ecbd2c9304272.nq.gz
    ├── 003df557632b68e729fee4e121a1bc8021ee6343.nq.gz
    ├── 004696c262407ffc3c7a68c5c065fed4aa1ecf12.nq.gz
    ├── 004e89d21f5e8b153191f83f66e7a07c7968e808.nq.gz
    ├── 00553cd7b471897c832806e8c39a49187e4f2ad3.nq.gz
    ├── 005c25cad2c271e5ded68b622065fc9ca055202d.nq.gz
    ├── 006c4390d214f6a7581e9b205adc4971a8ea8a04.nq.gz
    ├── 00773d068ecf48a4d119ecb7e9f7c07c299bb23d.nq.gz
    ├── 009d4e8949d4922d352b09697b6e074bbd8e430f.nq.gz
    ├── 00a306cfa6bd70d31950b46ca81e623db4fcc9f6.nq.gz
    ├── 00aa100fa43b9e58aa80cf487d694425cc6af13c.nq.gz
    ├── 00b228cca511dce433a9c932fc4205926bca6c99.nq.gz
    ├── 00b2bfac653f1dfa22eb39d2a37d42a14d9eaaf0.nq.gz
    ├── 00c0e99b4ed145748cfab09fcd7c113fdeb50aa3.nq.gz
    ├── 00c7b95dec6fd3f01f2b8fa7e993565637d3ffdf.nq.gz
    ├── 00daeadcc5e1141a0990a232c5dbbedae97f2695.nq.gz
    ├── 00eb60fed80d4865390e41e1054c10c00e6bd413.nq.gz
    ├── 011050e77a753a48bf693ca6568da6e43ebcdef9.nq.gz
    ├── 01232b031028fdbaf51531d68440da6269bbc894.nq.gz
    ├── 0127d6ee9763fd2ebb6e4ba39b9e5ff283df2134.nq.gz
    ├── 01389a915ec24c750c2524aca05c5a6dc105bf20.nq.gz
    ├── 0143a04ed98538794ebf9f9ad7fca3631d31d595.nq.gz
    ├── 0150550767a528f701d772481575c8bc0e59a0f0.nq.gz
    ├── 01557f1eaec0b27f6216d641a22e92b74624898c.nq.gz
    ├── 0180d38b8558a144c679a7c00619f78ec6b0ec15.nq.gz
    ├── 0188a3c3f78475ab3f5326f3d7561f5ef25e8d09.nq.gz
    ├── 018924837ff0334b096ce10b59b63d6f934f962d.nq.gz
    ├── 018b5f426b853a349246846f7761f54f44a34770.nq.gz
    ├── 01969127045751509aafb68a4f046fbc7724f0ff.nq.gz
    ├── 01a34dd764e7dd304c646b4d0b2ab9200e6f07df.nq.gz
    ├── 01a423cc4667c079cbe824540dffd7dabf62d2d6.nq.gz
    ├── 01a5d8aaca1bc02e2d3797e3dc72586db932cc9a.nq.gz
    ├── 01bee4fab15e146b1ddbe572e09f4c48af7cb851.nq.gz
    ├── 01d5c29a10345ef878fcb9087a988eaf68a65723.nq.gz
    ├── 01ef5caa97a889466376784aa33018f02466de64.nq.gz
    ├── 01f58ce8064602558f5b27fa88c8815849f427c6.nq.gz
    ├── 01fbc057c880549eb4c082482d6262086192aa7c.nq.gz
    ├── 020a1afd1ef5453b2b189a18aceb69e76932984f.nq.gz
    ├── 0210db1948e181fef546254e8b1271f09dfd8d46.nq.gz
    ├── 023b016b851edd2ddcfbd1813c248125ae40185a.nq.gz
    ├── 0245fc03ccd110eb90d53506d8a902a233fdbbd8.nq.gz
    ├── 024cb733343c5cd3a8155c5d87ba4133bba0199b.nq.gz
    ├── 025431fe470c5750162aad0206762ac929b1bff9.nq.gz
    ├── 02582c2ebbcb36617d7ea01aa625957211a87a37.nq.gz
    ├── 025d2e41610d8381502b261b90fa9e3594fd6b45.nq.gz
    ├── 0273b234c3de2bb1e93bbe8485d7ead60074a0db.nq.gz
    ├── 02957fc89b97cef48f03aa3271474e97b9ba5d87.nq.gz
    ├── 02a14708ca8f5113eca1754639aa059663a01a35.nq.gz
    ├── 02b410b140ac2b68e03bb792a0b29a3138e0b12d.nq.gz
    ├── 02c52abee36cdf2955c7696a1c3015546dab084c.nq.gz
    ├── 02e04611cb49e80bf9319c1b275a9ca6876300a2.nq.gz
    ├── 02e2e2362a9de24ceb88f8504ce47eea809ef4bb.nq.gz
    ├── 031bcd3fb12af615ee8f881a7cface72e7eb6fa4.nq.gz
    ├── 0331f6ab13f7bffc4ad5a03c4f0b18bbe039407e.nq.gz
    ├── 0341f5f213540604d5bf5d531af3c8d318b1cd9a.nq.gz
    ├── 0347b254f5073005dc1df6b6d43f01943bcfca0f.nq.gz
    ├── 036ef6f76b9bde123fb7e899ab74a16ada5a4edc.nq.gz
    ├── 038d29133c808cbc4c27390bc9c846b3f665d117.nq.gz
    ├── 03951de91475fae15400d426ab6ecd5fe816c0de.nq.gz
    ├── 03980a74e35cbf40994e50e9ea65edd03e696b9c.nq.gz
    ├── 0399fdfc0068d028c530224f7807ee6b0d031ea3.nq.gz
    ├── 03a40d5e2fcfe3d7defae6aec51b103e31e10ea0.nq.gz
    ├── 03ac81c0599c3b1921acf337a19fe86055bb2a33.nq.gz
    ├── 03ad0f675f4db05e9127ebe475031a231d5d1ac8.nq.gz
    ├── 03b76f9bbec99b924c26ea644045609ade07a8ce.nq.gz
    ├── 03c4e9ffd47eb29113486ef7d9e28e812bbe9e67.nq.gz
    ├── 03c79ddf1febd6a0960a5f9ddf7fffa682e95087.nq.gz
    ├── 03c7c15bd739d28e5d13eb33a3780db8b4e4c645.nq.gz
    ├── 03c95fd85d0b28d2edffa29ee465dc08823b22a0.nq.gz
    ├── 03d0585795c0e98e0befbdf2215b46dc382dabe2.nq.gz
    ├── 03df2a571f4d4de54631f7459f9be4f47abade92.nq.gz
    ├── 03e86806b872c9a0592003d6efd37514c6f62417.nq.gz
    ├── 03ef597f06a0c99397949f67cabe84264d7a7873.nq.gz
    ├── 03f00328d7cde9daa18d92eafed895399d76cf19.nq.gz
    ├── 04120bc5219737bcb3f9d688b9d3f2d86bdaab76.nq.gz
    ├── 0417f210be8b4e300005f61ab18df273ae77e2cf.nq.gz
    ├── 04371e20cd7b0c45973637380332aeb4a8430e62.nq.gz
    ├── 043b6b13f8bd05ae3a35056488907d685763faf5.nq.gz
    ├── 0447a4dd12b2c3882a0cac54b549ea547166cfe2.nq.gz
    ├── 0451a63e059f77f7e8de2cbb04c90f7f06e67924.nq.gz
    ├── 04706a8c40cf80d1626e1d70fd75b7ae8873a3f7.nq.gz
    ├── 048b3415b3aeb31a1873f5919a8aa53eabe56bee.nq.gz
    ├── 0496187f7b1dca9520b1c01591f462a351713cd3.nq.gz
    ├── 04a4a1eed8f915bf8f56eeec73bf9922dd951d72.nq.gz
    ├── 04ad540a59fa4441d2e55d849b67843ce5e41358.nq.gz
    ├── 04b3615d62ad74a32ea8fbc742bc7b6129aec348.nq.gz
    ├── 04c21274811f1d613d0ee49869c9de47dbb43554.nq.gz
    ├── 04c77edbcbc636e9873fdc6077152b21a713ef10.nq.gz
    ├── 04ca0b9cbeef627baecfce7412aefb131dc87d41.nq.gz
    ├── 04db723dfd02bc52c6520b11407cf884739f4e33.nq.gz
    ├── 04f754626571422d9fff5b65c0ba8a741f01577e.nq.gz
    ├── 05002d7b2a6060607d4ec4e2eb35216459994191.nq.gz
    ├── 050341b8a9f9e137dafaa521bb0d34da06d445b1.nq.gz
    ├── 0515e062c6765e0f56ca3e19dd730c10ef65d157.nq.gz
    ├── 0517d180650b0799888cc72d9c9024712613dd65.nq.gz
    ├── 052407d2c19179eed4da7fefc5254590266e05fb.nq.gz
    ├── 052a60630c554c92b8c28cc24e18482cc39e8bdb.nq.gz
    ├── 0531c1c83063b9abd84a788f4ddf3c003715d087.nq.gz
    ├── 0536593b28efcaa127713fe13a32ea42b5052725.nq.gz
    ├── 054ae946ce759aa96c3068c10b7e05deda9bad90.nq.gz
    ├── 054eaa445d0e0fae93268bba230c9cf5de93c241.nq.gz
    ├── 0555a049b4b3c1a2925e3595e9c12f3f39b6210d.nq.gz
    ├── 0589571f7495199223fa5f5ebec9950743dce2ab.nq.gz
    ├── 059ced1bd5be27d3dee3b23268418c2a6fdb60c4.nq.gz
    ├── 05b18a3898368238de89cf59ad73f5b62c5736c0.nq.gz
    ├── 05b912b5168f0ad887e19667668b13ab179f5dfe.nq.gz
    ├── 05bde6245255ab9ef5626b3da986b5d62a7dad65.nq.gz
    ├── 05c2f5b3a499a99d3da366d6f6a23c53ef6f4361.nq.gz
    ├── 05cd3da6b11559c6187b4f9361c25b39e99ac871.nq.gz
    ├── 05f35ca0559f8026549988ec8ff3c6aee177b622.nq.gz
    ├── 05fa595aec95a92c49c5d14143f1d1f6a6ca538f.nq.gz
    ├── 05fad956b0b7f72d6aeca604f9877497eefb7d52.nq.gz
    ├── 060a0a5a016455c877546fdfad95f0905bf4515d.nq.gz
    ├── 0612b896e5717b97c7c9c379f02732e9c445f14c.nq.gz
    ├── 061578b72a25bf521e8608903ef9603ce8d2cea0.nq.gz
    ├── 0635ff8931a3068a5730d86c43084cacfa385115.nq.gz
    ├── 063845e098c4d0fdab3eaacdf8d7e483781e874a.nq.gz
    ├── 065ae30cc8534d4d8d1fdc7f74a1b42c5a2e4d91.nq.gz
    ├── 0668a38f92f3334ab39bdef511e4bb13015409b2.nq.gz
    ├── 067c7dca3f14a65e6a1cf983c480e13b43408903.nq.gz
    ├── 06871d144fa8d06ddb7eca683a5a3e1ac153656a.nq.gz
    ├── 0695fd24c6b9ed6767a5de5979ac3affa14489f6.nq.gz
    ├── 06a64756d719001cba6d5ecc376c4bdaef57fece.nq.gz
    ├── 06a7ca7bdc3ab98f6f7f5a1221a059f43a4699f8.nq.gz
    ├── 06acf707c091eb53090bf61422f9e6efbf040dbb.nq.gz
    ├── 06b0b6a42538c672dd0ad970b983a0afd0342c9d.nq.gz
    ├── 06c24e95edf4ff6cb1bde3496dbf2d381d0df0f7.nq.gz
    ├── 06c60323da36060f42819e7e67f38bdf6d083d36.nq.gz
    ├── 06e0a924a68eec32bce6ef70e755f892c40a736e.nq.gz
    ├── 06e57de993fdda8befc2e90ef8285ea8f312350b.nq.gz
    ├── 06ec33b9f521da631c539f8121a2786bac88eabe.nq.gz
    ├── 06efea474f6f549825693fade7c6cb582cdb4810.nq.gz
    ├── 070fec8b066addf910d4a3f0b36f9def555d1057.nq.gz
    ├── 071193be3d7eccf464a6f0821911d9a4e9f18b07.nq.gz
    ├── 0712f04344786893e28cc9a12093d25b32006b56.nq.gz
    ├── 0722995790b2d5b2870cbb4eaab524cfdb092888.nq.gz
    ├── 07257659dbd5a74ced85a92ef5d6397941adf0bc.nq.gz
    ├── 073aae03247785e35f56ae434fa81247498ffae0.nq.gz
    ├── 073f4dc874d089f04499960266b2dcb45ada4452.nq.gz
    ├── 074200fc11f9e9602242c16380a60d2878426ce5.nq.gz
    ├── 075ecba93d4984d968c22da9754acb4820f35a5e.nq.gz
    ├── 0777219683c6222b01dd5343da3174ad6eb2ca46.nq.gz
    ├── 077751c60c2608a00d07eaa3b3c37ab3b5e939d6.nq.gz
    ├── 0793c831b0bf3f5d6e4d8d6a6f31178946fafa8a.nq.gz
    ├── 07a9a4c60cd95e1d3cc7622f3bf893b71d52bf81.nq.gz
    ├── 07aa0d25c73ea698c17dcaef59c1c63801569016.nq.gz
    ├── 07b28d699cf2cae740f479a8757a0c90f6a9d75a.nq.gz
    ├── 07b66b8bef61e66c40f24e58b9db5b40e2e9aef7.nq.gz
    ├── 07b8acd4cdc28b73383f9bd0d0fbe16566e6aa03.nq.gz
    ├── 07bf9a4582d4222ff5b72d5caa12876913fd14e3.nq.gz
    ├── 07d360c5006f2c7f2f9553b31e303a38b0f5e2b4.nq.gz
    ├── 07d9dacc5d52d8791df12fa0f8861c45ba2a6656.nq.gz
    ├── 07dac6edc158dfc8b41ac94833e74c2cd932f3f2.nq.gz
    ├── 08076c2871a61e929a2c4a5de30898d83e0c7b3b.nq.gz
    ├── 081cbf364fba784a51b62be6650d997b9d3beb52.nq.gz
    ├── 083557b9987d56e3c93f7b9b7070fd3d48b5c3f8.nq.gz
    ├── 08413dc8aabc1d91bd68524d75e5dafcb0ea25ad.nq.gz
    ├── 08869f2a89c764a5a76b48f542d776a7f059b10d.nq.gz
    ├── 088a0013a368b0b911490d71b1c3d687fa84d1a1.nq.gz
    ├── 08ab614ccd2b3395c953788f5fd8206dde826b91.nq.gz
    ├── 08b43b8b5f279eb1bd96cfaaff195395ec461c45.nq.gz
    ├── 08bd4da482553952f06616ce2e46c81820822c34.nq.gz
    ├── 08dcc60e9db05a6c09520d4cc7335fac212ac504.nq.gz
    ├── 08edd6d485a7eed873cdeaa43e130c11ba1188d7.nq.gz
    ├── 08ef6fefbcf9a6161649f0f9288f30e2428a5a35.nq.gz
    ├── 08f46fed707c51e4b0d9afdd93ff61876f636ce6.nq.gz
    ├── 090265e36af7a599078db5e378b1f237366f815a.nq.gz
    ├── 0904b343d605a51c4de7c91ec67cd98991a0bcfa.nq.gz
    ├── 091481c09c2a8e0efba120556faa8da117dc04fb.nq.gz
    ├── 091cc8090e581c81e2cd9fbe5ae1e09813c66020.nq.gz
    ├── 0932d8bd7565372cc9675fe9545de1cc294bd170.nq.gz
    ├── 093787607f55ab0806843409c23af0519f60f135.nq.gz
    ├── 09419882bdb3c10e852c435d374468e4a8997ab7.nq.gz
    ├── 095be1e00497b57a6186c0559a6e73c45cda51aa.nq.gz
    ├── 095d98d1710c389acf855bfa5d95a6f0fc8df239.nq.gz
    ├── 095ed84b5f63dc5fd250a7ef8aaf96775881211e.nq.gz
    ├── 096246370df6b5a6edc0606a2f447722d646fbea.nq.gz
    ├── 0974b185bd66fc8958c9a4c0dfc6507e0f4a7a41.nq.gz
    ├── 098cd7853022992255bc22ab1bfe4cf2bc3788e9.nq.gz
    ├── 09992405b486c18e340a2ccbe134d6aaadb1e6f9.nq.gz
    ├── 09a63008402d89a7599a9ddad81650f83c6d888c.nq.gz
    ├── 09b5d6eece5a90b95569a2241d6c215c1035e797.nq.gz
    ├── 09bcafad2bf289d89ee536b2923f02d6897baeaa.nq.gz
    ├── 09c0db5529d17d2c3cf4ee40f915ac3fc6678aff.nq.gz
    ├── 09d8c63acb04866aeed47f4fb85bf8b25beedc55.nq.gz
    ├── 09dead5d19a6dcadae1a06f744099f4e3b1bdfe1.nq.gz
    └── 09e3683bb40537d418db04fd7aaca0df2a7de077.nq.gz

9 directories, 200 files
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

[apple/servicetalk](https://github.com/apple/servicetalk)

---
*Parsed on 2026-04-23 by [repolex](https://repolex.ai)*
