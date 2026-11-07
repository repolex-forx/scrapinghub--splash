# Repolex Knowledge Graph of scrapinghub/splash

RDF knowledge graph data for [scrapinghub/splash](https://github.com/scrapinghub/splash), parsed by [repolex](https://repolex.ai).

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
rlex download scrapinghub/splash
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ab28b0233c245461189881f1f5656b96371a4b40
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ab28b0233c245461189881f1f5656b96371a4b40
│           └── chunk-001.nq.gz
└── blob
    ├── 00582f77581f079a5a750b4d7d15d0200b0883c9.nq.gz
    ├── 009e1abc673256548452428e8b6b24d1917efcd9.nq.gz
    ├── 0189fb59e1f6d8592d2582a76fcc8fcbf5514367.nq.gz
    ├── 01f716e5c97c3332633127b1a96be5ae2adbf645.nq.gz
    ├── 029c0fb9ce22b597d1a9590bc314f64ad2f0f55e.nq.gz
    ├── 02fa17a498946f9a46080531255057b2143fcc55.nq.gz
    ├── 0399f94dcc7504a9e6df4006692516c7a487a865.nq.gz
    ├── 044963bbb3dec4ad4fc6d06c0736e089a9121eca.nq.gz
    ├── 062dcc40f594e5551943e2fe062694bf9df57112.nq.gz
    ├── 06608f6c33b0a86df6aafe648e4a050d7817262f.nq.gz
    ├── 06a44925684e46887cbd0ec7f351b177b2b8b98c.nq.gz
    ├── 0adef39bf0f02685bfda35045d98a83a83c1f312.nq.gz
    ├── 0ca646226441deceb9d180a244cefa57e36a4a36.nq.gz
    ├── 0d28ec46cb42928b98f54f4e5722af581646225f.nq.gz
    ├── 0d5d3198610b7acff306dd274c3e3bc4d930278f.nq.gz
    ├── 0f4d6392dbd5fd51fe389d775b2e74307d2a817f.nq.gz
    ├── 0f74becf0795df615ecd7eb70be0e7f3b3055f0a.nq.gz
    ├── 1240b151d34cb68f996db54fe25dc71cc74ec122.nq.gz
    ├── 15d952d7415d862739c24f86555cc41fa2b4bf91.nq.gz
    ├── 165074a604eb705252319fcdcac3615b8de32e37.nq.gz
    ├── 16ec5a5be2014fbb79dbe094f3eb2acf6149ecb5.nq.gz
    ├── 1737b78d98373171e2775b6d4baffbe978f1e8a3.nq.gz
    ├── 175654dce4cf1d90573cad34a72da3490ae6c60f.nq.gz
    ├── 191a7b7d37b41ac95bfcb6a3ae45c2babcfe2f1e.nq.gz
    ├── 1c3bcb206914a0bfa1f3c3f4a17d0d708d2726ed.nq.gz
    ├── 1ce9028914e89456fd7cac49a9341898633c5a70.nq.gz
    ├── 1d0940995bc405136fda105c0193f1c403d02efe.nq.gz
    ├── 1e55109640fc2f44a8d2344268e4aedcc4693abb.nq.gz
    ├── 1edc23d539da1437b2c4b410e10aa182acedc139.nq.gz
    ├── 1fdcf1ae965cdccc3854d4efec15369231c4d4e8.nq.gz
    ├── 200883172e01c2b733204e418aefb7b886fe60e4.nq.gz
    ├── 200bcc1626d89ef2e4793b41c1d373628e1e4732.nq.gz
    ├── 20ee860a5196a817240f655eabf3f15847bdc696.nq.gz
    ├── 2361a6b8ec2f287f0180254fe7c29797d527e997.nq.gz
    ├── 251b40dd4354b202f0cd136a2e975163dcaf5c18.nq.gz
    ├── 26f695f1ce201cb2bf4edbf88df902190ca42ed4.nq.gz
    ├── 287fe871d5a925732ce3d80569d5adf500b6dd52.nq.gz
    ├── 28844d398536a60a90d611b510f47107b26c701f.nq.gz
    ├── 28e1cfa7337127e979d3713dbdbd70ed3d9f6482.nq.gz
    ├── 293e608be884112167e9c9e07d10dfe5a456cedf.nq.gz
    ├── 2caa7fb776fa22b84c9ed22c6c9ca26dd1da2f79.nq.gz
    ├── 2e66aba7fa7dc3efd4b4171a8f7ce4931b43b205.nq.gz
    ├── 31b75ad835b2074a08614007193fc8dc832ed7e5.nq.gz
    ├── 32bc6546995d09c9b266eee64f3290d8c7a3973e.nq.gz
    ├── 3503bf9c38e82d4ab13203ef66beae23915059d5.nq.gz
    ├── 35a26d7c46cae561fc2cddc2bb2fe40782f492b3.nq.gz
    ├── 3819c7bf9dea4df5fce813e39c4823b5f985525c.nq.gz
    ├── 385ccc8495f8c16446d2137a89644bbc27a78093.nq.gz
    ├── 3a71d5e3eecd8aa2eedef47d7aefbcdf49a25262.nq.gz
    ├── 3d111896cc2d7be720a4b09451f41214dab09741.nq.gz
    ├── 3e0979990c0271a0ddeea76eb244561ddbb1aa02.nq.gz
    ├── 3e0cb05f3f785667dcc4ce0bcbe38e46e13e972f.nq.gz
    ├── 3e5fcfa34be6fee872a28ef33fd3b9783e4657a7.nq.gz
    ├── 3e79b59f427b66e9d393a50be0c8dc7333b21e49.nq.gz
    ├── 40a96afc6ff09d58a702b76e3f7dd412fe975e26.nq.gz
    ├── 421f32180b2c6afba2e31ff6d3f37c5a005226cb.nq.gz
    ├── 423f415c25a654cba4d665c6a799854ebbc9bc70.nq.gz
    ├── 4295d0c6e2c9d87e711f891e6c4a6098ae175673.nq.gz
    ├── 44eea2b7c9afaef67c58ff12cc1b5ddf812ef719.nq.gz
    ├── 44f751fefbfc151d43217abfc5d484656838ffc9.nq.gz
    ├── 450c17157ab465cd4afce69e6738baa142fa0923.nq.gz
    ├── 4b82c9799636bbc9384dda1caa74ccc121808031.nq.gz
    ├── 4cfa483f1b23c34ff80835717c0de8cb9e54b461.nq.gz
    ├── 4d784811da07d8c52dc6ef1bbb56144e358a01af.nq.gz
    ├── 511088d8d60b9fcd5cfb2cd91faa46ffa8bb735e.nq.gz
    ├── 57fe23134377007347d149edb9654da8c36c633d.nq.gz
    ├── 586e68c3114c9e40844301d4625cc3581b4d33dd.nq.gz
    ├── 588c694fcb93d5e23b3022c127966606ad239a15.nq.gz
    ├── 5b7376397f364305ee137bd9383cc1debeebdab7.nq.gz
    ├── 5b881c1f9b9393b91c87d3c608b060a130162806.nq.gz
    ├── 5bd42de062f764831dd112147ab0de24586d2e0c.nq.gz
    ├── 5c371175c38cecdd5085e62120bcae3e559feb80.nq.gz
    ├── 5e8fc42b3c30d7252810194d6405036edd2fff28.nq.gz
    ├── 5eedd78f12adfb6b3bd9f39475ad8de0c03f0b84.nq.gz
    ├── 6105a1496b1e75a5adaeb34f0e44213aeb4345ea.nq.gz
    ├── 61b7958681fe4fc0f9aa9f21d8d5e534d8296907.nq.gz
    ├── 630ae176418833554dd96bc01bac6de3d25a32fe.nq.gz
    ├── 635528f4afe43f294956e1571451403651dfe0e6.nq.gz
    ├── 63d7e84aeda4b2db9247113c0b2d7fe687c55a03.nq.gz
    ├── 653988a7274794d1f26567d4b9d97fd8b256cd16.nq.gz
    ├── 65410499ca0b0f3c4e59a05e5ad867b8228e0942.nq.gz
    ├── 657e074ae51e27df1109cc32bf40dd7ba6d45a02.nq.gz
    ├── 683f926d6c580d55e41738cafc4b32ccb4ee123f.nq.gz
    ├── 68415f3776bfbc0d8abdbc3ba531f6a02f78c718.nq.gz
    ├── 6963b9185cc9f614665288709a6fbe36c2ded9a5.nq.gz
    ├── 6a255648ccd3d4a4772f23010ae49ebec40e74da.nq.gz
    ├── 6ab529c33b11087a5b8936456f127009aef44e2f.nq.gz
    ├── 6b8c832903c6c3bb65986860a9cd1e40a4e9be31.nq.gz
    ├── 6d0193c292023bd258d9d1d04a5512e89731d2ff.nq.gz
    ├── 6d7ff5984d9b580042ead25887ea16975bc5c4cf.nq.gz
    ├── 6d9106e2de1a04f8611f4de5827cdbd8d3315919.nq.gz
    ├── 719f7a8eb55f8053747de5f21ccd7c767c4588fe.nq.gz
    ├── 74aec6d0a9ff4f3e95670af9ef63f9cfa7789edc.nq.gz
    ├── 759033dc2661e1bb9b9697945bc0b9c7eec22998.nq.gz
    ├── 75c8a93d3828922939b59410d5d26042f3644784.nq.gz
    ├── 75dd3a34b02dd528b29d276458e59859f3e1adf2.nq.gz
    ├── 7882b26b1adc3b601df3a1b61336ea2c5c0209e1.nq.gz
    ├── 7c1c8739a8a8690ee166a1cd7765dbe88a0a037d.nq.gz
    ├── 7c468c581e5f6f3a29e58c999b9773916aa98cc3.nq.gz
    ├── 7ee73bd3b309d691e48cf851ae5ac0f3cb4f513d.nq.gz
    ├── 7f8f011eb73d6043d2e6db9d2c101195ae2801f2.nq.gz
    ├── 80a59c7ff95d1b685be0c5354e77d4ef5ededd4a.nq.gz
    ├── 815e379b00b1a896b2f566fe05ec9c7d9f79c354.nq.gz
    ├── 82ea4e8d85218900b8b94bd02c60ad888cdb019a.nq.gz
    ├── 85dd23457293f562d59d4b032988be50df55450d.nq.gz
    ├── 861e530eac960dbbcc712a6fd9747615dedab544.nq.gz
    ├── 86fdb7b8a34096394ba2d4cbfa26b5c0d42ecbcc.nq.gz
    ├── 877008f1241746b4b5a9ade18d7a5f3715831c49.nq.gz
    ├── 87cc2941c69f4dc00730893de4cf9de83d29c6ce.nq.gz
    ├── 8938f91d26ff626a199e7ac81e643dff4d8f9c5e.nq.gz
    ├── 8987cdba8d355108f83dcd2f835508ea4fa12961.nq.gz
    ├── 8a1cd65b30b7bbba4f6241ea55e68759c3f56fc4.nq.gz
    ├── 8bad02d1dde48a4c0d695f182b3b6a70a6b124f1.nq.gz
    ├── 8e4c8c55962f990a1ab58a8781f75bd5e943bf49.nq.gz
    ├── 8e92c9aa9b72cf923efb079fe58a9d0e1ff9921f.nq.gz
    ├── 8f04947e07723779691cea4f69ab0cca86dfde40.nq.gz
    ├── 8f0f43efa5330909bb45f6d98d1244dae50c0613.nq.gz
    ├── 8fe7531f4eb8e9fc45f0e1346bb4a4e001d25eb6.nq.gz
    ├── 905204e2cde08a6bba35a293adcefe512e975215.nq.gz
    ├── 9122d5922bd5b78beba0f8f105349c1e671ab9f7.nq.gz
    ├── 9125f0c07d94be6fc05b9c41b2ae72c0dcb85a2f.nq.gz
    ├── 917d9bf25deb90bc3cd843717dc94359fcc02eb6.nq.gz
    ├── 91c2ee1efc44b1d193b1f335a9e2aa3087ccdd9d.nq.gz
    ├── 93580845ac67a53313b1b1af820a34463d347119.nq.gz
    ├── 9552bac011eece65edd07993538156e0fc62498a.nq.gz
    ├── 95b0439642a521bf30d867516ab711bba9729767.nq.gz
    ├── 95badc6075413b51ea18781828ae9012d78abce4.nq.gz
    ├── 97f49b93ca4586798c51d665ac069781b1ebb2a0.nq.gz
    ├── 98ca45d5f2cf3b321ac0cb159eb3224bfe8a281b.nq.gz
    ├── 9a2b6ce552ad2a8539e43c81f9c61aad4dadc1ec.nq.gz
    ├── 9d1c96829b9663c888d29f84ad652c7f20ec6703.nq.gz
    ├── 9d7b853e66bc6d8b8e7066a805767a5be88fa191.nq.gz
    ├── a49dffa55bc7521ae37e5d8e731904b80a93fddb.nq.gz
    ├── a50b9bdf19c6cad782b1cb94de2794b36e5f959e.nq.gz
    ├── a60de83f6f9eefa66b4f0486d12700c08144f4a0.nq.gz
    ├── a7489641832712f6aed762809bc57cd093810dfa.nq.gz
    ├── a841282c3297f9ef0b1c46d90049499b5e7f70c2.nq.gz
    ├── aa09751584effc172c255a2b6307cfd8439c53f1.nq.gz
    ├── ac0e400b21c2adb899b1e7a385bd31c36a0dee4b.nq.gz
    ├── ac23b54b0a3fd233e1e856523ebf5ed5172df62a.nq.gz
    ├── ade427164d3423c26f880094beee3dab84510225.nq.gz
    ├── ae15a49106386536c77be4df92cef4e836e8e7c2.nq.gz
    ├── afeffce12559ac7ad7a68e0ccb1ff4529c9a3ceb.nq.gz
    ├── b042a407349d76c5ae0b98e82ac5b5bd62afa6ab.nq.gz
    ├── b06ebf38cebde4d3a84f51aef8920dd11d407aa2.nq.gz
    ├── b1266163e3cc86d776d415183a881dc70159a8ba.nq.gz
    ├── b2698ddad4de9cbb4c7fbb97f0e3da454e645b0c.nq.gz
    ├── b36690ef13b592673a3894fbd6672754c0fcc19f.nq.gz
    ├── b5c209762beebdc43174af1fb0f91bb15b36c591.nq.gz
    ├── b73c92e3570703d89bf915c320a59871b4a216ce.nq.gz
    ├── b89663232f3447682368eed3d778d20828f7f76f.nq.gz
    ├── b905be94b57072484d377144bf82508edeef2983.nq.gz
    ├── b9ab7c9db1ec00edc64798e546e0ce4b44a6b09c.nq.gz
    ├── ba3e2b1a0d955dea5d38a7734c736aff2e1a1ce5.nq.gz
    ├── bb3de967656dcf75b24e0cb47cab1fa295984c9c.nq.gz
    ├── c02615d478c1d3dc6d0d5868e81d01643a6a3827.nq.gz
    ├── c06b20cf637f853f7c0a3cf37991b39b5263a0e9.nq.gz
    ├── c1f0b228fd5a6389f2f03471cdc7f7150cc98694.nq.gz
    ├── c33bc7d226467052624bb0b87359d5cd885ffc40.nq.gz
    ├── c3e5de9a025211998f6d3a0e9efa2d7fed72cd56.nq.gz
    ├── c41bd55d1fe621baf4d66d69155144ddc6d7f2e5.nq.gz
    ├── c76886d3769e5c50207d6cb965e74412cb623e79.nq.gz
    ├── c91699de0ca44add98deccdf8680bad8319890b9.nq.gz
    ├── c9a8ede7eec983ff9bee35cd533332012917fc50.nq.gz
    ├── cb7346fcf07ddfbf9b09abdca6549c25c70026d4.nq.gz
    ├── cc5ecc5b228e2a18ede0dd436e7ecfde5e4fa4d9.nq.gz
    ├── cca3bf8fea3f90403724e4c3e7f879a036f54815.nq.gz
    ├── cf1d84d9a4da5c0875d7c075d41775d276dadd40.nq.gz
    ├── cfc2f49926619fe2a23b6602674a2d34f9f9451d.nq.gz
    ├── d2ca8cb9cbecf04b5aea4dd5181379255d98110a.nq.gz
    ├── d59f536544cb88c54b54e76aa30b0c4cf9a4324d.nq.gz
    ├── d5cf5be15597d6aeb42848a940ce2d891d390485.nq.gz
    ├── d648355818a5475c8072adcd5466b7723372e23e.nq.gz
    ├── d6a68e24f4b5c82b23cd33c235885f3a27a9a014.nq.gz
    ├── d8aa6b984fa2c4c4891f114100d205ad99801b34.nq.gz
    ├── d901e1990e1b26fa39fcf6284551f2da27cfeea1.nq.gz
    ├── d902f99a4d423d29b368addb947ee77ee911f1c4.nq.gz
    ├── d9e113ec685b92b018297dd2f200341d1fba01f9.nq.gz
    ├── dbe963f2173d3275727633cb367a8b7a158cd2f8.nq.gz
    ├── dc2713624e03cde85be0e300b39e6d6b0502927f.nq.gz
    ├── dc976e5b444caf352209004a91963a8773c89e1c.nq.gz
    ├── dd4d5d44f6b7f74b745f945b83abb186c44b03c0.nq.gz
    ├── dec63c2592b10a6064a4b4a76c9f642545c81823.nq.gz
    ├── dfd43e4cc76a1666c76f483daa55501164e6f7c5.nq.gz
    ├── e06689711584b8374f4c979de50bd21fa19a2dd2.nq.gz
    ├── e1aff1bdcd700cb8b44fa9667a3a95bc2d103834.nq.gz
    ├── e246d7e3871b0bc9c68765265b5761184d7b352f.nq.gz
    ├── e2a4600ca38085f069de2854e54a85f31c3e4b50.nq.gz
    ├── e4cf9aa8e364cabd9335b0c65f54d0bb5d114826.nq.gz
    ├── e60214e4a7f679268de5de41941125754554a7e9.nq.gz
    ├── e623b0c8a0d042ce4a971e719feb4712352d8759.nq.gz
    ├── e6634a5c0c480c335cfc0e1b52bfc99d63d8b22e.nq.gz
    ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
    ├── e742727d150b549f29e85957bc1402ce7494218c.nq.gz
    ├── e75c29acd59aa18187c676234307c06fdfbcade3.nq.gz
    ├── e7616425d991aeece7caead3d6868ce53e1024ff.nq.gz
    ├── e9306f87cbdc342f261c26afd997755d7ac685a2.nq.gz
    └── ea132e2523fb81f585fd76c80f0fdc7a1b1705b0.nq.gz

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

[scrapinghub/splash](https://github.com/scrapinghub/splash)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
