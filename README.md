# Repolex Knowledge Graph of modelcontextprotocol/ext-apps

RDF knowledge graph data for [modelcontextprotocol/ext-apps](https://github.com/modelcontextprotocol/ext-apps), parsed by [repolex](https://repolex.ai).

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
rlex download modelcontextprotocol/ext-apps
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 82221c0c8ce7661efa6771c9d461511b1650495f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 82221c0c8ce7661efa6771c9d461511b1650495f
│           └── chunk-001.nq.gz
└── blob
    ├── 005ecaf75b23d0f059703cb5930d4ef796f54e6f.nq.gz
    ├── 00c0d52b2e7fac9d2a247c94165571f4d5549caf.nq.gz
    ├── 00e4801303a075b8051e430bda8ab663f8171b54.nq.gz
    ├── 0155dc079279eb2016812beacc786536ad5a222f.nq.gz
    ├── 0236c5561369cf65fdf27d1ce17f2a051247768c.nq.gz
    ├── 02c03cb5944d17be8db653e34a25351d82ac3fab.nq.gz
    ├── 03175e4e51c4a15cdb350824fa31c22e3e916697.nq.gz
    ├── 03200adb76a52c3ba3afd17c324f360fd4a59692.nq.gz
    ├── 0370932f9a03b6f85edad691d8fb3eb5aa0f1902.nq.gz
    ├── 03d9f85d32bf343db07e6e472d555d0a7be41c58.nq.gz
    ├── 046f1279c8d23156a3f9a604088c7568d9711bda.nq.gz
    ├── 058fb3f2a3cc1149a93f7e36b2de76fe4262a6f9.nq.gz
    ├── 09176142b04599107fdbbe72a0113729a806cccf.nq.gz
    ├── 095ef8dfdc53b66beea2fe747d5a03f47555754b.nq.gz
    ├── 0ac8e6cc1f17a1d150ed4f0e957a0bcd46486bbb.nq.gz
    ├── 0b2a5eb4d8c331d2c5466adc64f3ef1d17653d94.nq.gz
    ├── 0bd09dd05a6760e36ef73dd5f4dbb3a1d1fd4ce2.nq.gz
    ├── 0c45396378b0e4ae5911563ec048e95906a04c1e.nq.gz
    ├── 0c5399b3e4596c60c38d176b018464b8229cf3a0.nq.gz
    ├── 0d0453f477116c71be4d7940902c1ab7ae0c02e8.nq.gz
    ├── 0d385f51997dc381f8fe4fa52a94cebccb2b3006.nq.gz
    ├── 0d5b6f114313158955ea0c57838b639a97b75d12.nq.gz
    ├── 0dff91215b4bf651557c63f3f2e86891ba6d92f9.nq.gz
    ├── 0e0d416f6daa64cf067219ae609d72f3037d6d84.nq.gz
    ├── 0e6e571d879e5c82dfd347bc464bb9ba20b86d01.nq.gz
    ├── 0ef36d6f13b6e502a26203573ed14b86dd44ed8a.nq.gz
    ├── 0f4cf849b26c20b4a8cbcbd4826959854892feb3.nq.gz
    ├── 0f7caf60b5eef1ad1e9bd143b6602a63131ae0f0.nq.gz
    ├── 0ff9f049f1e431e0ffd15df0c65262c0d57e484b.nq.gz
    ├── 11677e6ae02e0e57790c57be82f4207dfa7f39ff.nq.gz
    ├── 11f02fe2a0061d6e6e1f271b21da95423b448b32.nq.gz
    ├── 12d392e936b4cb5245056fe3ef88b9987dc71e15.nq.gz
    ├── 136529a0346fc0466e424a67d6836dfb17772fae.nq.gz
    ├── 1542cecac3fd1bf0bcaded4176fd3be4d4a80ae3.nq.gz
    ├── 1548f7e8f6da4414fc5aa662be973d72be15a71f.nq.gz
    ├── 181858e19d87c736d218e464175c19db8523e1c4.nq.gz
    ├── 182f01a9014ddd01c1b4ab03dbba1fbac60634a3.nq.gz
    ├── 183f6c0c54c803241fa3bf523d9c3c326bc5b6fa.nq.gz
    ├── 1886326266fbfc859d4a2466d31e403352348e26.nq.gz
    ├── 18ad40e8cc94e33f459bd688653cc7b0f58bcd35.nq.gz
    ├── 190a1869672144d2df64dc7791ee468352a32518.nq.gz
    ├── 1983373c6f27e7d3dc36423859481888a1a5e992.nq.gz
    ├── 1a10d2d542504861294e73e97504d0a097c632f7.nq.gz
    ├── 1a92a3c3c4c134702a2f782cf35ab556197b4aab.nq.gz
    ├── 1ac4db48514c7546c15d5a31a84aba5fbd315f3e.nq.gz
    ├── 1b64ee9df0d0634046abfc7477eddc64a307fe54.nq.gz
    ├── 1bd9783c6d74421cc02a3278a7d863f1ee6a9106.nq.gz
    ├── 1c101ea936983a1634e032e4998efad66a6547a9.nq.gz
    ├── 1e6e169ddc1c6f4cb5d360323c09e41e1d0f4756.nq.gz
    ├── 1f901b285c2ab907cfb3947bbb1264621e209808.nq.gz
    ├── 20169c298ed31e38b92fe1489044ff9940e5e60a.nq.gz
    ├── 201fe8d75ff9475aa028857cd88f0b0abe99a488.nq.gz
    ├── 214b227c205240488ede84a37ac58f3a2fbb2d67.nq.gz
    ├── 214c29d1395919ce175f26d140526368127981ba.nq.gz
    ├── 219b947187b121b56a16a3e884be8333e920a442.nq.gz
    ├── 21c5e18af5b72617cd42ebd051eded581e48398a.nq.gz
    ├── 22d5d9f0ce19e957b483fdaa34abecfb7ee64b44.nq.gz
    ├── 237b8eba917ae54d6c0e9160684677b5fef681ea.nq.gz
    ├── 23a9955d31bee0990bbbeac73faad0430ff6957d.nq.gz
    ├── 246ed7d9b09b04af053e1c59c2e2d37484decaf6.nq.gz
    ├── 2636ce8d891460a3b1342218f447260853bb73dc.nq.gz
    ├── 27070ca611c22d3f6c8331a5149ed6f3fdfb00cd.nq.gz
    ├── 27eb28f33b2bba4a09766e318621ea4fa3461a3c.nq.gz
    ├── 281729bd4a53aea2ed8ae09152b4b038676c3734.nq.gz
    ├── 281a356747180ae482935615180370fb65db9f5d.nq.gz
    ├── 28baf8106d03a0526a42c55458421bba3de4a9f6.nq.gz
    ├── 29173341d7b6e80b94167bdb03e2f545a37b3cc0.nq.gz
    ├── 2a24d21bf5bdc6fb046b3ea75b0d67607d696b32.nq.gz
    ├── 2a3f8f91de07b204a6c1b5e5b345ca71597a741c.nq.gz
    ├── 2b5fbef9a153aedfb14fb01b4976ab0c09fd4ebc.nq.gz
    ├── 2b902e3d642c198e02d7f07d09ed8d0730c31c73.nq.gz
    ├── 2bee370a13ad84b2a728f4b144c4fef170226478.nq.gz
    ├── 2d78b7b33593b4ff95f2ca2121448c2fe0e16d1e.nq.gz
    ├── 2e10abc75b80580abe01aa38757747cc4e7a00e9.nq.gz
    ├── 2f1814f766337f30486791a35566f2b61dc1a9d3.nq.gz
    ├── 2fe7e627183f5a9b0cd346a113d47a19dc076205.nq.gz
    ├── 309467bb33d53dec6643be7e76542d3936be85c2.nq.gz
    ├── 31dbfa1a614072124b9c72412a77326fa4128218.nq.gz
    ├── 31df301033fea6ba540887601817fa5485adbd2f.nq.gz
    ├── 34139744ee5dd883c62d51e1115641a6a539e596.nq.gz
    ├── 3497a85d94c35bbf0ec27c60f2973dc8900ed16a.nq.gz
    ├── 351a8ec21665c6f7853eeb0cecbb0b45eb23727e.nq.gz
    ├── 3599b9a6ae57f7ab525dfc672b74c090bb693330.nq.gz
    ├── 35e01a7a3b602f88e96d3793aa1af7234f7a95e6.nq.gz
    ├── 36e35801b0856e04504f65aae323052825bae7c6.nq.gz
    ├── 38b4bbfb07e30b19e0a9932758788a446e40a687.nq.gz
    ├── 390f6447eec442263b3b6c2c7b050dfe38d92d63.nq.gz
    ├── 3a170cdc26f0174995a43b89747c060aa00c7e20.nq.gz
    ├── 3a28c411fc03c9e06af0ad11a22136dc49967a5d.nq.gz
    ├── 3c143ca9fa228f65302f98c5551898fc91daf58d.nq.gz
    ├── 3c6b81661d3a9392f73c75842a7059874e362eec.nq.gz
    ├── 3dc851e676d04cf17427ddaa63dc066f7e1e0619.nq.gz
    ├── 3ecbdad05dec2de61cccaff34009a264c2626da2.nq.gz
    ├── 3f7859c20bf861e6350470df35b4b2565715a1ef.nq.gz
    ├── 40e63ff842429b91d179dfa66bf0c39201b0a906.nq.gz
    ├── 41ebc22471018b62051269ba2c8a3543a54d6520.nq.gz
    ├── 4349361f11a0e32ed4f42f8f1c01eb52890a3fe6.nq.gz
    ├── 43811a2f99864c4e1049dbb5bc931f1e98f86b76.nq.gz
    ├── 43fef209d449c5456808ec82da8fb012c3b9b678.nq.gz
    ├── 44fee0c670abbc575a1d9b99e11d0cbf8c87f891.nq.gz
    ├── 451673dd9cd4597e4fb9bb2fe8efe756ab7d521c.nq.gz
    ├── 45e0c74580f2a27f2201fc8792651cb51eac5dcc.nq.gz
    ├── 474a625594493376e132615074d81a23f8d7c03a.nq.gz
    ├── 478c5b80710ba6fc8be41ec1e73ad0cb1f8ae4bb.nq.gz
    ├── 47ad6234ff8c22f00d3291ff14f05c0f4b94fd92.nq.gz
    ├── 47dc3e3d863cfb5727b87d785d09abf9743c0a72.nq.gz
    ├── 48435e342f4eabf058eba9fa2d563f87c0410a18.nq.gz
    ├── 4849aa2a4097a20371cfc30d621649bae569599d.nq.gz
    ├── 489d0b0de3636604db414ba5663b117aedf27cbd.nq.gz
    ├── 48d83647796120538b61546dafa3cc965783e066.nq.gz
    ├── 49e491555415d0fabe94ae6b55c967be2a02b117.nq.gz
    ├── 4a93985763241755401a10678395303de4e720ba.nq.gz
    ├── 4af5aeefbf4541201425cfe2e6ae68a3dada201c.nq.gz
    ├── 4bb898ec47b7de20206b8ad46e4aac3c742cc5b6.nq.gz
    ├── 4bcc1d796faefa722c43eeddd9a08dc6aecffb19.nq.gz
    ├── 4de7331877b86d64d53f5d0edd260737bc996c4e.nq.gz
    ├── 4fd3cd7f65c5be40140d481400786030819543f3.nq.gz
    ├── 50292420096eb98f07f3945dc30325fe8b17a2af.nq.gz
    ├── 51a82dd8f111d8267bd6a41611342440214cfe00.nq.gz
    ├── 524000833018084b18e9972e09076779843267ad.nq.gz
    ├── 52a99ee9ac7f2e34f1fa6791dbd0e64415d27022.nq.gz
    ├── 52ba7b11f73497c2b15855fc1f647932a92f4c85.nq.gz
    ├── 53c93e54757437932ac755db58bfe9f031ceecd7.nq.gz
    ├── 541495c72efab36ba568f30655ce282f2f90b8ff.nq.gz
    ├── 54a986089d87bd6ba30d5ae2011f8ffc38ac9440.nq.gz
    ├── 54eef27a6120c9ebbba6f76a8d26abfb48cbd69b.nq.gz
    ├── 556b726df891d978af463a6ae6bf939e730241d2.nq.gz
    ├── 559ffadef219dfe4791414772c42775f09cf075a.nq.gz
    ├── 574809bd869a2d498b1f493a1f61b991a3a2f96a.nq.gz
    ├── 5780bb706a444b39bc58f18b9db23fd81c90f057.nq.gz
    ├── 57acb8e1295211bc861d6f727e4a0f61bf87da28.nq.gz
    ├── 57d989fd06a1de843e43065045973115e75dc2fe.nq.gz
    ├── 5a473f02d5b8f842a382530f5c5d449136f8f330.nq.gz
    ├── 5b5486bc745484e418eb80b72313ff9fc1a2ea18.nq.gz
    ├── 5c745acb5334760af50f80aaafd94f4e508e8ee1.nq.gz
    ├── 5e632370f8ce41a51e7271d3940a92abda8f61ee.nq.gz
    ├── 5f680ffdc9eeea012ba1838e9de2a19fdb9cdc25.nq.gz
    ├── 5fad055a0aa2fd04ec51f848d19d6722fcb276ac.nq.gz
    ├── 5fb7b0be1e2438e0f704be25a1ac88cdd5fa11e8.nq.gz
    ├── 609891828fa772a9a98020c30f5a25696318b21a.nq.gz
    ├── 60e7c355fa989a88c3a2fb1a51e06c5b70dab861.nq.gz
    ├── 60ea7ea29b14461aed3532d79b10fae0dc87a5d8.nq.gz
    ├── 61361e636f2e7d8883d1874fadaea9f9b18453da.nq.gz
    ├── 61b6f60f77262c4443b177efd8a0a21a4bc2c45c.nq.gz
    ├── 629ace85f147a054cd0a02fe4ca80ab4483f5a32.nq.gz
    ├── 6445d8cabd96427af41ba54832e9c36f85eaa324.nq.gz
    ├── 65c878fd51608a7c698cabe1c7a58c22dbdedb05.nq.gz
    ├── 66af07e9623de31f86b61773e6e68d25516df409.nq.gz
    ├── 6752d9b196d27fa64722e99d5d748436f237f73a.nq.gz
    ├── 68f32ee16c8c4d9dbb33cc71d273f1c27fec36a0.nq.gz
    ├── 6a75ddb07fe717a0a078187043b1917ea879020a.nq.gz
    ├── 6b5084a3a1134d2c97ca9fd51108b98258dec73f.nq.gz
    ├── 6bd22151ebb97fce6d7d8f976688ead901bb2219.nq.gz
    ├── 6c63f8520be5e0d7bfae5280c22586af9a4bd9f5.nq.gz
    ├── 6d27edf9ac8587113253213fcb796a7730ff6eab.nq.gz
    ├── 6f0dcd7f3ebddd7a700cb30f5524c2130739b2cb.nq.gz
    ├── 6f1dd93d7a948d1e9b5a8216f13c4ad7e5a4e283.nq.gz
    ├── 6ff6d9979af57038bad9b8c7fb3d984d45939b17.nq.gz
    ├── 707ea7f5e08ce138c67326945c085206c68ae8d8.nq.gz
    ├── 7235ceedad02d86775c24c3d9711fef09485c61a.nq.gz
    ├── 72552e2a7ee63130c7c4c3ae5afaa501a829cf6a.nq.gz
    ├── 734ec0cdb3476139fce042ed635afbba53d20041.nq.gz
    ├── 74b57514cbd181d459c39852d84829f6bb42bb8b.nq.gz
    ├── 74c09051e12e5b0076ca7811e20a07d151524e60.nq.gz
    ├── 74e070db403504d5a9a14e9b30b5080ff5f00648.nq.gz
    ├── 762ac77a92d43232fe79776d5eeb9459b26aa37f.nq.gz
    ├── 769661cc1aed92a8b0dd460493db107b6c517d8d.nq.gz
    ├── 79a74ed260f83651d9214686726295374b49da75.nq.gz
    ├── 7b6fd5277645b96ccea49b39b97c1338e7c2c718.nq.gz
    ├── 7b80eaf120f59e91e440855c38efa38446c7eae0.nq.gz
    ├── 7cbb849dad96aa9b35f46ef9cdb0ae6b9126927e.nq.gz
    ├── 7d475efa0fa2df6aa2cc16c45ce05c2f4aeabc6d.nq.gz
    ├── 7d8ba2c3be16040773a785630e06037edbfe5ae1.nq.gz
    ├── 7e3787e40d871cb026a7e418754f14d0b697b23f.nq.gz
    ├── 7e388f0a6b0ac842b71d116cec26355c2fde035d.nq.gz
    ├── 7f370a86827edabf25eb074f063e47ff285d129d.nq.gz
    ├── 7f9e1201f3d2a9fe6e57a22e8d6d986bcabdbbdc.nq.gz
    ├── 800b2249963f897f6a71ded58b0ca2439e9129e4.nq.gz
    ├── 801291f469c1ac5ce3a94c048888d68b5d5ce53a.nq.gz
    ├── 80383942d0b43c22fdc52069932108b96212e6f0.nq.gz
    ├── 80e17056868f17ebe0ddab61c59a72176ba352ff.nq.gz
    ├── 81a590173de2e59c56cc875cf5552ed91e9a4a18.nq.gz
    ├── 81ff8ad0bd50bba169ddea74521ebdbeef555966.nq.gz
    ├── 821e4074cc5f36bbe0a9539faeed833562a95b4b.nq.gz
    ├── 83a7b404191f03e674a1515ffd9ce4f3e4a21e71.nq.gz
    ├── 8420e81eac9f115acd5ad5f3e7f869893fbd844f.nq.gz
    ├── 848e1c29acf0d739b33cf294dbc22cd6bc733f24.nq.gz
    ├── 84fcdbd48674375f360039007539a80aecd3021c.nq.gz
    ├── 864a5c47ffeb8054cfe5c8aaf1f8b8dead87c568.nq.gz
    ├── 869fec089675dd57b253c5a9938d266f53b7cae8.nq.gz
    ├── 876655e180fc43edd0758144fd91701c991afc3d.nq.gz
    ├── 882b10ac09429acb1dba55609da2b10fbc81b80a.nq.gz
    ├── 884de26517f53b1267ea68c15b4bb99bf558e4de.nq.gz
    ├── 886e815701b1d46614dfe14bbcc01e0965d5ae0e.nq.gz
    ├── 88f78f67cb3f42b3f781a972900d790e864db634.nq.gz
    ├── 895073b8d691d1fb85918a6669643ffd443601fe.nq.gz
    ├── 8978ab615c412db4850122aeade9e87c0f034582.nq.gz
    └── 89c6c35e7cdd087e31214fd49c37e577d94e39b9.nq.gz

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

[modelcontextprotocol/ext-apps](https://github.com/modelcontextprotocol/ext-apps)

---
*Parsed on 2026-10-09 by [repolex](https://repolex.ai)*
