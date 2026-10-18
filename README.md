# Repolex Knowledge Graph of pandera-dev/pandera

RDF knowledge graph data for [pandera-dev/pandera](https://github.com/pandera-dev/pandera), parsed by [repolex](https://repolex.ai).

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
rlex download pandera-dev/pandera
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f3a6a1e6b5f5798f4d803b29e0085ec378197817
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f3a6a1e6b5f5798f4d803b29e0085ec378197817
│           └── chunk-001.nq.gz
└── blob
    ├── 013dc43dfa3517682b6dca7593e10363fc6b5f75.nq.gz
    ├── 028955a2f7be4e218d927aa2651701283c061aa4.nq.gz
    ├── 02aeb755ba062337b0ecdb82902c13027e3cbf12.nq.gz
    ├── 02b4e86b6b0c81b28340f4b656900eb636db7a24.nq.gz
    ├── 02ebbc5fea0fff1cde5b24f6fb9bc8e3d25d1232.nq.gz
    ├── 02ef33d121a45c8588cd59e178150613bd2ea310.nq.gz
    ├── 02f7591e1d6d0f8fa1dc0250b83dfa0e97c25e43.nq.gz
    ├── 036643f92165a96090797e76b878c649d573b451.nq.gz
    ├── 045ddc35bdbdaea2bc4ac8aac110f9e73da8c2c8.nq.gz
    ├── 04fbeeb3279e2f190d77f85274e31eaa0c558fae.nq.gz
    ├── 0585196a1ae41fbdf790f8c93b64d2f0eaaf3480.nq.gz
    ├── 062a01929ca262022f19f168f39fe5566063539c.nq.gz
    ├── 06d1384ea9ed608c2caac36ee30eff9adaa766e0.nq.gz
    ├── 06d6d3a51180693f2540a1f25f209f0d53abf1a4.nq.gz
    ├── 070901669aef8af83ffac3f0260b8f0b82d605da.nq.gz
    ├── 0739ad4de8d49bfefc4e3adcbf0b5fccdef3ff2c.nq.gz
    ├── 07c9a85846776b8183b310f1714e5ee26ef0ee1d.nq.gz
    ├── 085f8f88dc872705d39ecc08fee6ff149747b7f3.nq.gz
    ├── 0900db036852847cecb4559ac521d8586ef50e45.nq.gz
    ├── 09875f5bb926d8e946902fa773bccb2737ae23ae.nq.gz
    ├── 09a3a999017f16025718f7cdf15cbf7099481264.nq.gz
    ├── 09b67321cd0fab37e3ccff3ff27f0eba136a0e30.nq.gz
    ├── 0abe9a2ff682a5b78362c175ee186ae5afa433f3.nq.gz
    ├── 0ae3f18be37452dce0b1cbd7ef886bdd8118f817.nq.gz
    ├── 0b914f1a2910e9276891e342d94fd3c01da03c9a.nq.gz
    ├── 0bb311f4dd02b0730ac3f6772f39e0e65f19fc88.nq.gz
    ├── 0c0fe6f930934c5c23d479334734be0b7ed1637e.nq.gz
    ├── 0c4c392c3cfba39c06788317f0b5476fa2d10d2f.nq.gz
    ├── 0d011c62810c381b3f92a9142931f4ee9618d3e6.nq.gz
    ├── 0dcf340000a8441bb095e8aff1ca0808aa212f8b.nq.gz
    ├── 0e7f6cc453a74669d8c57aefab78aaa248eb5ab2.nq.gz
    ├── 0e9ab3669a97f61c6c0907cdadd1c6f78a2d6e42.nq.gz
    ├── 0eebac623729a89b87d60c0b7c1cded24cf9b6d1.nq.gz
    ├── 0f434a8a26d8b81bbbe5ad0b1c61ddaab2176403.nq.gz
    ├── 0f6c60d05490394e0be7586cf7da2f0cd9916a93.nq.gz
    ├── 1001abd3c1709041d979c063537680baf196a342.nq.gz
    ├── 106c6d71d8b9fd98f2dc8d6991e3cd4689a844cb.nq.gz
    ├── 1140005b2dad159e7cbbf2faf876d07d84b1b902.nq.gz
    ├── 12405597b5e6137cab09c43bc5c92350e569e075.nq.gz
    ├── 137a65d3919537e33d7f63da61356459f5d7d843.nq.gz
    ├── 1383ef90839c90e6927926a9a510b0b3c2953209.nq.gz
    ├── 13ad7c9cc914e849d8e0725fcb0468a34080b241.nq.gz
    ├── 141890e66686e4f781a644d6309a8143d0e89e1a.nq.gz
    ├── 1545ebf5235a626242d4ecf9aae44139796b34a8.nq.gz
    ├── 1565e9e62bb8e00a822497a0accf502c6f4deed1.nq.gz
    ├── 15fbbd088c9bf2677861085f7bc446fc31cd7b79.nq.gz
    ├── 172f962c521106178c2e7932aa19fd01e3c32272.nq.gz
    ├── 1777d8f88081670265e458d0822888c70ed51438.nq.gz
    ├── 17957f205c8a95f1118db2a2730013e758f64e86.nq.gz
    ├── 179d6276b12504760155fb252afdb2c9ffcf23a0.nq.gz
    ├── 17b9c79a99e62c9bce4239c453c5a5d6ca550d0e.nq.gz
    ├── 17e240680781dc8feedb5921d619c54851ca349a.nq.gz
    ├── 17e995930f2b7117d91ca27ba71036bf2d9ce6b6.nq.gz
    ├── 1868e68321937f0a50204f99f8af0d04258d3f90.nq.gz
    ├── 18a791faf05ec845e7b25bd0abfcfe2d3e200756.nq.gz
    ├── 19b4e22f0411ed7f05b8743d7aeeb23fee365f57.nq.gz
    ├── 19f881377d6e7dc4920c16c215b1e0c94392c727.nq.gz
    ├── 1a55ac8af20b1ab6b886ea0601fdfdf4aafbc39c.nq.gz
    ├── 1aaeca918e1095184de6c05b4c4e36cadd821208.nq.gz
    ├── 1b1af5dbad4b75d60fc9fb37f3f1fdb79e7ccf62.nq.gz
    ├── 1b5715b6a22a07ba0b482d4bf81976fd07293837.nq.gz
    ├── 1bac2761ca342b4baf90098b76bf870faa06580d.nq.gz
    ├── 1bed746f90680bcc6131e44b91f6129d8ef6f046.nq.gz
    ├── 1c1c50e2fed3532a4f117cfc85fab5632278ca08.nq.gz
    ├── 1c688090db1816b8506419ec8e22bd3e41b60628.nq.gz
    ├── 1d3f17accf17370a8a65f884e0add6e5de83baa0.nq.gz
    ├── 1d817ef664fbbca8140fc51a2ccf5f71d0e0e8e4.nq.gz
    ├── 1dde9ec9ddf01b7377ab55b60f225db8ab4d4116.nq.gz
    ├── 1e45eeade3376e7441d6feae60264d1234ac7466.nq.gz
    ├── 1f3e4f4bac2a7c6cca59e329a60f50158822c584.nq.gz
    ├── 1f7a216bcc85f476295da73f64d2afdc1209db74.nq.gz
    ├── 20598ee0acd76937863639ff496065326aab27b9.nq.gz
    ├── 2098d6678dd6668dc056e40b6bab3f1bf8cc479d.nq.gz
    ├── 211c804c11bfba0b7d8915a0b786fd9fadf371c4.nq.gz
    ├── 21e9e62ff127b732c5b11ce4d966c6aa5fbdda57.nq.gz
    ├── 21fdb7ab055d0840fce9570d39fd01f4115fee29.nq.gz
    ├── 22607e5d40389edeead9707902c48de52c015634.nq.gz
    ├── 2283782a3abf9aad0dc22a6c5cc3a0e8c6adac1a.nq.gz
    ├── 22d0a3e4c95eee541cccb8469b6788e7f7c1b072.nq.gz
    ├── 23a56c7d2588176864063ca11c963248ed7266d1.nq.gz
    ├── 24188adc9bf951f5a3d1919f7fcf8de001e92910.nq.gz
    ├── 241dd5e72ee45350b3a00c68e6f69756a29f1a73.nq.gz
    ├── 247edb0f06f95f98ff9e0cf8f92e31916cdef470.nq.gz
    ├── 25062082f591f32817e18576dd8e35c4548e66b0.nq.gz
    ├── 2506336f436d81e03b2b30dba9258574ed8062c3.nq.gz
    ├── 250f725bc11b8a1dd6e25a8dad604942be2d1b61.nq.gz
    ├── 25541acd00663f3566d05def08d6ce8ba37b2b15.nq.gz
    ├── 287cf52b0ea6cb5a04f1f3e11a3b8b5fe4e95c1e.nq.gz
    ├── 28f62576b37dac8200a7f60af0a18fc2d2b235ca.nq.gz
    ├── 29f08e8513230476cbaebda4238a7b9ded927a2a.nq.gz
    ├── 2a193afe10eb43d96832822bb802113ed2071ebe.nq.gz
    ├── 2ace97056ee15c2fe7fa7941bab572426653fced.nq.gz
    ├── 2baa5197f0644c7b8d0efa00c610575f6086a5d1.nq.gz
    ├── 2c258b6efe20c33cc2b19f970ca12231c5af95ed.nq.gz
    ├── 2d08f3ed77b3d66c242f8e27ef3083dc5e247839.nq.gz
    ├── 2d16f5b1c160d72ef6c66b2bfd3b51389b9ab9a3.nq.gz
    ├── 2d2af64054cfc477cdcc9ded7643c70b9615dc70.nq.gz
    ├── 2d41b0cc7b509ba8985e90436ed4eba125f533b9.nq.gz
    ├── 2db1716008d6e34d2f98018051678fdd36da09d6.nq.gz
    ├── 2e9b6185920ac395ca7342e34439e30b0cffcd51.nq.gz
    ├── 2ee79cd6fd8d8e31315292079fee8a8087651dd7.nq.gz
    ├── 2fa8654c6978ba11c7e6f99592746b486e6529bb.nq.gz
    ├── 30ad94d136d81f037175e8895851f08fde558b65.nq.gz
    ├── 3154be239e6962b27d59d5d14a4b877f2754cdfd.nq.gz
    ├── 31b7d8513927d57b5dd929586b06adf26566d38f.nq.gz
    ├── 32d8d900c6e434603a84984cea7439ea981eeb6e.nq.gz
    ├── 33e79b11749e016a132545a149ebdd2819b2b4ec.nq.gz
    ├── 343744125c7aa516c2b273c343e506912e29c805.nq.gz
    ├── 343b73141654f730a8d9af2401755c525ad49c99.nq.gz
    ├── 34667917c36ffa4c6a951a0932971733d8215272.nq.gz
    ├── 34680922a4ffd3c662ee380a520ef97486630319.nq.gz
    ├── 35732e510e5e67c83d569545d080f7dcddb9c2ff.nq.gz
    ├── 358e74198d8fb456c483b37a30babd8b484cdcbb.nq.gz
    ├── 35b6af64ae1ce2b6cc5b2a1079700839ee422146.nq.gz
    ├── 36ad12fff098fe6ae2eca2a4bdea67b67ea18e7b.nq.gz
    ├── 36fb5f47337a7e9147fdae0b58c05b39da8e8edb.nq.gz
    ├── 3703ad5c51160849279c7c8ef1327c310d6b00c7.nq.gz
    ├── 377dbb6884ff506ba49c635f71afa5e10c23e7dd.nq.gz
    ├── 37c034494a545f3b7d09cd781f6a5af4c16085cf.nq.gz
    ├── 3827f10d49017bdd67e254dd0407ee18cdce0fa3.nq.gz
    ├── 392d33ce38b86ffa453890aa2fc08c726aceb64c.nq.gz
    ├── 394c2d20f20d883ee4c5b77233062591a48a2166.nq.gz
    ├── 3a0beeacf8c6a96a2bd035e573213dd986412c7e.nq.gz
    ├── 3aab39cea7e35a79f750b1e1f0d5d3824562fb6c.nq.gz
    ├── 3b43c698de1d77004cb87d4afb657807e952ba29.nq.gz
    ├── 3c544d972f6af13f671ee1f3b43486cca732d55d.nq.gz
    ├── 3e0d6aa0d022d3f34ab9c65395ea1c7ee13875b3.nq.gz
    ├── 3e56f5475c5b6371cc7a3e5fc74113371c1df039.nq.gz
    ├── 4032663496d5e508e739ea14d40d24fcd2542f15.nq.gz
    ├── 412b9cd386c24da6f3518f0d41c24c01f8bd79f7.nq.gz
    ├── 4141cad26032583b6796873fd2cbdd1203c448ea.nq.gz
    ├── 415f2371171647b4f321520301bbd1aec8f38b60.nq.gz
    ├── 424040abc4d43cc11907fad15d3e212ee03c1334.nq.gz
    ├── 425943f5d4ff0a3456be640daf3fb0880dbedc11.nq.gz
    ├── 42aa06f984928070794a76b10bc95ff241601d8c.nq.gz
    ├── 4376d055004c52de0c0c4cbc904d20b92ae7ccda.nq.gz
    ├── 444136bfe9cf86c4d8bdc9435606322643db2a96.nq.gz
    ├── 45d861adbedfc1e08ccfe4c7468a22e305dd60d9.nq.gz
    ├── 4747432b05508eb845d5d725b79cdcf649dc2e0b.nq.gz
    ├── 482dfd73fb34172869886c240d175e902a6939d6.nq.gz
    ├── 48a46543faf59ae05e3097f59b9bad6c6e75268a.nq.gz
    ├── 48d855f5afaedb7d4eb61978c2f9eed58744bd6d.nq.gz
    ├── 490f567e7b0636a1d6e301a12b6df34a18080dff.nq.gz
    ├── 491ac59a32ce7017b143a8286ffbfd9289b8fb2c.nq.gz
    ├── 494c8050269728b1089e6ae35e392980c1140f11.nq.gz
    ├── 49bcd5000b92f897d9ef11d7e6e024e6d01f7a3d.nq.gz
    ├── 4a1311d2f1ba50bae02d0627b9bb061d383c9077.nq.gz
    ├── 4a3dbe2e98e9d473a39d8c40c3c2386c06ec5df4.nq.gz
    ├── 4afe93f72c5b709ef640d16273c8e079339a0a00.nq.gz
    ├── 4ba71884f021abef9503f15674cd43b245b55e01.nq.gz
    ├── 4c493f4273a5d1a08b4af8cb3c3a2c0366ea1749.nq.gz
    ├── 4c9045f2424ea0b564480374201bc891ebe2c551.nq.gz
    ├── 4d4b7759037d0f13af38c4de5a3180de8c68c412.nq.gz
    ├── 4ebc2ddb765b7f36a2b6c88758c5ddc1bdcd8b18.nq.gz
    ├── 4eee3f5fa1a913b5dfa0da3ab5a2d2291ed45933.nq.gz
    ├── 4f358a9f642a7cd55d638d8f4a5ab78824bf267c.nq.gz
    ├── 4ff4d294a2da2d1684044ef91f6f0000331a039f.nq.gz
    ├── 5087642390051d95046726a5fa54ebf76ff4f7e0.nq.gz
    ├── 51381e6b17c29d5d93229e92054e6344b7f3a75e.nq.gz
    ├── 51c49f164c839ab4a02f32bf690dfaf88d41d6e6.nq.gz
    ├── 51fec8bba2122324e2259129a2cdce56068254b7.nq.gz
    ├── 521b24a98c099df0924e6da5e15a7b5e2424f789.nq.gz
    ├── 52286e958e252d3ca1d2cbcdf8fddf5935f04ce2.nq.gz
    ├── 5404fbdb8289043e2d561cb30065e3331f2e4eae.nq.gz
    ├── 55781aa49fe21fed92223908a72c2809252ca970.nq.gz
    ├── 55e7d9bc762df82284eb30e16b46b1c07cc20776.nq.gz
    ├── 56b433159954fa8d89e9581cc313e7e3af35f1d3.nq.gz
    ├── 56e040caac67092b7ae52249c4d59c56b4d20faa.nq.gz
    ├── 5753333f630d2a964be1b6476dda934d5cb0a579.nq.gz
    ├── 58041a3618a36c422a09ab529bcb4be72be3564b.nq.gz
    ├── 59a8834d235414a62d9db70bd25d7306e5f94f2c.nq.gz
    ├── 59b68e6e424cf0b3a7127ac7df4f5eb0485123b3.nq.gz
    ├── 5a60073c8ca5c650edd9d33484acb24e42ac595a.nq.gz
    ├── 5b529caf964239bcd8e2014c8934f72e88467f16.nq.gz
    ├── 5bd1f126f280ec68f372dc3377b940751291729a.nq.gz
    ├── 5c284581d8ec6e1b2fcd400c5636a6d3f874ebf1.nq.gz
    ├── 5c8b26d45ed82b0b2b1193de7fc11557b63212e0.nq.gz
    ├── 5cfd01855b6228942e80c856dc3d230b3acb1cea.nq.gz
    ├── 5d1fe4bf3d283ccbd8d5c9d5a484744441ab9516.nq.gz
    ├── 5e11be10f172197038ff296475fbbc5594136d88.nq.gz
    ├── 5eda215df2ca63f73ce45abdfad6dfa0d1b5d21e.nq.gz
    ├── 5edefd48f1cc65456926db458e029065bc103285.nq.gz
    ├── 5f08860a68e1a0bb4f03ecfd727dc4261268e3dc.nq.gz
    ├── 5fd4965d11916682d2c5c54e50a78cc8d570dcba.nq.gz
    ├── 606849326a4002007fd42060b51e69a19c18675c.nq.gz
    ├── 612c6d4588aabef796fab50df8fcd73bd90f0065.nq.gz
    ├── 617b5ed7a4500974f9aebd163535b1b405f8c426.nq.gz
    ├── 6247f7e231716482115f34084ac61030743e0715.nq.gz
    ├── 6296c175779b964aa60aa66edadac0806da4ce92.nq.gz
    ├── 638f2d138624c4d952879b76803a5cd2634223d4.nq.gz
    ├── 63bc47336ba011f058348a7ea5d524d7dad14846.nq.gz
    ├── 63c22bd77d786816649627bc6b88238cf2ac0fdf.nq.gz
    ├── 641b4d5ae2f8e36000ff6d2cdce22037de46be0e.nq.gz
    ├── 64a71212ce0040ab39c6070bf50a946351fbcedc.nq.gz
    ├── 660839e3d3367ec5ea3ad061625aa41a85f3ee0f.nq.gz
    ├── 664f81afda46959137ac65ebed964066ec01860d.nq.gz
    ├── 667c3e948e0ec395b5d70cd7d490bb6546f23c3e.nq.gz
    └── 6792d58be929e74c5a396e1605d607a37dc326a2.nq.gz

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

[pandera-dev/pandera](https://github.com/pandera-dev/pandera)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
