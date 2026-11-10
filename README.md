# Repolex Knowledge Graph of prettier/angular-html-parser

RDF knowledge graph data for [prettier/angular-html-parser](https://github.com/prettier/angular-html-parser), parsed by [repolex](https://repolex.ai).

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
rlex download prettier/angular-html-parser
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0b9e1364456375554a28547c094e31afbcdf06ce
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 0b9e1364456375554a28547c094e31afbcdf06ce
│           └── chunk-001.nq.gz
└── blob
    ├── 0011c6d626db0411819a9e483b21558826a558dd.nq.gz
    ├── 003620bfa382264a8a276c17cc818ae710f94fdb.nq.gz
    ├── 0044786c9522818e01bfc9ab0ac1186ac30a1149.nq.gz
    ├── 00491db411fdb967076367725bcf3911e3badfc8.nq.gz
    ├── 00646435a3ac691d18b0310c7639dff4f16def95.nq.gz
    ├── 020f5fc2d17a00296134fd403a78fad9b57ca5cb.nq.gz
    ├── 022bb9d147316d0c6199328a9396c8c4f187326b.nq.gz
    ├── 02ec43bc16fc137890e94f15389001c2368b284b.nq.gz
    ├── 03df317327dc6a2996b68e668a35b5d6a7a747f2.nq.gz
    ├── 0475886c43123c010083e0cfc49fb384dcf87fab.nq.gz
    ├── 060551340b1892a5fd4c905b14f3a1feab9f3316.nq.gz
    ├── 061094ad1ff5d3afbe4ce0b368c39d276c9a4c6d.nq.gz
    ├── 065095d04306f5f19ba640d2f05ee93e29f3c5be.nq.gz
    ├── 06dc8d1dd6b448fa0b47e042c911c6fb841d3a81.nq.gz
    ├── 06ee0f8c056951552c26c9f90a3e705b5177a43f.nq.gz
    ├── 08385dd8d52f1a76e3323a21fe2f3c756fa69e20.nq.gz
    ├── 087565cb38b4cebc97326a40a7fc22e054923758.nq.gz
    ├── 091f2db757394e169a4e32f5b897fe1816d7e555.nq.gz
    ├── 096752c21a9c67876f47d888cd329a5f92309577.nq.gz
    ├── 09ff0733696a8a9bb4871580106370c01904e709.nq.gz
    ├── 0a3fb8e840b846dad4841e3b2f3432d40286e7bf.nq.gz
    ├── 0a77e2a2bd417a33b3232476948848db2a6c5ee7.nq.gz
    ├── 0ae77eea5d4cc3ee80522f86a7003703469dcfaf.nq.gz
    ├── 0c3e894d097e39d5aadeb8ccc20f615d777b71a3.nq.gz
    ├── 0dab9caad6bdfe3162c0b30dff72d42ed7edf9dd.nq.gz
    ├── 0db8581977bee2480734759ad27735b37e0e214c.nq.gz
    ├── 0e2bc7b3e4a6485b14d32b4d7b717f03d8ea49fc.nq.gz
    ├── 0eb12f713b68392c991c77b4f4fe8d0ae497977f.nq.gz
    ├── 0eb265a28d5eda009f6dfd0afd411e5f22abcc74.nq.gz
    ├── 0efe9729d104fa4eb6e975ea93aae17e19c3282d.nq.gz
    ├── 0f19a6e3d1e158c6c4c11bfdefd00972d3e8e082.nq.gz
    ├── 0fa07a949a4946b7368cc56ba9901be2936c100c.nq.gz
    ├── 0fe7a768c44808030de2c563556eb845d71202af.nq.gz
    ├── 100fa09fafaf79094edd7b45d732d757ce9907d5.nq.gz
    ├── 10bde014f57b39084c9a71d3a32d5822c62483f3.nq.gz
    ├── 10f6153ecff1505a17a6b297e2ca3b57e40ad91e.nq.gz
    ├── 112ebc10ba537210cbe8691c8fd7867aa0cbdc4b.nq.gz
    ├── 11734f9e0ec69897ad659e36acae26239d98076e.nq.gz
    ├── 11e087db558cd3fcf06719b96642b76b3701c084.nq.gz
    ├── 11ed69b908d78ea265a33037ff5e8b3ed77950a0.nq.gz
    ├── 11faa0dd80245b5230a1d7caab3d0197ee05b40e.nq.gz
    ├── 124da143bd6717b7ad1390b2d3a781ee85146c42.nq.gz
    ├── 1307f122c860189a0443635660357720ba29412e.nq.gz
    ├── 13abc6a9bc4b666509ed7747d4a6ecaf8bb392fe.nq.gz
    ├── 1459c4ecb4b8249edbe5a388753cc3372f634f0d.nq.gz
    ├── 15eae9d97fb66f64f61465accef511d21b7c82b5.nq.gz
    ├── 16715f526a316d04f31b0cf679cb002b25690b20.nq.gz
    ├── 168def4721e17c526f28442cd70e804c5b0d538a.nq.gz
    ├── 17f5a0e1d2febd7baa15cab2f9d460561f0664fb.nq.gz
    ├── 18179f828588201a8203ca749f1fa64ec75f408d.nq.gz
    ├── 1838f059c446a919d760a4259a751bc553a72989.nq.gz
    ├── 18c9c74ea467f404239dda2886eacd7c462c60af.nq.gz
    ├── 193eefc1ca9fa7df6d7908a9282cb4cdd1611029.nq.gz
    ├── 1965ea6734cf43d0401f1a53960523493efa2397.nq.gz
    ├── 198cfaa3ecc3388318ee3761597cf8b40d9d2f14.nq.gz
    ├── 1bb28e8308aa76eb9427c07d26ac198f197750ae.nq.gz
    ├── 1bbe306fb59efb11cd9a5d00273e47cc5a2eb25f.nq.gz
    ├── 1c8c06438b0a66732db90e2d021c4a4aba567171.nq.gz
    ├── 1ce09a14ab6f0ac53094567c6b2e0ba2c8620ceb.nq.gz
    ├── 1d7e8a79198da2423bd314cb2ef45a0ba0d672d4.nq.gz
    ├── 1dd869e0f7858c057e6ff78a31969b25d75b7d9d.nq.gz
    ├── 1e0b3b3cd5d11d670b0719325e2ceb661cafef18.nq.gz
    ├── 1eb1fe0f2c8a4d9e4383d5b6572a976be2077a5e.nq.gz
    ├── 1eeb30101071c0c1a9bbb01368ba450c058adcd2.nq.gz
    ├── 1f15c663f8a410d6e74e7171616e466c3a0fc9ee.nq.gz
    ├── 1fe043b428e028378ac1cb3cb2867fbbb0fe3874.nq.gz
    ├── 205af4416187052609e301f3d02b57fc4f32ab60.nq.gz
    ├── 216c84347061dc03f89199837a1ba8fe790521af.nq.gz
    ├── 21bb0dc6532e89a086471285a22fe8a2ac1a6f7e.nq.gz
    ├── 225a4aa585b670a0d95a0bb99123cf7fa629eb39.nq.gz
    ├── 22696ba38edee006086a7fb0100368d3978e3df9.nq.gz
    ├── 23d3c4a99deb62331c053a53759672a41ebb1e04.nq.gz
    ├── 25dba47418a61c19898646264c7d2d732e574ed6.nq.gz
    ├── 273724590ac261ee0487a01e281b1cc039222edf.nq.gz
    ├── 28ae1bd06551bece591f65aff5ef2571b454a7fe.nq.gz
    ├── 296250b3d7477f86f673b1c854472855b85702b4.nq.gz
    ├── 2a819e5ce14cc8f4d56aef5882318ac6d6078a2b.nq.gz
    ├── 2b374d2c85298665f84224895f3118b6b1891ce4.nq.gz
    ├── 2bd2e0f1c6bcf187ebed2f73a6bde4821e1d0954.nq.gz
    ├── 2bf5f6432cca9b06743b726a4106d9b4c3ac09a9.nq.gz
    ├── 2dc838d6f359fa4f3bf3bba05635b33d0aa8c12c.nq.gz
    ├── 2dfc8490995ffe2595d95dc4d5aa441f206c1766.nq.gz
    ├── 2e8ba428c34b5b6bd61a542b409374a2ec9f3793.nq.gz
    ├── 317345f010ed50c6b7ac80d25f6c2167b9822e81.nq.gz
    ├── 31966a11edd15ca1ed19c545209bab03143a174f.nq.gz
    ├── 31e1091b227bdf398ab0511456ba544294a57d4f.nq.gz
    ├── 3435a5c90e01e682af9556b2320ef105f4e53d00.nq.gz
    ├── 34cb8a0509fefcfd17a3c70d66d1e8591b44280b.nq.gz
    ├── 356e0f985ba16d7c621a44b14b94008eeeecb19f.nq.gz
    ├── 35c8fff3f19d6d301f01167487938db9d0be4a1b.nq.gz
    ├── 36b6bc5f2f182a36c80342d1ad3f1a28b5e431d3.nq.gz
    ├── 36c15b01565081e7a36b47612805f2de83d7fc5f.nq.gz
    ├── 36c6c8b852b0fdda480bad7bec372eb69489d7fa.nq.gz
    ├── 36d8b2a62dff96360efd3501952caa6208f16813.nq.gz
    ├── 3733a1324a7c53c7db0a36741b112dcedb66b539.nq.gz
    ├── 374e2d5f3746b46e61cab734c5f94d9fda05f941.nq.gz
    ├── 3922c3c9a205017f9165fc25748c520b9361c88a.nq.gz
    ├── 3986a68acf9ecc22f9b0f3c9e5f0dcb9b992b063.nq.gz
    ├── 39ce12f8ba30a8caba5d67266f5e6bf8e39685af.nq.gz
    ├── 3b378a2f1231ca19ee8aefdf83c6bbff3adf5868.nq.gz
    ├── 3b8d1a2a5b802ae618d20d5d0ca5fba756099604.nq.gz
    ├── 3bcfc94940aade8966cda914dcd03fa3c2b79aa3.nq.gz
    ├── 3bf281f448c535bd71ca0b3f2eb9e9ae577c320d.nq.gz
    ├── 3cdfdc467e5f6c71230fbfe2a5b0805020f0d277.nq.gz
    ├── 3d9cdb5b4207ff52a5757d99358ec4e4cffdc5dc.nq.gz
    ├── 3dd400f73d10ef196d8eff2e7cdf255eafa0bf07.nq.gz
    ├── 3ecaddbc2958ec82bae8659c66d4c5e85961f50f.nq.gz
    ├── 3f9eacb71aa9d597aa850e50832230b5b5f07c3b.nq.gz
    ├── 401afcad4479c8c234958f0f118db7aa4c4c26f2.nq.gz
    ├── 40f760787ff5cd7ad7ea0468d8a07fd6aa04aa37.nq.gz
    ├── 410cab6378611ba5e357a3f15724c01e411ccc74.nq.gz
    ├── 413528caf9f7306f967af708e684fc712bdf19c7.nq.gz
    ├── 41cf8168fb1d2c8f514ff1bf8a4d6b7d9e31eead.nq.gz
    ├── 426b22f61630e45f9bd82272a8fae7b9865f391f.nq.gz
    ├── 427a7beb49a86e884dc427ae5c0b15919c5d7424.nq.gz
    ├── 42a25c33e28d0eee61b203684d662954e89f63ba.nq.gz
    ├── 42ddfc030ec578cc0c1a0b6fb99d05f3dfed2a70.nq.gz
    ├── 43f30985462219b389367f83e86a3e554e662015.nq.gz
    ├── 44901c28ac9c305b098ab9811fd0ffdd98eb0a08.nq.gz
    ├── 44e63b965329b525c5d957564bc0edb0bef76805.nq.gz
    ├── 4505e6aebf6e8bef103538941a0717bf154db05f.nq.gz
    ├── 46a8bd6fb4d0bf777e2147452fdaaa8b4d07e355.nq.gz
    ├── 4729c0b5244086109e1700217316d3c9845863f3.nq.gz
    ├── 47971ec6046e226023355e009d9dc2f2073f865e.nq.gz
    ├── 47ab2243189d6ee56cd60bb6b849000147f35157.nq.gz
    ├── 487bb9b08030468b19da4e65e173f95224ef2ff6.nq.gz
    ├── 48e53392e86091d3cc3a9beb518d0fa6786bf054.nq.gz
    ├── 4b2c031d3a05f8e9be68de2088d56a7e4e374a3b.nq.gz
    ├── 4b5c179e0135a8df43bab965c63e467d5ba35cd2.nq.gz
    ├── 4c06b5e1401a0a3c0fbc75a0043277b32426c61f.nq.gz
    ├── 4cc9682e9e99f1a310002e3fc71c715f3970337d.nq.gz
    ├── 4cd8b014d66cd0862bac768079cab95fb64f13db.nq.gz
    ├── 4d36157a395804db7c6a8902a065e5761cbb289c.nq.gz
    ├── 4dde89f6a0410e2dfd4af98c9414d2d437861239.nq.gz
    ├── 4e3410cb12c60c8cfd20dccf7106d32f01040519.nq.gz
    ├── 4e917e6aabdaeb3caf0ce07680b1d1bf9beb95e2.nq.gz
    ├── 4eb35a9c35c966c725b1cae88fa27ab793743042.nq.gz
    ├── 4eb916fd6e87097a2eb87ce47ab3d9770565505c.nq.gz
    ├── 4f318f7e55c95c2a70f17a8b9ff58d838edcdcf1.nq.gz
    ├── 5018b060b4e5bb82beec0ce00af724b4c1f0004d.nq.gz
    ├── 503659739ca045f06fa12c37b8f5ed75d535d2e5.nq.gz
    ├── 50b7d1be38d2df68611dc89aa31e203a17ee5883.nq.gz
    ├── 5142cf688e3dc5f168950d07fd2bb36c0e0c89fb.nq.gz
    ├── 531189a2f1225656d7223d8abe393b225c815118.nq.gz
    ├── 53ae1af75adc694b8f4e18b05624d2cb0b131d13.nq.gz
    ├── 53ed56691c9642ebcba16ca8a09d15b1c7144a0f.nq.gz
    ├── 5410ea04764095ae39a86c215d0efa470207d98a.nq.gz
    ├── 54a73b05a9677b24eb74ac91d2da7d0e139f0c2e.nq.gz
    ├── 54c67b332ab04478178771707e4597c600cb753b.nq.gz
    ├── 55ae2f49175656d5ba1a90429b4c4f9bdc9e31f8.nq.gz
    ├── 55cbfb31002807d4d661d63bb5a5e7a920153971.nq.gz
    ├── 561604ddbe1e704805513a104a7b435d677f98a6.nq.gz
    ├── 562597438bb6e29be27163036ac08e9415d809dd.nq.gz
    ├── 57614f9c967596fad0a3989bec2b1deff33034f6.nq.gz
    ├── 57a5e58daba1537b5df08dcb7fe965b316da6624.nq.gz
    ├── 589be4525e4ba44b953bf729f642450d9893396b.nq.gz
    ├── 589e15e341f2948c25324a3940c4e0be163ee87f.nq.gz
    ├── 58ce0e224f823d5721aaa73aed9c18b0b37e30bd.nq.gz
    ├── 58fd380fd06f5cf3a2d82ed93fb509f6ac46f7bf.nq.gz
    ├── 5a05f358df2ba8afdde789617a521f3fde77264f.nq.gz
    ├── 5a3d12b942d7336a07bd0c9f8a6afdeb9465be38.nq.gz
    ├── 5a634fba9faa653d441de23c0d6f4b3120ad7a4d.nq.gz
    ├── 5af8cd078bf1fb4674cac59cd4b553cc71813531.nq.gz
    ├── 5afdcdcedc18b2afe30d38b6680df58a83305981.nq.gz
    ├── 5b0024f535271949e5a4c3077ae0c2f05980f966.nq.gz
    ├── 5b06e9595ff9859e38a53a57aeb073b8f19538bb.nq.gz
    ├── 5b6fa001982750c6de23ad931e0a30f247e30aca.nq.gz
    ├── 5baa0b82dc0a201f62aca6132285c9d14e470ac3.nq.gz
    ├── 5bc1a247b555dafc9aea2131c4147edb194b258a.nq.gz
    ├── 5d73d9863c59d3930322ed6d3b3685efff3631b0.nq.gz
    ├── 5d90e888c514d4af8d00746e7f4f225e2eb614f1.nq.gz
    ├── 5ddd955a7ec198137905b11faf4f672058203e80.nq.gz
    ├── 5fdb48e513d2507facf2198758d30f565e0950e1.nq.gz
    ├── 600c50ebb92415fee0d9d38b8f7e84c2450f692e.nq.gz
    ├── 60faaa1bb659b640e6fe14588defda3d5e7243be.nq.gz
    ├── 6134fd1e994870ce4ce83603463237281ed7d050.nq.gz
    ├── 6163f38ee427311479af5c2a6e21abd281400436.nq.gz
    ├── 61a5ab9ab6e1da4d771f7ecec328b280be6ef53b.nq.gz
    ├── 6327406d395ada14226069e76a6eaa80fb5e0433.nq.gz
    ├── 634b23fd56b024e9f91d53a5cb93935c7e0ff06a.nq.gz
    ├── 6398405e53292b27a56a6e91f94231207be9db49.nq.gz
    ├── 642e7bb79105612d3adaf6f381f7df4ec8f0de19.nq.gz
    ├── 6492644c9b0689dddaed1eeee769d58037365a88.nq.gz
    ├── 654edbbcc2258378b7c6aef6232394cb5340e6ba.nq.gz
    ├── 655f8f39c561608e54d9aedf5f6b1d41cc473768.nq.gz
    ├── 65ace3df6b1aad8d6474a5275d502ac3183bd851.nq.gz
    ├── 65b5095fff049acd683c6081f5f979d934f88c17.nq.gz
    ├── 6667619cccb0b4dc9af6a69be3200cc66ce5a702.nq.gz
    ├── 666e320edbbd7eeeeedcd93a0b553af03d9fe442.nq.gz
    ├── 68f1564e748b3eda115471e57fdcd98d03471309.nq.gz
    ├── 69132d5fa3985196f8be0691800d6a30cd333331.nq.gz
    ├── 692a59a5434405d231b24b88792f0b4cb960da73.nq.gz
    ├── 69429927ee5db14b1d9c0753fccca8eab40b4bf2.nq.gz
    ├── 697a32b8b9aecbe8ba025253915711b60e934695.nq.gz
    ├── 69f66b666a1ca9b5aa3d76df8d83774a1132e59f.nq.gz
    ├── 6a14d89c9855650c46650f14c390ea7101bb0d35.nq.gz
    ├── 6b5be016553314e835fe7962e27dc3ea1d5d9c26.nq.gz
    └── 6ba18757e519a0fba98d4bc924384f8594dff628.nq.gz

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

[prettier/angular-html-parser](https://github.com/prettier/angular-html-parser)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
