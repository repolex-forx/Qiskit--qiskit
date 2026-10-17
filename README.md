# Repolex Knowledge Graph of Qiskit/qiskit

RDF knowledge graph data for [Qiskit/qiskit](https://github.com/Qiskit/qiskit), parsed by [repolex](https://repolex.ai).

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
rlex download Qiskit/qiskit
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 829b3842dba943576e527929c54947dac33e66a4
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 829b3842dba943576e527929c54947dac33e66a4
│           └── chunk-001.nq.gz
└── blob
    ├── 003b73208371952b1f798b3f729ec9623dabb9bb.nq.gz
    ├── 009a97720e301d2ec3aada6faa45dacbfc311da8.nq.gz
    ├── 012e2970f5f9fd70d9ee8ac9b661affbc56a1a0e.nq.gz
    ├── 033bab64a0e7d5c433735b8f638ef16dbdf44fdc.nq.gz
    ├── 034a7c3c587d28a3bbb975f177f7a452f0004ffb.nq.gz
    ├── 056f66ef02e4bcf7678fd457de79acce3939903f.nq.gz
    ├── 05ac759569f74a2532efb224d61462d755d148ac.nq.gz
    ├── 06f2f2e102d8ed01aa46bad8cc20ec568c53fffd.nq.gz
    ├── 072105b1a1c50f192354710e6e58be775cf291c9.nq.gz
    ├── 07570179f8ac9123a3d39b6d11be4e92fdc650d1.nq.gz
    ├── 090654e16b9d97b821e5818cbff0aab55349e091.nq.gz
    ├── 0a53e747f10d95701e4092f3f4e5c02f772ffeb8.nq.gz
    ├── 0a7022968e74fe202d157d92b2e65afea743cbc5.nq.gz
    ├── 0b429d877588b4ef8cee262d5444b3c3b81877fc.nq.gz
    ├── 0bc05b296f2b803e3bf95dd1195d59757e3638f4.nq.gz
    ├── 0bed0e095de859b8fd72439a798b0e2cf0b1dfdd.nq.gz
    ├── 0c3d86659f992d108f801d9ad199703557c86c5c.nq.gz
    ├── 0ca64d36672d03ea094b842fa6917ff7093993cc.nq.gz
    ├── 0deacf340a044d04c94a90779e804c0e43a89218.nq.gz
    ├── 0f42c02a1694289658ddef47030362eec809b1b4.nq.gz
    ├── 0f5a741f07dcc5c3eab0eedce43ae27d2c32cc36.nq.gz
    ├── 0fbf24b4a6cd7a76c4c995c50d26079e59a3ba66.nq.gz
    ├── 10d6e84caaf63d062fb833e43674cbfb0ce06083.nq.gz
    ├── 1137c2271ac9e6afb45b228407d0d196cce3c77d.nq.gz
    ├── 115cf54e80aa489de49e8a1061c45f495846d7a8.nq.gz
    ├── 117a4c31829f940de23ed0ad5fadc5627a0404e0.nq.gz
    ├── 11d3ddfe74d2744a3b7be4ff7accf982a1b21b1f.nq.gz
    ├── 11d94b413cd7f1e5fe767e2e5430a85989b128e0.nq.gz
    ├── 13b3953ecd9e63acc26b51b85e18b0c15b4bb877.nq.gz
    ├── 13bc62db1ba1b96cefd8f1b24af8402f0717e819.nq.gz
    ├── 146c1e5085875ea59dde7b1d312c6a2cd9d64f97.nq.gz
    ├── 14a4ded91365aa2c5cd261c69bb60fbd09f40eb8.nq.gz
    ├── 14b2ff8a0a34c7e7dcb68be5db28f1f354bf63ef.nq.gz
    ├── 14bec27f1098b6c1430e938050b555e1f32edc6c.nq.gz
    ├── 15c1de6d4e7bf3233b20feddb96c6713edac4d0d.nq.gz
    ├── 15c4c1eecf4697e3bb7284f413631e3d66d0a99a.nq.gz
    ├── 15d7afb93a5c8ea9e91bead71dbc4423fc7d8f33.nq.gz
    ├── 15f20fd6ee19d10e2fb9d750d10f3d774cda33b3.nq.gz
    ├── 164553189e67baa4b0f3546ffbd6422b62c7e8f2.nq.gz
    ├── 1795c83a36f642d8657349093e3ec08c922b04de.nq.gz
    ├── 17bf77f51c1bb5409e3fc59e68e918879c9acaad.nq.gz
    ├── 18f426c4d8ea8c95ef8f0da947d462fd1dd0e6de.nq.gz
    ├── 1b7caf6da4dc0bcb0ead2bef3c62ea13a42e26ef.nq.gz
    ├── 1c380b91b3d0fa8bb24f0fbc42f0086676550795.nq.gz
    ├── 1c71bd30e38cdd76b7a195290552d8f226308315.nq.gz
    ├── 1d2bc2c36105d2e3d6b734ef040accc07dc4a633.nq.gz
    ├── 1df41261376369cef995e0e91e131745e88f2c42.nq.gz
    ├── 1e9c1a1cebe7498bdd2f511457ff382ae72c9f57.nq.gz
    ├── 1ec1774e680a9e3253720480c15b4bddbf81be87.nq.gz
    ├── 2017dab991dcaad411ed10c85f5c5f559ac307fb.nq.gz
    ├── 2072784f3bfa352b26b8a88d8b1c104bbafb87f1.nq.gz
    ├── 2130ef3b10130731102e5898fcc51337837f138d.nq.gz
    ├── 218a24a07fbc9415a7286a87491c6a50f1e4de0a.nq.gz
    ├── 21e2b472b213db2bb9a7bffe8fd488ef7f079c89.nq.gz
    ├── 21e61d0579e96a5016f59a52e573de0530cab843.nq.gz
    ├── 22491f2a1ae38ea9ef7167df1cad4890105d67ef.nq.gz
    ├── 224abaa84f68ca1f9c92afde75a4c65fc25dfe44.nq.gz
    ├── 23eadb7ff39140db8028724f22bb7902f30ef077.nq.gz
    ├── 24797bdf943be160c0ce9f230aed761c0bedcae5.nq.gz
    ├── 24b00a262e0fbf8b4e8e4f3bd6c14c6c093f7d02.nq.gz
    ├── 24b6ed106829ba9bbd39eec46234ba0bc6a0bb66.nq.gz
    ├── 259d8eec83092fdd4af02ba843906a754dfedcc5.nq.gz
    ├── 25e921e3b3961f8359a7b7b70fe50ee25194aa25.nq.gz
    ├── 2741d76df589cf9ea7a6d603ef7243832fc2ca83.nq.gz
    ├── 27d451bc703d3597650f902d07b244184bff2dc6.nq.gz
    ├── 27dbb0d1c33ba0a1bfc091f19bb19bd762ec44c9.nq.gz
    ├── 28732a17a6d338abbef0e5f0c2aa3e5876dc4ed0.nq.gz
    ├── 28e0d85a3d776988d87d268d4723879e6a8f798b.nq.gz
    ├── 291845728ae251fdc33d4397520ed3f4f7d2da61.nq.gz
    ├── 292fb5eaef7688e0d905d22f19bf097aff7507bd.nq.gz
    ├── 2b1c7a7a7350f55785e7f4edf679dc95a9bee627.nq.gz
    ├── 2b47cfb26df50fea46dd5a41d1cfa47151eb6abf.nq.gz
    ├── 2b68b9dda67cc2d358f751d97cf7234a9e8776d9.nq.gz
    ├── 2c119c17a7c34d5c3f07f95b2c0f239e531fb701.nq.gz
    ├── 2c5f2145cf8b57412b2620d3b7bfc43831b0d9be.nq.gz
    ├── 2d6461da5ee6b525d6e21e7de1c115bbe5ef0136.nq.gz
    ├── 2d68284ec92af64ec29bf306d2f080ca869f9661.nq.gz
    ├── 2d8ed90772e68a9fc43fe68553d2e01f11e91398.nq.gz
    ├── 2da15c9b7eb30b1f82777a5180bd2dfa45f482cd.nq.gz
    ├── 2ddd5fbb2894175bd1781edbc67ced90124be598.nq.gz
    ├── 2de2c784e7ba0abfbd16808a61e93ad956d87b04.nq.gz
    ├── 2efeefc94034bf9dcdbbd027ac680252a4c65f46.nq.gz
    ├── 2f6e8278050c44372c3d3b6c5dd3e470f832ec84.nq.gz
    ├── 2fd63d6814572ecc4b5f37b36cbddd9dae7a2fd5.nq.gz
    ├── 30b7baca783942fe5dd9a31133dc123237cab5c2.nq.gz
    ├── 31037351e5ff2d3d176f0aeebe25befed35a1910.nq.gz
    ├── 310fb62ed02d0f8bda1328c93b66a3bfdbb6a153.nq.gz
    ├── 31655974ffdf9b3989206f9954d95c9cdef8558d.nq.gz
    ├── 32c2cadc34efcbef99650825e478d758453dd6a4.nq.gz
    ├── 3311ce610d1d35774b2ab2c458f595008642ab57.nq.gz
    ├── 33aeedf8d89244b0bbaac68d3a6219e5873d3254.nq.gz
    ├── 33ce17bafa8dd4a83012e13032fe1e6d63543cab.nq.gz
    ├── 33e8fdf996777abc68babb2381581a8babf19c7b.nq.gz
    ├── 34b7f73a59b02947561199561595e3ef245ad13b.nq.gz
    ├── 34ce84284fe62447c7a40c9390d95b8d2b0cc19d.nq.gz
    ├── 350bdecec637eee576cc32cd9d07be16e49b6d21.nq.gz
    ├── 3557728c07b913d7b490fde4a523e76417cf1d46.nq.gz
    ├── 357345adfa266652278b367f05f2a39e5c186b01.nq.gz
    ├── 36025e9f50fce6ff569043b1e1252821718f902a.nq.gz
    ├── 360d1f057192f32ad8ec9b0beafb2b1cf0ba7e0a.nq.gz
    ├── 3687b20c3e9492211c21dd8e8c90ab68be8ba65e.nq.gz
    ├── 36cb1e47775ca5b708e53d24d6e936c67f907d56.nq.gz
    ├── 37cdb10f83cecbc4e2addee7f7ac123b128307eb.nq.gz
    ├── 384e6bda696312918a20c3e50aac015222e14af0.nq.gz
    ├── 3855a87cdc6764fde292f7b21728cbaf610343c7.nq.gz
    ├── 386904d8f8b9ef913cc35580d56ddf97850107ae.nq.gz
    ├── 386e19e161849a57be89febe80688cb8abd34fce.nq.gz
    ├── 392066bc6318e423855619fdf55384bd97a52f6f.nq.gz
    ├── 3958be4bafe8737d6174a627f4b5fb5f6a002447.nq.gz
    ├── 396511fa1ad5816846b288a681b47fdc3995f847.nq.gz
    ├── 3a0c2ec9e720517b0e1606b0294a933391f0f2e8.nq.gz
    ├── 3b5f08e882d432ac44e6f84dff010db7bc292f2c.nq.gz
    ├── 3b8581c3b5a1bb890e821bf7d335a107834be224.nq.gz
    ├── 3c00c6d06cea8f6bb5b3c0df3eea2a8328fa878c.nq.gz
    ├── 3cd59ff5e4272112290004eb9a0a354643112544.nq.gz
    ├── 3daa5fb7fcd4a7bf0db7a3062ebc0cbb3c6f11b1.nq.gz
    ├── 3de16dc2075575cda26fc02832f03ea8622c2258.nq.gz
    ├── 3e04728590ad83a5cf686a057f40664ef037bc33.nq.gz
    ├── 3e2671712ddac0e4ed9fb6a6d0b5174a8294094d.nq.gz
    ├── 3f9bbac59a652264c9618cd283c4726f9ff5addd.nq.gz
    ├── 3fa19516733647e2648abd5851ecea186b949881.nq.gz
    ├── 3fbe3b3c6ae04b9f1da89822718957ae0a339a86.nq.gz
    ├── 3feaea26b7af9dd2c4099630b15f03ce862d979e.nq.gz
    ├── 404fa29345287e4b11442b4fcfb16177673e193d.nq.gz
    ├── 406f723f395b24f782c8be27177d0d650ecdc7f9.nq.gz
    ├── 409ffea38c4394bf4996ad7aa5a21ac3c51b6cc7.nq.gz
    ├── 40facf79ff5ed689d4d61826c142501e6e3f95fb.nq.gz
    ├── 441ee909f1d83d57e83cedf411506a7a90cc2bb3.nq.gz
    ├── 442c202b75085eb39b3d8d91dc89afcbe37184e1.nq.gz
    ├── 4512f97f4fc382b17394e837f93731d8198c29af.nq.gz
    ├── 453dc79f5d7f8fb400b40397722fb5f7160159a0.nq.gz
    ├── 454b0c6955406248f299f85f575fd89fcd7635ce.nq.gz
    ├── 4607560d96a040c27903e4a14e427c8e5dca4af0.nq.gz
    ├── 4615ecee0f8416d1fec1a8958e510b38784b5b85.nq.gz
    ├── 469f47e63717586110fe263643cfd7bb4df673ec.nq.gz
    ├── 46c223aa67c784e0acda75dc34262d5d28bbd563.nq.gz
    ├── 46feebef4cacf27cb49fc4c9a97fc7cb583d4424.nq.gz
    ├── 47bef1112396b02ae65d7cd491dd3e4da863379f.nq.gz
    ├── 48656d0bd46ce8680226492993d7b2f8d57c14e9.nq.gz
    ├── 48fa04f04d8d21a4ff143470a5b9fc43b95df58d.nq.gz
    ├── 497baa92193981c868ea8691e2a8e4ff38f40146.nq.gz
    ├── 498aefb826485e950a1e457874f0be407d44f998.nq.gz
    ├── 4a46c41e559b20905b82b6a68df989b3241f76f8.nq.gz
    ├── 4b4609ca8dcefdc59724dba2e1418e038ee1787d.nq.gz
    ├── 4b66a76cdfb58047c62cb1420186ae02695cb740.nq.gz
    ├── 4bb9853221cd379c0d549eadee98cbaae7fd07a3.nq.gz
    ├── 4c044d6c62c8fac64ac8107ad365b4ff66571bc7.nq.gz
    ├── 4c898f7d46dd95c20b5bd89b786a985d10792190.nq.gz
    ├── 4cbc1337c02024a18697b41b521c90331ac5329d.nq.gz
    ├── 4eeaa9aa3d7a842c36e00733f6788ac97b4e39d6.nq.gz
    ├── 4f060dd553dc5d6abdb2de692283810bdf5a789d.nq.gz
    ├── 4fde5e38f9f98e8c598f317e54a5ca684e6fc8a5.nq.gz
    ├── 5000a9b03697c9b9f8d734ff808223fb3b28f44b.nq.gz
    ├── 504db1ad1741aab14391e40e5607a68375fccc3f.nq.gz
    ├── 50abfbf0b63b8f8ee309d9075fa96f25d264a990.nq.gz
    ├── 50b602cd48152f8e2b52b0038c156d92a09ca4d2.nq.gz
    ├── 5289182114e3a76378196bac9ca93640bccbb23f.nq.gz
    ├── 5291cccb850cb2f1f4b357cfd0e6896b04d9e79a.nq.gz
    ├── 52ed0851076818657f7477349e9410ccd839ce77.nq.gz
    ├── 545032c17a17815afd45e38e2b1f1414f338b7d0.nq.gz
    ├── 5452dd7eb72fe35d008648be596fa13f7811d684.nq.gz
    ├── 545e1351bf9ff7e6a68f45e0cbfe3c274bd82874.nq.gz
    ├── 54971d9683df90f626167a5ec53a209218a92e8d.nq.gz
    ├── 556fd133724ed2554b429f4079906408dd73b2a2.nq.gz
    ├── 5574dbcab3682c10f8a5c42b326bbefabf710f30.nq.gz
    ├── 5733e1c85287e24c41b0018cb46a49b9f5c8cdc5.nq.gz
    ├── 578ab3b7866251798464fbd2d404bca80605838a.nq.gz
    ├── 580676bb756492c832864d4ceac98c2119d9fbcd.nq.gz
    ├── 5819639f7d96cbab5ae6f0d353cc21ebc61034bb.nq.gz
    ├── 586f503813ddf79e71e2964304d8b2a34d36b37f.nq.gz
    ├── 59ae61445da07eafa049e2da5f9ca9b66f3775f5.nq.gz
    ├── 59b543f7ab4cacc25258be5df15d6c83e45ee08c.nq.gz
    ├── 59fdfb9ad9a90716ad0141e55bfdb39804dafea2.nq.gz
    ├── 5ae9579ee69f68ab2591308a9e1d0517e469e16b.nq.gz
    ├── 5afa10c2b1433b9d6c3e4df6411c6f50aeff3cb8.nq.gz
    ├── 5b261302d4c41f3d90edae5da2467b093efee0fd.nq.gz
    ├── 5bd7ad305e4ee18602f2151c61a97636667110de.nq.gz
    ├── 5c137e39447cbd4188683a1b154e7c95e441532e.nq.gz
    ├── 5c1c5d84f318bf1c5a19e17d359e714c7f66574c.nq.gz
    ├── 5d6c9227b18683d4588913aa165f99ddffda0584.nq.gz
    ├── 5eb442a8cd1cb13e62a271e73adcbd8470b158fd.nq.gz
    ├── 5ff79af6a816c2c45a2da2c7236e85eff7670d12.nq.gz
    ├── 6079842980d6b3361331dd10bf9b8275f68d8421.nq.gz
    ├── 608f91537a08bda3bc02474ec44dd17f5c24fdf2.nq.gz
    ├── 60a7bafcf8a3f2df445ca1c7f446dc56a5d9ccb4.nq.gz
    ├── 60b65043a37a5df44272b040b36656c11d49c92a.nq.gz
    ├── 611774e30f458d76331b16de67166485aa8546bc.nq.gz
    ├── 61241809837243b59e34dd4d51cd8aaf4aa70f24.nq.gz
    ├── 615910206d43b6dedf7ade7af48a81ecf5afc82e.nq.gz
    ├── 61bac94899302f181fd02073ef8c89916629692c.nq.gz
    ├── 628ac976ad76abd726153d3eea457fd33ba3f234.nq.gz
    ├── 63a3229561329e4e42625e16d1a243274cd43f63.nq.gz
    ├── 63b71290aeb6fbccf492ce500bf6d6920ac0bf3b.nq.gz
    ├── 64d81b5e01ed052b9997d869a8f9477a83e441ae.nq.gz
    ├── 6558e8703f4ae138d2d13e0acd4ddcc939e560cd.nq.gz
    ├── 65f81686cd33a483b45657c77cfa3ddf45593b64.nq.gz
    ├── 6614f147b8bd562898849018f79e5ae618f607a8.nq.gz
    └── 6673bd3008eac454657915e0107a65d640fc2b03.nq.gz

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

[Qiskit/qiskit](https://github.com/Qiskit/qiskit)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
