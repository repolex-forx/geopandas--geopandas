# Repolex Knowledge Graph of geopandas/geopandas

RDF knowledge graph data for [geopandas/geopandas](https://github.com/geopandas/geopandas), parsed by [repolex](https://repolex.ai).

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
rlex download geopandas/geopandas
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ee889bb6365319dee15b43ad001539ef10b090f0
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ee889bb6365319dee15b43ad001539ef10b090f0
│           └── chunk-001.nq.gz
└── blob
    ├── 00891231583168daad5d013370ee0b9abbe97b80.nq.gz
    ├── 014caef9cb285c5f0512cdf9455a236de71d8d69.nq.gz
    ├── 023cc9736a209fcc81e0a9de5be012bc59b0fcbe.nq.gz
    ├── 02854fc3f7a53136dadeb1add900aa2068a6ceb1.nq.gz
    ├── 028603be2080134aa4817ed691fec3f449ffa609.nq.gz
    ├── 02a2ed43c53fbf9b9039176bbc6098fac48b60d5.nq.gz
    ├── 02ed59c0ae176d95f9fd8f20076b70943ad13af9.nq.gz
    ├── 031021db222eecc873a4c314905853d3b22684d8.nq.gz
    ├── 04facee01185710f132002ae5e961acc8f4f7720.nq.gz
    ├── 0519ea0c64f01f1c7569f4e0636f0f8b0de5cb11.nq.gz
    ├── 057f08b66450548229cb544d8723e93c51cf896b.nq.gz
    ├── 05ba404ccc69a0168253b88b9abe3556d65b35e2.nq.gz
    ├── 0635fbc1a3fbf950821f7d91ca996e645d72fcd6.nq.gz
    ├── 063d1b1e30a28192d54700478db044de5ec86013.nq.gz
    ├── 0780b0bc5e0735bebd5267e30da104424b503319.nq.gz
    ├── 085a976c1d6d6ddbcb92e2947f931371f31d21bc.nq.gz
    ├── 087338bb7befc77530842ad277a456193a436d9a.nq.gz
    ├── 08f9f0d2d0fe6c6d8525f32c00119808fe517e6f.nq.gz
    ├── 09dde905b5b0253f2aeb97afaf20f291cba61bc8.nq.gz
    ├── 0b044f0a236f5fc1cc3793aac8aa4b2b31ce51ef.nq.gz
    ├── 0d2eac32de76225dd57535041a0551f7131fe060.nq.gz
    ├── 0d43ace709def8fb069dfd94872cc3fccf779f29.nq.gz
    ├── 0daa539269cfc77ffde30838f6c4b792ac16a158.nq.gz
    ├── 0dc7526865aabc8caf27cc741fd0a4220aa22951.nq.gz
    ├── 0ddaad1fc7397b5a54c5caa43f5b5542dac8220b.nq.gz
    ├── 0e44af7a5b2c4e005df2e6169949b199c9c20cb2.nq.gz
    ├── 0ed5142bdda8457a2bb2b3de9243d19f971500b7.nq.gz
    ├── 0f0aab3cf31603807dad8bb80a6b21002451c794.nq.gz
    ├── 0fd0ad8bd41a2279d144b52fc0a83cba801e240e.nq.gz
    ├── 0ffcf8191571bd629b381a6a39f30dbc1f8b0611.nq.gz
    ├── 101162abc80b0a5dd6ade070dccdacddb11bfc96.nq.gz
    ├── 102630efadbdaf40bf9e144e200e6d217c9551af.nq.gz
    ├── 1094aab17a331b9dfeab27ddbc828c94d1313c23.nq.gz
    ├── 11ddc96730047525106edce9320bccf50df7775e.nq.gz
    ├── 1317d03cf0379413de5afb22e1d9c84d9c190e05.nq.gz
    ├── 135a8ca85878d4657b4de5fb290ebb48224b8c0c.nq.gz
    ├── 138b7d6960e1b7deec6d64a9f08d1403ee542e56.nq.gz
    ├── 13aac42654c6c4fd7f53d73ce425123eabb8e2ca.nq.gz
    ├── 13ccae19a17541def5bc923b0c50a282261504af.nq.gz
    ├── 16cc3870dcce867a4d79b09bce1d1635ad32771f.nq.gz
    ├── 17771c4b4ed39277f520c03fb181c4130a9ba115.nq.gz
    ├── 17afc4eca62800ad473dfdc71087d9cd3d0adcef.nq.gz
    ├── 18447e7ac392f6c4652ad61fa2ad8a50d9f5631b.nq.gz
    ├── 192c6a0f96a221e4d69287677a9faf305f02ebca.nq.gz
    ├── 194301315cafbd3f463b51d0d80545412f545b1d.nq.gz
    ├── 1a5a3d7b839aa02fe0567ec8aceb37795252c4a1.nq.gz
    ├── 1b88adac32dc9dc0e54fb1b919aafaf278e7c502.nq.gz
    ├── 1c8c93ad6f173def211c16c04b9ee28f3de66a53.nq.gz
    ├── 1cc34345b03428965a7661d218ee1221be26aa04.nq.gz
    ├── 1ce3154190c2e5def2094747970b688638caa6fa.nq.gz
    ├── 1d3b7631c0d2ed5f2a9b1db00381e98eaf14e75f.nq.gz
    ├── 1e6900a7318c8219fecf8e4bbfe43ecaa9e887d7.nq.gz
    ├── 1ea42c0c4bb6a5fbc6befb2bcd3b68b63dbfe895.nq.gz
    ├── 1f5994421bed39e942e9de189affcd3125ed5ef6.nq.gz
    ├── 1fd95d8252ca4cae6f2b1b5cfcf260d7ca4a586d.nq.gz
    ├── 1fe0698a733d5dfd81f5e63227c33490ccd2e752.nq.gz
    ├── 20a97d107d57463e77eb27d7ac28cceee4ff0f89.nq.gz
    ├── 20f86765fe382b71539bd4a32bfafe983743b975.nq.gz
    ├── 21d7e7490b159da2507345b50141ce45b928b08b.nq.gz
    ├── 234ea954273345e44c96002f89d29a679d303b77.nq.gz
    ├── 2399f366bb7ff01d65e88091a564701bb1b9b731.nq.gz
    ├── 25e21faf0cc99fcd739edeb3e164d4c98e46e90f.nq.gz
    ├── 264705df6fba8cd34a5d101feb41f118b5f76a22.nq.gz
    ├── 275512f80d174331444d331846760d792b97b45c.nq.gz
    ├── 276e71427c77e096123830015f64bb5df3a5049e.nq.gz
    ├── 28a84904039c8340bbc3809f5a940bae570aeca6.nq.gz
    ├── 28e94e9a55714a920b0a2e2be52d50102b8aa68f.nq.gz
    ├── 2971424c40836f56d4aaed3fa664a29099a08ae8.nq.gz
    ├── 29ed517efb2494115bed2929d13a43e6d62302ce.nq.gz
    ├── 2b504fb47070c655baa6298c1a874de31b44bed6.nq.gz
    ├── 2bb58225a1020186e7b0eea4e0cd3867bb0223d6.nq.gz
    ├── 2c8d2c5bb00c5bcbca1a88cae12c4e3ab88064f7.nq.gz
    ├── 2c9c83bdafca59814b1fd590f32f78577db10690.nq.gz
    ├── 2dcb765c3f0b45126e623332d51203fd72617e73.nq.gz
    ├── 2ea881bde20235d159d58ba534d4c920c860f016.nq.gz
    ├── 2f8159486064c5520a2554466774d0702762c9bd.nq.gz
    ├── 302a85b21a123cfaa3d5d0ee6df6c9a2dc81173d.nq.gz
    ├── 316e2b1e220e933245058b4965ed4d633a5cea36.nq.gz
    ├── 31d0d5691bd322a736bd6f7b3a77488550308e07.nq.gz
    ├── 32e5afb027c849450efdc407e686827843ff53c4.nq.gz
    ├── 32fc6f9c5e18b51fd496b37362903aaf5c527c14.nq.gz
    ├── 331ad12d08a3ff9135fe89f415ca07d38710a664.nq.gz
    ├── 34aeda2f5233f064b03782ce3d47455ef44855f8.nq.gz
    ├── 359a5b952d49f3592571e2af081510656029298e.nq.gz
    ├── 35cf323baff03fab6521d0e9536d861551845967.nq.gz
    ├── 374737f0d77897b8756040bdb8838d4c71006598.nq.gz
    ├── 38beb8f60e106cfe5bb52d4d5313653325c1a1c7.nq.gz
    ├── 3908d8d77c1bd4633e5f62ce683ab0be6499398e.nq.gz
    ├── 399768a727787eb9813e004974d43030eb8f01f7.nq.gz
    ├── 3aa6930b4bc309631e1f28a4945464761490e969.nq.gz
    ├── 3adf4700cba46f67b619d2c6ab2c0edc212bf44e.nq.gz
    ├── 3b779b6c0076bccfe254a0c0b2ae2d11f92a3972.nq.gz
    ├── 3d79a84c6dd8458aa4c2cfaad422e743e47e4036.nq.gz
    ├── 3e8006dde0fa7bad642c70d33b0f520f46c02731.nq.gz
    ├── 3f7fd4660ab7be390245eec018b62af46fc951fb.nq.gz
    ├── 40072c395b1e114c0c738a4d064f3970db666ae2.nq.gz
    ├── 409b85d7c3da6ffd0b15e9594da31fd7e285b5d9.nq.gz
    ├── 41bc5c32f9d84e92770dfbeb22c59e0f1435149b.nq.gz
    ├── 4254d823147e69f8a410659fd06b484784297033.nq.gz
    ├── 42ae2113d543dade605e979514e1034850cab36f.nq.gz
    ├── 437bb979eaafdcc477f382e1177cb93be1b13b1c.nq.gz
    ├── 43a8d2f9dbc693371bc448bd14e87a509c7d3c27.nq.gz
    ├── 4464e8f4c782709533607bac7f6169d6fd912561.nq.gz
    ├── 450d7be39aeb14a5edfc00e40deb708be3ee141f.nq.gz
    ├── 451dcf9d204717a520a503d0040ccf8ff54f8acc.nq.gz
    ├── 4574bbbfc1c2154ae0c8edd37815ced8125b5bdb.nq.gz
    ├── 46b163a81ac03887d772c4ab572655495be654db.nq.gz
    ├── 470ee2a31695337f45486403a816cbaefaf90834.nq.gz
    ├── 47778cb4e502641799e65e795329f77e49e98d1d.nq.gz
    ├── 48e56fe1eb2d340fbdf7e7736cfa26d0c8fcc369.nq.gz
    ├── 48ea6ecfe585cbca7fd1083298624bd159c7dcc3.nq.gz
    ├── 496de6e045e94cbddc4c69e0f0f109a5d1e8148a.nq.gz
    ├── 4cc86171823d2ff05ecde21c77b553832f69ca14.nq.gz
    ├── 4d08f0ca5f697d1eeec11000e01a74b84b754dfc.nq.gz
    ├── 4d53c4e2609232bdf161cbfe424d58fec5f9a0f1.nq.gz
    ├── 4e6489aa576363b2ebacf69ac49763a5fcc0c8e4.nq.gz
    ├── 4f74157d156d2a03577947fe53e763189cfc5958.nq.gz
    ├── 5060b0834941d6f521741c4f3049f4e9354519c3.nq.gz
    ├── 506563ce5062d5ae9be124592926e6d9daf05566.nq.gz
    ├── 508c38c20058daf066c2afce9ff09617c8e37c3a.nq.gz
    ├── 50aa274f87f6ebf67607724824010fe4b0fe8be4.nq.gz
    ├── 50d1206223cbc09399895ac88c50d7440928d640.nq.gz
    ├── 50ebec9d7d2cc33a5ac8d8be4ddd3f83ee064082.nq.gz
    ├── 514dc949b5a10b942a0e7061ba5303a99fd0ffcb.nq.gz
    ├── 5164e0e8b10456113bbf418b532176264d255a62.nq.gz
    ├── 51d4e79813684174f3259a19a51ffea687f3d3bc.nq.gz
    ├── 51f2fed1cb1be115ccea2513998d1f67a3622f32.nq.gz
    ├── 51f559435e93084334470846ded5c7c2e82957b7.nq.gz
    ├── 52000a2fd624b5d787ec56f67d107fbe7c06d2b5.nq.gz
    ├── 52a6cb062fb430e69fd36a651ecfa1ddcdc622c1.nq.gz
    ├── 538b8f4e64705c94988a8fc10636f8d77d17ad68.nq.gz
    ├── 53e9ccb620319807fc206e08508802f34e486b25.nq.gz
    ├── 5451ada58d4814f596c55fb17d6f4be8a7cde1c3.nq.gz
    ├── 55e068df958d787812f21b3331f92222f1d62cd1.nq.gz
    ├── 56765e8164e122bbe4f03c3a2092a3dbe49873e4.nq.gz
    ├── 567e46c047ed8bb0279ea24945ea0a04cb699bbe.nq.gz
    ├── 56ce993714ba5656a00998965ef1056b6b269aa2.nq.gz
    ├── 57d0a314e94d66e08f9ba0524beec6aeb88f0402.nq.gz
    ├── 57d1862c1ea3c39ea1cd0086e9aa11604688445a.nq.gz
    ├── 589847198af302219f22853c3fa511e02b451d22.nq.gz
    ├── 591d02ac0c202f1a0442e3d340317420fa4f3a99.nq.gz
    ├── 595a05d3ac56df8611d3efc652f79e3abc41cd14.nq.gz
    ├── 597f46a755565ff075bab29257a6783ed832db28.nq.gz
    ├── 59973be72ad89816eb7862f5946ceda50eadb64b.nq.gz
    ├── 5a3440b253e0c28764a3466fa970daeeadfbcb74.nq.gz
    ├── 5a4a1823357c9e6ac050ff3ea2dfa35112af0575.nq.gz
    ├── 5b0a97a36f3d6612fd31cecc82b77892f0875b07.nq.gz
    ├── 5b3480ddb0d6f6e284d2eabba93575c3fa3c75f8.nq.gz
    ├── 5f2874fbfe4ea4568507dd479bdac2e2d8355378.nq.gz
    ├── 5f6e7b0a7c8ca1ed15f05928671cee57b9fafa45.nq.gz
    ├── 5f8ad9a656095ea824740d66d926cb6a2623e81f.nq.gz
    ├── 603aad0de274900a7e2a64eccddb04c077e6a942.nq.gz
    ├── 60561504636ceed937965e63969a48c3cbc02e84.nq.gz
    ├── 608b510d15f90d1ce6318e7dd4305069261124b9.nq.gz
    ├── 61863c37178bd06719ec8ed03ea30cfdbf0543be.nq.gz
    ├── 61a72171c6ad1a4650e66ef8682ebf6bfb663033.nq.gz
    ├── 62901c8f6d2b863feb6a444e11176c7448e1938a.nq.gz
    ├── 633ad1ca66cc3294448a653d7cf0a0023f6e69dd.nq.gz
    ├── 63b8b82a84dd23d5ad9dab8ca91051cdfad095a5.nq.gz
    ├── 64851a0861a6585d63d5971730933a743c09e1ac.nq.gz
    ├── 665c5ba8ad39d4526d349de94068116d9603c7bd.nq.gz
    ├── 668713cabe30ba7d769ec97b20b8c429b78e4101.nq.gz
    ├── 6744ec5d6d57f4e24bd33f58dec66978cca82f01.nq.gz
    ├── 67b5f9eaebe9d39e582fcf8a81367a6a1ad7b616.nq.gz
    ├── 67c307f3a816a7ad678474e247e59df4b344869f.nq.gz
    ├── 6899d14cd34064dd29b6b9dabca4b170d3eca0f7.nq.gz
    ├── 68d1aa67ca4f3d1b29c4205a4b0eedf68eb2f02e.nq.gz
    ├── 699458961edb8b29e1e1da2cefd202ce5cfd1244.nq.gz
    ├── 6baa7e8d0a44d960aaf84dc764e6c253a10ba5d0.nq.gz
    ├── 6cc35196646e2d5a7c4fca925bad0fce378d7a13.nq.gz
    ├── 6e019078f68d3b732e230c5ac1207dd4a6452c1c.nq.gz
    ├── 6f458146903118e59207476bb7d63e7cfa5f8a7a.nq.gz
    ├── 6f606d7cbae5b6c3a5fcc9a1feb2feb2174bdfd6.nq.gz
    ├── 71f642a77bc5e052cd65fa93fd826d0b443a26e3.nq.gz
    ├── 723936afa69b5da2ac17108142539865890d654f.nq.gz
    ├── 72c17ba39e47e9fa8c1aef090cf27f5b40b09541.nq.gz
    ├── 74114d9afde3816bb31ab76887a297358b2696a3.nq.gz
    ├── 748ee652368e8da51f813008d06c69bfd0ed827f.nq.gz
    ├── 758abbb8b3b132134638eafa708cd81c1ed9bc21.nq.gz
    ├── 76805e2e4973155ccb49d28094002287fa12f4f9.nq.gz
    ├── 76f6a348f3b14d3ad6fdf4f39a6685c5dfcb972f.nq.gz
    ├── 7852838fdb45e53e29d0c3e71961c1d07153cd06.nq.gz
    ├── 789335fd3441baf7d36d77ef1ae05afb3955d8b0.nq.gz
    ├── 794634fd0e08974abeb2117714d8c39bd4e8cb94.nq.gz
    ├── 79700ac3b18f831a492b2d47c64a35eb701b9e37.nq.gz
    ├── 797e188dfbc18f67c9c70b8bbce509a68a10dd63.nq.gz
    ├── 7a7e54b424997ceefd7acdb98986b9263c8e8473.nq.gz
    ├── 7d61b0eff2bb067b32752859c2e92b0d03443726.nq.gz
    ├── 7de1e4f09d78defa6b065d0b99e62455651efe6b.nq.gz
    ├── 8041b9f1864a40c6ef1a5ed3f31a370aa743b5d6.nq.gz
    ├── 818dbaa3e48c011b89246c0babfa96dc58e22159.nq.gz
    ├── 827a4aa45e07c55b72fe32fdeacda9a8414410ab.nq.gz
    ├── 82bf7720e9c26ca387011168b53c569fc9fac10b.nq.gz
    ├── 841dc54b411cf6317e6ed35a1db08e616b12c50f.nq.gz
    ├── 8454f250b3a4211286d8ca5372d06094e13aec1d.nq.gz
    ├── 8520831f7b51a63ddd0b581c494af02fd82ad3bd.nq.gz
    ├── 8564ec3896d84703925a25ac03d5104bd0604dac.nq.gz
    └── 85a32ce8ac36850e16eea63b9d0df8ee97516b5f.nq.gz

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

[geopandas/geopandas](https://github.com/geopandas/geopandas)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
