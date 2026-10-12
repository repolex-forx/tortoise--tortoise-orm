# Repolex Knowledge Graph of tortoise/tortoise-orm

RDF knowledge graph data for [tortoise/tortoise-orm](https://github.com/tortoise/tortoise-orm), parsed by [repolex](https://repolex.ai).

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
rlex download tortoise/tortoise-orm
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a47e3f6c9eb787ad1cec9291926800e194d40062
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a47e3f6c9eb787ad1cec9291926800e194d40062
│           └── chunk-001.nq.gz
└── blob
    ├── 0007b80e640327906c49996e6521759cde0b3903.nq.gz
    ├── 012696d5da176a4bfd809b2dede6dc43a132acda.nq.gz
    ├── 01b11b96dea1729a465979a8a605cb39c485fa5c.nq.gz
    ├── 01ca36f84196f5bda545f18b31b586bd97ba782e.nq.gz
    ├── 0203a3bbfd7c4b95b4d45de949e2bf7e10a8455e.nq.gz
    ├── 02a99b7865f6fcfed618f4b72575de6c2155720a.nq.gz
    ├── 02ce6532f7eec397156a8eb6c40f6f46bbbec29d.nq.gz
    ├── 02d3fc3457f60efe7ebba60498751534da961564.nq.gz
    ├── 03d7ec53616ce7c712e57e7eb9067971b30840a1.nq.gz
    ├── 05afb6d17591182ba47b8b42941fc2c01871ddbb.nq.gz
    ├── 067fda66cc272925b461dc00b1ff8f661aef7af4.nq.gz
    ├── 0681a57aeb9d0ecefe59dd9f4141b053c2835ce0.nq.gz
    ├── 07035d877962c1600e884b9fb78f5ce9ddb2511a.nq.gz
    ├── 074a5169c41b15de457565520c9dcaf1251b653a.nq.gz
    ├── 07fb1258aa30f1c280c307cdf9b9d371e93cb3c9.nq.gz
    ├── 080312e2c4411fe7beb92ab23a8eb5e06c24517c.nq.gz
    ├── 098b240f78f72968fa87b53d158e1f0940a39651.nq.gz
    ├── 098d6231252c7e53e493697bdec7d6f6c600a055.nq.gz
    ├── 09de14f6bbefb088eb1b4d2af2877cee8367e7bf.nq.gz
    ├── 09e912ccd3f23cffc483776693ec54866b6e3f5f.nq.gz
    ├── 09ff0cd28e489a373982621c25aee8d4c385bd31.nq.gz
    ├── 0a7a59bccd2fee8ab00bd21004f941cbe731122a.nq.gz
    ├── 0b4044ea9da09aef6be0694ee3975ba07dc3192d.nq.gz
    ├── 0b80bb96a6eb3a768cb886e509ec9215b96c477b.nq.gz
    ├── 0be720e1e7c8014db0eeb5fe2041d290747a19ed.nq.gz
    ├── 0e5bdc850ee277bbfb1c0a9fba66704539113543.nq.gz
    ├── 0e9fdf6edf7244cdd41364043dcd5f00019e3307.nq.gz
    ├── 0ee55b5fd93a00d044afcff787e0ef0fe97f1d87.nq.gz
    ├── 0fa5088c33d18c39d216adee371442114dbeec2a.nq.gz
    ├── 0fab88f7142ec7f5c24a7fb11c1751b488566209.nq.gz
    ├── 104682fa4d771bd39fce467eccfb35c4c114355d.nq.gz
    ├── 106f6c1b479edfc78fa1ebd7acdcb4daaa2bac03.nq.gz
    ├── 11fbb09a59e3efb84d8263a1428c880540f8bd86.nq.gz
    ├── 1257c2eb75b72c25ecb8fa6353c89e1dfd7e7002.nq.gz
    ├── 13308cb487139844c89af808b68e3e88b1be884a.nq.gz
    ├── 150a9413b53a5aa289e9014d31c10f7b59fa2c69.nq.gz
    ├── 151c3f5da10c4f7ac9c18ca8fb382de4b7fa2927.nq.gz
    ├── 161651e25b9422e3aaa343755e598e82a16f0be5.nq.gz
    ├── 167d6b57a4d235da4cc60c05de4c9c513346377d.nq.gz
    ├── 16820818b5837ceed31115c00005dca52cd116c1.nq.gz
    ├── 17d6feab39964f3bf5cfe91eb3ae0294951848ff.nq.gz
    ├── 193742abe029a8a5c0a82b3a530fb77eb3e798d6.nq.gz
    ├── 19721a232f92b8d8e6033000d036bf2a6b6b4ac0.nq.gz
    ├── 1a483b0c3d7d93a60b85c731f48dadb01ea71903.nq.gz
    ├── 1a56124b9e00a53f24f72a3832c5e85c3aed54e0.nq.gz
    ├── 1af6b15bae5766f96ee49e38b67505bff1eaa540.nq.gz
    ├── 1d18f4c19cece515ca95777994aeed8c270cb336.nq.gz
    ├── 1d8b59389aaa73062fcb2ff065c3c768573950b8.nq.gz
    ├── 1d9723a11466d956f8b0dd482a87da9e0e25911d.nq.gz
    ├── 1e0f14322ec010efc25588256c8e4098165b6a13.nq.gz
    ├── 1ef0966a8746d47f07f5a01583f3ace0850cb347.nq.gz
    ├── 1f93e75ffdfb680159c9897966f82242529ed096.nq.gz
    ├── 1fa04269437fce4aac3ba97131df0edc3b0ad840.nq.gz
    ├── 1fa51e0b6d52c3c0b6f0cf2ef9ec358b6aa2bf6d.nq.gz
    ├── 2039c00545ffd2ec3037bc8d96455d2c05f7b37f.nq.gz
    ├── 2052d3eae906a4db6afaf34e536b28d2acd9e35c.nq.gz
    ├── 2179544c451160d787d164ff5f6ff93434df3852.nq.gz
    ├── 2193b0e6ce8e1b6d09ecb95e675ad46669ec62f5.nq.gz
    ├── 2287f3373eca05f1520e1992a87abd627bd0992f.nq.gz
    ├── 235679a13edf1e352bcaa5bdb2b3e54458145db0.nq.gz
    ├── 23a2b6a0617b2099726a5322d7279ac29b5c7955.nq.gz
    ├── 23fc17691e10249610fca7622b23e9066b758e51.nq.gz
    ├── 240777733a919d6072d7d321e2fa2f244f2ce724.nq.gz
    ├── 2461778d7ae27d37a4a31ae1406888093e9bd57a.nq.gz
    ├── 25ef289a742a48d2453dcb075b32822e30d0d1a4.nq.gz
    ├── 25f5543a0ab3da42d6733fa0cd0bad319105801b.nq.gz
    ├── 26d85a4e394f4c870bd4392c617ae1d6ac80bae1.nq.gz
    ├── 27932bb19c2b983341ffa8e4f75da0ad3644f27c.nq.gz
    ├── 2814179bf043f02f8dbb28d8948ebe32433f356a.nq.gz
    ├── 2841d2cd9f6f23b8565da4a8e1c18ead397ea868.nq.gz
    ├── 28dd1bf8062114d1d98608e87920f082fd89cef6.nq.gz
    ├── 290dbad74ff2eed19fe9559c0ca0a85f9f7574e8.nq.gz
    ├── 2b3664de564eaf0a1e8a4f03359df275a78e161d.nq.gz
    ├── 2be4a2bcc5f2cde8a918396f3434e014cff55f1a.nq.gz
    ├── 2d12f3d998a5f770167a95c716f7608ad5c898c9.nq.gz
    ├── 2d2040c19de433e04efc7bd294390f67c663bea7.nq.gz
    ├── 2e06ef8ca43fd5e47b01b85d93157151ba875e68.nq.gz
    ├── 2e1d2221869eba9b2f5ad13fb2d05d49f1d6807f.nq.gz
    ├── 2ed5dbd0ab6055e328b67094efa34c5311faa83a.nq.gz
    ├── 2f429993561b6ffe50174630a5094dfbc0d6bc9c.nq.gz
    ├── 2f4e317248641df2a154687d64329b9f23cbb2b0.nq.gz
    ├── 308ae60a51ec9be7d4cd4354b807bb68a902564f.nq.gz
    ├── 318598c5962e4325c00abad30a922965f1a421c1.nq.gz
    ├── 31d3a7b578f2360e928866b47fd21e58366eacdb.nq.gz
    ├── 32a5b647702a1d20aae602bdc87208533ed874f7.nq.gz
    ├── 3307eb2a357eece9707cbff9c11f23d17a82c564.nq.gz
    ├── 330a6d1393d4b2782413ca8644c974e285c075e7.nq.gz
    ├── 338d6a000c7d7ddff4e5688552f1270e68bff2c3.nq.gz
    ├── 33943471b7bdf447a168aa4c09e8b9e4aa247d6c.nq.gz
    ├── 342a004a8c0ad9ed2060304aaa6ed515a1137a7e.nq.gz
    ├── 35b4e8554dcbbc88b5c1a267b64ca3de3be51e18.nq.gz
    ├── 35db98dac7f18a116a4b16c8a7fb18b97a2b64bc.nq.gz
    ├── 36068105214cebe3fa467422d7e54bf8fbbbd723.nq.gz
    ├── 36bede415a2dd7524bb5277d4c277851c339d9c7.nq.gz
    ├── 36fa2ec2a730d0d650895f8a2659cb5b65d63c29.nq.gz
    ├── 37802ea7b33c92321fa0a218e16750938741e322.nq.gz
    ├── 38ef0b0732983e48254f41fb3e5517b1ed94494b.nq.gz
    ├── 3901a1125b190eaebb97ee8d5c76575545aaf66b.nq.gz
    ├── 39908ff47e5b5fff54f2719a27fe583c7ad6e4b6.nq.gz
    ├── 39ae6e862c22c6d2c1191c215055f6fa30094958.nq.gz
    ├── 3a04ad244534ff6fbf64a466c81bda143ae197c1.nq.gz
    ├── 3a0bec2d3dc21917cd3335452870f7d030dace8b.nq.gz
    ├── 3a48b4310556c4e0026181201616f88594cdaf5f.nq.gz
    ├── 3a5dc283cb11f073c22e5cfab4e825f65984b076.nq.gz
    ├── 3b76829b25eb08641714b6766e0e9e2098b41ecb.nq.gz
    ├── 3bc54795e83af0f33540946b9c7eb3ca01c924d7.nq.gz
    ├── 3bc8fcc1d9a9d9b22e8ec0233fd241c47e00888c.nq.gz
    ├── 3c9106db4cd60cd0bc37e75e89181d8e051bf8c7.nq.gz
    ├── 3ccd4d63978592085770e180df6b1c9d66751a96.nq.gz
    ├── 3d343e10fdf64ad347b9950c09c7c630e3a46f61.nq.gz
    ├── 3d8c653a526f07acacdcc713597b0ee83d366812.nq.gz
    ├── 3e0c84a958e62501550403a8f7a78d37d1350a15.nq.gz
    ├── 3efeece2933187e922eecc9fe52ccd1864683567.nq.gz
    ├── 3f1f86c9154224335da4be800fff0dff3fe4165c.nq.gz
    ├── 3f48784098d8a3a078929297a09f4318a8d03280.nq.gz
    ├── 3f4cbfd00348659c22f293844101cea6f826625a.nq.gz
    ├── 3f80a6b8a0607ff4d5beb206d19840cba66c4559.nq.gz
    ├── 3f83c03c914777ab0b97cd15f00051a76c6afb24.nq.gz
    ├── 403f222986bc99ae64b8586418a82d3c9328f328.nq.gz
    ├── 4101f71ec02779cbd37d97d3f599ab4aa5cf1ea1.nq.gz
    ├── 41c7da61819658944132e2dd69ad2f1f594a295f.nq.gz
    ├── 4251b879f465f3c4464b4be4b55b481412495895.nq.gz
    ├── 42c3ff7e20720bc762bd684434c429d1eb15a44d.nq.gz
    ├── 4391df6e30517300096d5569f10a9bad68a8172d.nq.gz
    ├── 43a999c6d085456d5ef9cf7b4d3a9ce3eea545a1.nq.gz
    ├── 44d2482058e06f92d0b585edaab91f0a5742c549.nq.gz
    ├── 4581055a77d9b006a3f633fc06b4553787ff4bbc.nq.gz
    ├── 459794a04f2b318d255d10217a62496157b5a6d1.nq.gz
    ├── 46c82b3a97c72d23c70f24d4b16e113693ed2063.nq.gz
    ├── 46f10c912143c99e6dc9330bcf584260536be7fd.nq.gz
    ├── 4788e6510b09dd3f21ab9f69dbec982173c5abc2.nq.gz
    ├── 47a91cdb56b50598038d57987d82f3ecc58e391f.nq.gz
    ├── 4844651bfa54dae97970b7d11e5257a738d7b783.nq.gz
    ├── 4846751b895845bd03e92b585e6168de5247ddf5.nq.gz
    ├── 487479a6a1cb8a35af7144b1d0966e12769dca61.nq.gz
    ├── 499ce11efc84dfffaee067f905664204bf210308.nq.gz
    ├── 49ef2557b16e4c1443f257beab7762f2ae57644e.nq.gz
    ├── 4a85ffa9f5b0be65c47e836733d6a475f32ec8f1.nq.gz
    ├── 4b278b09af9d92b072a6b28c7d2b91aec80bcb53.nq.gz
    ├── 4b283aa872a26c4a0cdeae0d103b750bbf07be16.nq.gz
    ├── 4c45b23e186956afe4f0e3ba3eddf73c1c54a8f8.nq.gz
    ├── 4d1604e589a23f75602a80528e18f6072bd4865b.nq.gz
    ├── 4d1e9eaf14c6a66e8df0cdf6b21287aa78ec3aa6.nq.gz
    ├── 4db010a46b74b68f021cb84eb2554f7e01fe4c89.nq.gz
    ├── 4de3e09db41eb4878d7ee5b085a537e1af0c233a.nq.gz
    ├── 4e44b8d5ab0e5c245b93db75ce87aa1fd0e94dc6.nq.gz
    ├── 508f9e3f4751b56369647eb4bca27e0e8fd710cc.nq.gz
    ├── 50d6309a984c7bbe2a722ca6c52b03c97ee6505b.nq.gz
    ├── 5285874d5baad3ccf0c73c067eba7dbf1c8dbee3.nq.gz
    ├── 52a629f425372971cab7d6d0640ef639bb1f5e6b.nq.gz
    ├── 52e03b4f81e8ebf12aa985dbf06cd781b6997223.nq.gz
    ├── 53047df56b0a36955cc6ef843d78e09f0e4fa124.nq.gz
    ├── 536a1d7a684210840ea56f2fa55654c298b5d87e.nq.gz
    ├── 53bef98da65eea246c1e20e70fbddcf57b45717e.nq.gz
    ├── 545934f31f244c466f2c5267826deada7c4a44ad.nq.gz
    ├── 5531b0eb4097fc2887a182ea43435172076dfce2.nq.gz
    ├── 559dab0a104df026b9ffeb83eaafc2707fd77f92.nq.gz
    ├── 55c1f18aa4853d0e9f76b224db2c2a63977ec551.nq.gz
    ├── 55df49b7a46d972d4d400c7dc0d278956ce8dba2.nq.gz
    ├── 566295d4144070129e0d76bb7b4890b40cc89061.nq.gz
    ├── 56f2c0e6f93a45f0f2fe8c452371d6373b348f94.nq.gz
    ├── 570dfe112ca16961f9c016b9a58e45f00a274622.nq.gz
    ├── 580f04a11cde10704f01596413b76767ea65d30b.nq.gz
    ├── 5986e580f148eca6e63aedec9a39aed558bb6763.nq.gz
    ├── 59a1430ec158a18ea2cca38caf897a7dd17c0325.nq.gz
    ├── 5a00b7d90176ec0cc805565258a5ebd666933097.nq.gz
    ├── 5b34238bfa31ca29b5d23a84b124bd040c50b41d.nq.gz
    ├── 5b9bd009bcb63bda1529214021efc6b74c40badc.nq.gz
    ├── 5c75e728b2d30b75baa146a03169a8932d09ec8a.nq.gz
    ├── 5d1f69c5961bab1503fa27223f90b0fff1e563ef.nq.gz
    ├── 5d653dcde81e22fbafb5344a1ac33ac69ceb14a8.nq.gz
    ├── 5e41b69f5169cc6ddd5d3b6183a4dec1566d9393.nq.gz
    ├── 5e95275b629c09dad356d42b90c87be14d2bc5a4.nq.gz
    ├── 5f08f3cdca34fdbb2aa3f3f1ba871eff0db78695.nq.gz
    ├── 5f4b59cb637b115c2f28a6bdb8473d619391698c.nq.gz
    ├── 60044435c3962f04b4fb82bb97a65f95e8f02a26.nq.gz
    ├── 60f7538c58a72af2ab8df1a8b94e7d6e8f90a054.nq.gz
    ├── 61792ce5cf2cc9db23f9d44c26174606c074f0dc.nq.gz
    ├── 619f9079b3ef0b1e5d841e3246521468bf93acff.nq.gz
    ├── 61f77bc03538e8534d05e8a7669833d5addcfe24.nq.gz
    ├── 622934cc5b6bc59207104102df7f78949643c7f8.nq.gz
    ├── 62ea9e24c2521ecda8f46d3574f08db9bd701c2a.nq.gz
    ├── 63098bce14d1b862d77bb466d997a89968032ce9.nq.gz
    ├── 6327f902c509eded87d26540e9683a02f278ae66.nq.gz
    ├── 637ba142b0300882ada5321f8268978695814add.nq.gz
    ├── 6382610d92b05eb945432ebede8851ee83a538d8.nq.gz
    ├── 63a53e50f899e1862d8c5095b13a3828f9fbce60.nq.gz
    ├── 63a5b4c4f59f323bd7d0898b945cb1c464c7de8c.nq.gz
    ├── 6430a5958729fe664942343670c0640fd368874f.nq.gz
    ├── 647c594563377064454fba9a37880769ec02ef95.nq.gz
    ├── 6525c695fa8cbcdf5d28f40b703ef408efa740b0.nq.gz
    ├── 65f191fd94cc137c868560ba6da8d1dc84335550.nq.gz
    ├── 661486844b0f7b8db8a386a211844f7e7d5e459e.nq.gz
    ├── 6659656a9e054ec852512b51e7f8e552b9945081.nq.gz
    ├── 668909a1b4bdf5c58f39c9e59ca16b8da124a33a.nq.gz
    ├── 66b93ad63afd047547620cc7675499d13f3616fa.nq.gz
    ├── 66f7c64478e7427790f0ef8203305cb73eb0158c.nq.gz
    └── 67a9dac31cf1a3151c1a84421ee39abe6eae37e4.nq.gz

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

[tortoise/tortoise-orm](https://github.com/tortoise/tortoise-orm)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
