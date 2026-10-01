# Repolex Knowledge Graph of block/pg-sprite

RDF knowledge graph data for [block/pg-sprite](https://github.com/block/pg-sprite), parsed by [repolex](https://repolex.ai).

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
rlex download block/pg-sprite
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3d7e004f03336bd914a19651245ecad867f690f5
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 3d7e004f03336bd914a19651245ecad867f690f5.nq.gz
│   └── repolex
│       └── 3d7e004f03336bd914a19651245ecad867f690f5
│           └── chunk-001.nq.gz
└── blob
    ├── 0021233eab4ece774ab4f789ae6d3c69eb83283c.nq.gz
    ├── 00f01d09f94e7e0de6d697974d95927ed3fdc03e.nq.gz
    ├── 03009d4c5173f296bf309d4bdce18b81c9f03452.nq.gz
    ├── 03f80c8a85c7d0eb6f457af5f4c9066744be2cf4.nq.gz
    ├── 04da9f546bee64ac652c71b59738b1f8008d0b00.nq.gz
    ├── 0760e9161401e78dd2a317efd63a84885b22d951.nq.gz
    ├── 08378077edeff456125dfe75cfb9b278628616d9.nq.gz
    ├── 091b450ab62059f8eb1fead335a0191d99cc769e.nq.gz
    ├── 092ed9f2a676665fdc389bd686311c77ab4a20a6.nq.gz
    ├── 09d95b1239d7d44d3e42666b6c45ce135024880a.nq.gz
    ├── 0ae67f336589431df3e0e63c7097730625b055bf.nq.gz
    ├── 0b2134640783de421f7b447d0d09d676d42d9060.nq.gz
    ├── 0b39edaf0db409113fd2746d2bd1335106a0d410.nq.gz
    ├── 0bfd9837c99fda38d398f76395a8611e3988260c.nq.gz
    ├── 0c003f5236ca2e89b80f2755c2ddfcb1823ce4f9.nq.gz
    ├── 0d16fe929e76929ce8c3bf75d4d5aa2cb9f1036d.nq.gz
    ├── 0d1c4a930b9dff56ce54360fcf36c50eb7e9e5f6.nq.gz
    ├── 0db75cf13660ff92921d00ea1c6c35bff5d197cf.nq.gz
    ├── 0e1d83bcf25b6c157bfa928995a76bcb7a493784.nq.gz
    ├── 0e3a501bb5d954d5a924028a7a83745203543fbe.nq.gz
    ├── 0e6e545a29be0330fc819ea2af353cb4c28a19d8.nq.gz
    ├── 0f049d7ef0262968677b0e3c37a577ba976cbd3a.nq.gz
    ├── 0f8bd063aa5def9f90aaca5fbf0e6c222112c6eb.nq.gz
    ├── 0fff0158f40df0f124b7ff7ab786b5ad5109f738.nq.gz
    ├── 1061038cc1fe109457b8805e9da0b22578cd079d.nq.gz
    ├── 1080295a5dfd1a1a415788800ce25601aedd2011.nq.gz
    ├── 1132b15817acfd222bacd6defe0947c3e3e9cf0f.nq.gz
    ├── 11386cd6a0828759c0e45fd094541fdfc7844987.nq.gz
    ├── 116487e4a7954089b65612516d06db810b154fa0.nq.gz
    ├── 11730cb3b40185d3887ee76dc2fc05a25c66f2f1.nq.gz
    ├── 1194a1c3fc9807b14e52dce3103e72ac56c544fd.nq.gz
    ├── 11ddee2a5813b7129697e3f391fb96a869c42922.nq.gz
    ├── 1280bf7fa3612c7dda6752bef8b52b13e4c1c1fc.nq.gz
    ├── 1340fff8d8bad91962eb7db860c3f420dec06dcd.nq.gz
    ├── 13e8f560f1ebf495c65a7b0b65ad55b54dfd806d.nq.gz
    ├── 1457b3fb7aa2e0a511a789968e8415ef13761a1e.nq.gz
    ├── 155118cfd131249187045d19e178e4a8bafae0ba.nq.gz
    ├── 1605a48e2aa6b1cf1a223d5017042dcb9b283217.nq.gz
    ├── 1613b460f8241204d203169a8159ac53a7bf4f46.nq.gz
    ├── 162b0600fd244accb403a25d5930c34eeb6ea100.nq.gz
    ├── 172482548501006f74e85d086c0b648b900d308d.nq.gz
    ├── 17541bb68019c63aa6bc3d404552fd90ffe3c2a5.nq.gz
    ├── 17903abd1d7de5f9d5c7f1930cc0cf64b2d8c2b3.nq.gz
    ├── 1882b11562c8744305d4310f18b3d89e5f9d9885.nq.gz
    ├── 18861c5aa186f2591d5eb7357342fbd7eeb7e38f.nq.gz
    ├── 18985b370bb718d1de5b93498bb7cb62b3020727.nq.gz
    ├── 18c8a9f0677eecc987831f98af0fcfcc1f6a448e.nq.gz
    ├── 18e44180f869135b2e45c257f9b3f2f036f7a2c7.nq.gz
    ├── 19635de224f2eec50f0faa393eb7b83fd9ac6a81.nq.gz
    ├── 1a3e0f20df131e4d247844c33dee7415aca7e1ad.nq.gz
    ├── 1ab5c7ff388a7b40c0a7916fd6a6ad94f164b8d3.nq.gz
    ├── 1abadfaa1dda7ce0282590e02bdc5c1b91a41c24.nq.gz
    ├── 1abdd7ff8af1b21847f27afe8a94cab8254d28f0.nq.gz
    ├── 1ac5a2b9933bb1902b4cb1c53e05173cd9b9fcee.nq.gz
    ├── 1b61f7bd16b8bf4bd4f3fd70cffd93ee411226ef.nq.gz
    ├── 1ce251a825a5e5f9bc46e4f67178b378181c0414.nq.gz
    ├── 1d36c0fd0da56ce364e7a81486b24ded93a4bf3e.nq.gz
    ├── 1d4f42397ac54d276440cf79cf946bfb34a72620.nq.gz
    ├── 207d4111fe2e8cd944d11d483033547e4870d02c.nq.gz
    ├── 21255e8519499e88062fd9ee53236314fad37cb2.nq.gz
    ├── 2134d5a08ae2ccef4cb34529fabadcc32ae49d36.nq.gz
    ├── 21723d98f9510442311a9c2ad3ae19a3bfe9b345.nq.gz
    ├── 223e2bea13f8a2b5a7de4c153a68b8d0518e9385.nq.gz
    ├── 227c88b87ee7b77736c52fbf8ccd77b8b6d04465.nq.gz
    ├── 22a932108fc497b07ec9ce9c1bd29f0a34aeb1e3.nq.gz
    ├── 22b14923036d7140a3e42e76945c460547ec27e8.nq.gz
    ├── 231231ea89fb3139c932f6937e5998868d1448ac.nq.gz
    ├── 23751caaff50eee82d229089b019ecb519128c5a.nq.gz
    ├── 23784253734ac4ccf4a899231914333a7bfc6848.nq.gz
    ├── 23b1a112707644798d5d2ebfa6aec7bb548ae51f.nq.gz
    ├── 24240441449d0e7c6e9ae41a07a717a6c091b3c5.nq.gz
    ├── 2446125704438b47815790723aa643eebc4bd7da.nq.gz
    ├── 2495fcadbeb177ebb72daa06c57842bd00227eda.nq.gz
    ├── 2543847c49acfb282e043f400679fad8d7bf8232.nq.gz
    ├── 257a78fc9929ad63a40574ea2b8e9a57f23f4a94.nq.gz
    ├── 25d0282d9da973384ca8204bf29437c53ce87306.nq.gz
    ├── 25f5ec5a7e65835daeecb05264d4a5812afb7ff3.nq.gz
    ├── 263282b7e5647b61881235aee55614d16a9bcf5f.nq.gz
    ├── 26657375226c087e11ea203763749cecfc787048.nq.gz
    ├── 26a35bc83a76f2ef0191d4bc5612333c0c5e9f9e.nq.gz
    ├── 26a7bae8efc4123cbd9d908929af532cc34d624a.nq.gz
    ├── 26ffd0670c2d397bfd6982cb55b344b9d3b520c2.nq.gz
    ├── 270e0ea4aa1340b531f54d44bad81aded933d993.nq.gz
    ├── 280d24f35ebfec690f23eb1131a0ef7b7cf1b0c0.nq.gz
    ├── 280d6cf4fb8dd132e66ea4791baaa72ba13b5f26.nq.gz
    ├── 2830250d310479e67aa3c5bdd53140c78b65fbab.nq.gz
    ├── 287cda080b756c5b37edd14e1d70b7b9c3667897.nq.gz
    ├── 28d46e4b211cb1280ba4327ca14a509a5c8efb82.nq.gz
    ├── 2a08f2bbc2eadd5d21881e46a2302483a78ce3ac.nq.gz
    ├── 2a24e7bd139826cf8484f2a52d9a711b6b819027.nq.gz
    ├── 2a7555a01cc54bfc30b5ed7db4217eaf97d0e67f.nq.gz
    ├── 2ac604a5bd6021b2713db990a58c5b55919d7b93.nq.gz
    ├── 2adaa5bd01c0b48c360e7214f78ddf8d938c93ea.nq.gz
    ├── 2bb9466cc086fc94eb9edcf6906a4e688233e733.nq.gz
    ├── 2c618b00d39bed41a6daa0fe352f4ac2b2f7dba7.nq.gz
    ├── 2dad2dfc8f326e4f1e25fe72906a54f3e8d83e90.nq.gz
    ├── 2daff17a17013908fcc08b36d5c8aa8836832183.nq.gz
    ├── 2dd9552a6196b5d8d0b0ed132bc73bf745181708.nq.gz
    ├── 2de0561a865560b4bfad2d695c026f3449996b8c.nq.gz
    ├── 2e24e5dc9f034d947ed781fafcfed8fbdb4aff0c.nq.gz
    ├── 2e661fc3d3e256233e4aa100e65e0d0387eec1a1.nq.gz
    ├── 2e86bb6364c57889f72c79fc1fbabb0f76213313.nq.gz
    ├── 2fb415ef82f889d0780b4340c34eb5badd4cf44e.nq.gz
    ├── 2fcbc71a706ca6e1385f5a8a9057e8afb0148e1b.nq.gz
    ├── 308beef5357037f350b6225dd883dc4bf66344cd.nq.gz
    ├── 30ea225db8c5da20db96887270654f546a86160f.nq.gz
    ├── 312a2cb874e8d42f317c566978c73ddcd78b3c0c.nq.gz
    ├── 314055575185384fd07e4a9822d2afd46b3580dc.nq.gz
    ├── 330f2a794a0d784022df5243f11a7c866ae38523.nq.gz
    ├── 35d9cbca15cd9f40080d4de090a59b4a0b5ace2e.nq.gz
    ├── 35e567a95c55de1b6cd0fb718a3e49c2999e6b8d.nq.gz
    ├── 36084ce48136bc19c99fea2e748181cd2d3f415f.nq.gz
    ├── 36aec1489e10f2f5a7a4ba97a3f3fa6a48288a1c.nq.gz
    ├── 373b1ccaf31d6dba87a8475db4293ef14e63b8bb.nq.gz
    ├── 3787b77f495c5712cf5ab93e6cedd4d9e57d0f0c.nq.gz
    ├── 3890f7662fe7da9fbb5da797aef89786a73a17f7.nq.gz
    ├── 38b3d9be253b709adc46e499832598d2566108b6.nq.gz
    ├── 38c082e8e86b4e89190f521850b60c09909bb61b.nq.gz
    ├── 38da98323bbbf4f44970b5d929389e5f886aaa4d.nq.gz
    ├── 395341631e1e6b6c2604f39607bfb036e2a89a1a.nq.gz
    ├── 39f559f6f03346d792e6ed3948ad5fda52f7c78d.nq.gz
    ├── 3a9046f42a9545c1c9e196e3f859dba5e7b672d3.nq.gz
    ├── 3ae1063553dd37ff44642cfe9ad91cfb4ce37fce.nq.gz
    ├── 3c5e5e1d7248b78c549490c175250f51dc75d27b.nq.gz
    ├── 3d1c907eaf8532934f17472ed1c4893a1953205b.nq.gz
    ├── 3db0645745ad578dae4ae6a78d7107616ba5342e.nq.gz
    ├── 3e31cc9744c0e449e29faa1182153e4b1143121c.nq.gz
    ├── 3e7c8bd833c778f8f41cff7c8844abb9b4d10e8a.nq.gz
    ├── 3e9589737d911dac7d3aa64a2487f5708c64d85c.nq.gz
    ├── 4129e5d205a51e0305cac9a3647c5c3215d47c19.nq.gz
    ├── 414e7a955be8a0e543bce0c4af47738141aeb422.nq.gz
    ├── 42c445a57f027ce6655e605e4d55ae3912222fea.nq.gz
    ├── 42d148ce98a4d882bcef05a367a527e2dab20d33.nq.gz
    ├── 4366b5ac1a088216dbd6392d503ff78cae6647d6.nq.gz
    ├── 44330b1c873608ad4dfbb992325a14c46fba6f2d.nq.gz
    ├── 444e12043687d802ec5a887113ec4249de366d1d.nq.gz
    ├── 445b349fee77a5d3ce4a551b7a0f44fe491fe5a7.nq.gz
    ├── 446c81e58baf9ebfdc075b5e277fd8a26a6a4218.nq.gz
    ├── 44dc5874ed366b399b510f2acc11fab8ccf9ac72.nq.gz
    ├── 455ea40b2e5965efa7b27af68f7e4eeae474c355.nq.gz
    ├── 45850fc948f9c8f72c8fc0747de60907865486be.nq.gz
    ├── 459a1edd6582a68b33ceee710cc4fe547a6e138e.nq.gz
    ├── 46b72b196e1c2b25056abe86d80856896a7d8230.nq.gz
    ├── 46eee2406534e338d29a4dafa63564d13419d04a.nq.gz
    ├── 47497fa54b8eca2c50df1ace2daf6965aaf690ce.nq.gz
    ├── 478c353e73c5d856784c2357206489fb29abd1ba.nq.gz
    ├── 47ae15391925fb5319c1005c76be54486af27fed.nq.gz
    ├── 47b3f4d1f05a5b745a8275ee05ef65ba8599e962.nq.gz
    ├── 47dc3e3d863cfb5727b87d785d09abf9743c0a72.nq.gz
    ├── 4948f40cfb95e47b3aad728d9a6f16559d9cfc74.nq.gz
    ├── 4af3958eedafeccc3669161f3cd8bbe443dfa0f6.nq.gz
    ├── 4afe14e8863a26a17423cc9ebd0ce962eb8b80cb.nq.gz
    ├── 4b2d4a91a1feec49aedd97fe90a33f04cf9a4c9c.nq.gz
    ├── 4ba48ee1863b117caf8fe49bfa9e28ad08b22f49.nq.gz
    ├── 4bc8e7331d6da1c341577f8d3b037ac172167fae.nq.gz
    ├── 4d1f8f9331c61314fca493ba9f3a96f8e58cfe4f.nq.gz
    ├── 4e3fa97a2e1222c39232e3a1ee26bc014e0639ca.nq.gz
    ├── 4ef460589bc925fd66af83bbbecfca0ad299fc47.nq.gz
    ├── 4f508701f23c01f64766afb45deebb043d79d5e7.nq.gz
    ├── 512d4ef9247613c6b62782cf0dc5b6df14a147a5.nq.gz
    ├── 52b8369c67dfbc87ed1e9d16d42e3a306cdc9c0a.nq.gz
    ├── 537fb56d0e5f9e7e7ad2c8bf7b3401b61efbc9e8.nq.gz
    ├── 53f1c992a2d3ead2134352193bcd66af3aadb044.nq.gz
    ├── 54631506e33bb421d686cf3e252e8834d1821f86.nq.gz
    ├── 5592e97025bfbc37bd573bb6e30d3ac336ddbe75.nq.gz
    ├── 55b917de4758e4ee05868151da6e5ef67973272a.nq.gz
    ├── 56c0b37308f507b801208763c784dc869113b5e1.nq.gz
    ├── 56db4bc1c8b13e16e681cf3f2fcb5b13745022c1.nq.gz
    ├── 57b282079604d701f2ad126043f2ad7000af69f9.nq.gz
    ├── 598dcc4b898849ec7d164ec263ca2a6ec66c6507.nq.gz
    ├── 59e75a0d9dd01bf0b9cd6c324763f6371d2fd80c.nq.gz
    ├── 5a30fdeb6c21220ace4b9df67e21243473813ba7.nq.gz
    ├── 5a52d65b872edc0635e90c27e125452701b8d9be.nq.gz
    ├── 5b3a0a2d9b04b5e4b770c14654d36d29f9de0a53.nq.gz
    ├── 5c4c6cb7a44b5ac4a855e0f72a493469fb002501.nq.gz
    ├── 5cfc2bd452f7d2750f021bd855c75430feb99f1b.nq.gz
    ├── 5d0820d05ca7085960dd9f75069c0c9c448ff71e.nq.gz
    ├── 5d08bdeb24b1284ce6484521f7830117dc8cfa82.nq.gz
    ├── 5d2057833ff75c4688abb0012a28087f14ab114a.nq.gz
    ├── 5df2ca95b18f861aa6b887a50d9f25848eba52a0.nq.gz
    ├── 5f1cbff2d4a02323e3928a9db5784da3bceabe5a.nq.gz
    ├── 5fe9c6e7df6e27e67a76a66d20e6b12829e037d8.nq.gz
    ├── 5ff8862b1be102d1172569702aaea1ab1947f659.nq.gz
    ├── 616f4d4db2edac70d94ed4fe02ac664cd0bb4d5f.nq.gz
    ├── 639474d3c37d0abd1d6f5178c380314e7bff15d4.nq.gz
    ├── 639b3ded965096860991c51fa112c53242dcbb1f.nq.gz
    ├── 658f5efbe42f72a8a7dc300e6a83c70286900e48.nq.gz
    ├── 666f27ed84449092e2f115e19f1f0ec1b155c571.nq.gz
    ├── 6679e69baa311a38c5a8bce05c65d68b5273e8de.nq.gz
    ├── 66c42d85e93beee80d6267a0255be6c5eded9011.nq.gz
    ├── 677169cd2c91beff11e0fc7b3bc7ab2b127b2174.nq.gz
    ├── 6807d943274ab062a05ec9bbcf46526c7dd9a6ea.nq.gz
    ├── 6967da9a063b411a5e597443e0dc6154496a9535.nq.gz
    ├── 6a239077acd8dd2bee5f34c26492f4d779f8be5f.nq.gz
    ├── 6b3528fcaaf4bcdcc22182e5e7adaa7253bd80bd.nq.gz
    ├── 6b512296c669d6afe7988e44717b8307fd20dda6.nq.gz
    └── 6d5e18198b95901ce11b3c2590416acac592052a.nq.gz

8 directories, 200 files
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

[block/pg-sprite](https://github.com/block/pg-sprite)

---
*Parsed on 2026-10-01 by [repolex](https://repolex.ai)*
