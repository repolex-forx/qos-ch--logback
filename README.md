# Repolex Knowledge Graph of qos-ch/logback

RDF knowledge graph data for [qos-ch/logback](https://github.com/qos-ch/logback), parsed by [repolex](https://repolex.ai).

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
rlex download qos-ch/logback
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5761779e16b2f2b29ea04f8900970d29cf57dd95
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 5761779e16b2f2b29ea04f8900970d29cf57dd95
│           └── chunk-001.nq.gz
└── blob
    ├── 00493e38c58d3b3c7297086460eb3d9355d34abe.nq.gz
    ├── 00ac1f6d45f116b263065d5dd5fb19d138309c19.nq.gz
    ├── 00de1325093fd2b127e106a78627561497996629.nq.gz
    ├── 018ed46110ef00581783a666cc257291472b321d.nq.gz
    ├── 01ccedf4c7ec3ffbe63c665ab495e8fa8b056126.nq.gz
    ├── 020eb51a98de2ca5a2b3a94ad9b30bc2f97a5eff.nq.gz
    ├── 0264323c14bf0ac3523182cd3b70890ac19f8818.nq.gz
    ├── 0290134fab2530400606a1ce82ddebd680cd04bf.nq.gz
    ├── 030e809686fcb7fedd4ae67e852fe770ebd808af.nq.gz
    ├── 0344f475a1b1437f8dc7ce504706dcb1b2ea1533.nq.gz
    ├── 03621e0ad0600ad601cb61ea3618b89e35a861db.nq.gz
    ├── 03fa98010ffbf407b6d4c58002d13f702ceacec4.nq.gz
    ├── 04e62477b102a39827f7359bc146140a90e7bab7.nq.gz
    ├── 057510b96b5f66b7aec615d6c9042cf59619e6c5.nq.gz
    ├── 066abc14543ebc41268f081fbafc76374c06c09b.nq.gz
    ├── 0751237770dbc64fa9f472cd7f4ff6e2ef16ec89.nq.gz
    ├── 08aeafae97e7d594bd2eec080725e8b9b4fcdbe7.nq.gz
    ├── 09daa7a5195b27804cda7e78113e316cac067727.nq.gz
    ├── 0a9c451beb95d2bf95c07d6665e63a3e9b9d3ea7.nq.gz
    ├── 0b727da3bade4e3bd12a0a0743645b6ed07c7cb4.nq.gz
    ├── 0b80a85ed6d51e057b8895b46e8bc5dab016de3c.nq.gz
    ├── 0b8a2cd150fca0df972e82e9e1bce224761c8a04.nq.gz
    ├── 0c5e7d4b1ef53ed8f813180e9e5b62f9ba09507c.nq.gz
    ├── 0d06f4000043a511b2b3e439f55d75160afd6778.nq.gz
    ├── 0d65b11648eddedc0d9fdd410b7f9197bf1dcbab.nq.gz
    ├── 0daed8ef5c44584a6be1f95f69b88c63137a7b57.nq.gz
    ├── 0e4be0cafa923152d694449212f731e0baf7273f.nq.gz
    ├── 0e63bf39a3e57da930b38f5af69b8425f3a70841.nq.gz
    ├── 0eaee9b7a26c3f31ac8b6100f877f35151e5a9db.nq.gz
    ├── 0f1836d859525cce146fc89e5aded4180f5613b7.nq.gz
    ├── 108d967f38d378ccce4a633bcbb85c0dbbbff26f.nq.gz
    ├── 10faf099531e352ce650e50803a7ccb5cf64fe1e.nq.gz
    ├── 110726b505e9ef340fba082d4ddf7fa3ea2c11b9.nq.gz
    ├── 11ae54efeaa4e739d746d0d26dd097efceeb387c.nq.gz
    ├── 1263c7ee9b735d8e24f44e74345aa01815f4f247.nq.gz
    ├── 13efb5b6c1cc34047020cc1ae4cdfdb56d2d9153.nq.gz
    ├── 155863b62634fd83eacca13ad04acb1fa7c0fac2.nq.gz
    ├── 15b9cc49d226ddb8e0d39681d225c162ca652e66.nq.gz
    ├── 15d5b0be8cce41bf76c68d357b6f6904d2842d48.nq.gz
    ├── 168d9de6652526a46cd6759ae1fb5be75b420f88.nq.gz
    ├── 178d04027c35eaf09fe09f9b7489402acccf4342.nq.gz
    ├── 180879859c62e29499b480dec5e2daac5167a5ec.nq.gz
    ├── 18b314b8214b03c9746edccda3872fe747ef2390.nq.gz
    ├── 1901632a164ad87bc55a49779fb4a1ce1db85481.nq.gz
    ├── 1919d5fb6159631f35a503a4a0de6ebfdd4149da.nq.gz
    ├── 1a80ee1ae38142d659be0544d8b75c4b5963301c.nq.gz
    ├── 1a85bb7de27c3e74e4ee5c553ea6861cffd2ed4c.nq.gz
    ├── 1d88331a517a2c0676af2fa372aa1a6972c42ed1.nq.gz
    ├── 1fb33757f879fd04561b758329e04d3eac9c54f6.nq.gz
    ├── 1fc6ee192d7c625d371f92d496b18f9fed99c83f.nq.gz
    ├── 20ee2eaaf1039d16bd55d9343a256041b6a0b652.nq.gz
    ├── 2185dff424aae80914961a036fa8c0480d87ce55.nq.gz
    ├── 21de1824d52becfcde0a2fc1cfc798b753291f0b.nq.gz
    ├── 22e998428a016d4d6ed376fd65b397129934f62c.nq.gz
    ├── 2397fa1a91afe3b96fc2f388659a14bb830df195.nq.gz
    ├── 239b69f5c5245940f32c72ee65a68c757c8e286a.nq.gz
    ├── 23cb3c3560ff17ee364c0287e9569c183021f09e.nq.gz
    ├── 23d9c53a7d48151d47b191a079127561a784c287.nq.gz
    ├── 244efa99e6288c866e273c05fd4153c2d744620a.nq.gz
    ├── 24706395263aa0f141be226e7d3cbad1c1b99758.nq.gz
    ├── 27b816f183647b49dbe5f8e034e242df3a24374a.nq.gz
    ├── 28687eb0b722ff89601ec9bd623c4864dfa81c4b.nq.gz
    ├── 28a92500e44c564fc67e8da7188719e74d1630ee.nq.gz
    ├── 2927b9ece7fdf8cde3382b8bb17ed5bbbf40c956.nq.gz
    ├── 294b0173fd15a5ef155e56689849543e8cef982d.nq.gz
    ├── 2a25e7951671c57e1f9d026807816b99ddd7e91b.nq.gz
    ├── 2a2803d1c05f1ba054354e36ce42865041f74e40.nq.gz
    ├── 2ac250606da5b44b0740daee18b320bcd469e7b6.nq.gz
    ├── 2b834cbb9f83a81d79eb4a18958748ae56c512e6.nq.gz
    ├── 2d75e44d99a2320a4fbf4061d8a8ee00ac6e6534.nq.gz
    ├── 2dc95ee87cb92ea53840a7931318fcdf54978002.nq.gz
    ├── 2dea291c381264e8757b19f04fa0ce8344b4ce2b.nq.gz
    ├── 2e02a072bc7eafea5f8ca1994639bdf1b77cd42d.nq.gz
    ├── 2e3cdc53992b6ab060ee5542fa0ec8bb175a6fad.nq.gz
    ├── 2eea43a3a363e73df4c7741b9ea71c39acecc5c0.nq.gz
    ├── 309907914975862d4568007b4cb271bdf558c1b3.nq.gz
    ├── 32951556d186147fa965ce31f167b783833fdebc.nq.gz
    ├── 329ab39685124cc92ce0636c92fd1fcf9180d51f.nq.gz
    ├── 32a53481dcd74c5b4c07d519ae2609877b64fe41.nq.gz
    ├── 32e38482b1cb5e56fd1e67b3ab2aa01d689eff7b.nq.gz
    ├── 330bdaac3cebe40aeebbb1d402c102194341c120.nq.gz
    ├── 3322f92df3df9390dfe5e66c22318cf992c075cd.nq.gz
    ├── 333456f8bb199df8e37779bd1468b16c0907ba6c.nq.gz
    ├── 333ba6a52b1816c61c43e21bcc954cfec13768bf.nq.gz
    ├── 338634423773cb8d676785aafbc557d22601581f.nq.gz
    ├── 3449a4c3d5c63f5c8c973a53fcb0bff1a34841a6.nq.gz
    ├── 34f8fc31446f9e823306dbd0c85d8bec01da9b2b.nq.gz
    ├── 355c4b1db08debeef1162c097b552308b2fd7e7b.nq.gz
    ├── 35d6d4cdd604cbdd4cc0c8c12368f1f75f49b188.nq.gz
    ├── 36610192aed2a85c60bb84c8326132624f61ccfa.nq.gz
    ├── 3747341cb5e33e3b0b4911089a83722bc02a5d9e.nq.gz
    ├── 3794e9fd6ef478c92e11ecb86107f30814eba79b.nq.gz
    ├── 38477e03d6e75672e8e93f9bb6f34b1f6229429f.nq.gz
    ├── 389a83b9fe9bf387aacfdc487f33147a13a056ca.nq.gz
    ├── 38c313e61ea60bdcbdf1c4b0b92fc0b2dfe0dbea.nq.gz
    ├── 38cb8448dd5cb3d55ef55eb1ed6a8ded601c9a92.nq.gz
    ├── 396f6d9334e25cd07ce91e2ba3c6255296147cb1.nq.gz
    ├── 3a169228c8c3cf15e2c63dc40c5f93d56761301b.nq.gz
    ├── 3ab86c5b9a69e51309e8a4594d0aff3add24a8cd.nq.gz
    ├── 3c60552f30b31aafca90f7475c117513c6b39d73.nq.gz
    ├── 3cd94f43fc7fe25f0ba9231946478a66b6cfff2d.nq.gz
    ├── 3d0d9b210f94d0bc02fb47b3250c23ac349307b5.nq.gz
    ├── 3dca6170169d533108b313cca86e5232a9d093ac.nq.gz
    ├── 3ed44138acd8ef90268a0f888e1f7ea1948a381d.nq.gz
    ├── 3ed5d9a4d377b43b71fd3f4d32f6a081551ecc95.nq.gz
    ├── 3fecbf5d54942379c16acb1440104e1b6ef28dcc.nq.gz
    ├── 4057e7997da80d153baac03706a895eca0f66d8c.nq.gz
    ├── 40730aa2bdcde083e8c070ca45559fcaca05d7bb.nq.gz
    ├── 40e45139766d0727c0fb548bd5c8250a561cecbc.nq.gz
    ├── 419181bf3dbd7946178a1375b1a0903557665a74.nq.gz
    ├── 420fd2416906bc01cdcfd8862a08d5722fd8825a.nq.gz
    ├── 42bd61cd4cebc172fa6fae8ac3be62ebf4b5fcd2.nq.gz
    ├── 43810286106703c21bda927616fc927f19cb2b2f.nq.gz
    ├── 439d7687ea19ac7e8285cabb22dc794ca5328bc4.nq.gz
    ├── 457166096d6c1bd42a23c8fc379e7499eec8e06d.nq.gz
    ├── 457e9193c65d7f831b10f24a8813e8188e28303a.nq.gz
    ├── 4618542d590141cdc165d1996d28fbd281418e8a.nq.gz
    ├── 46420b331c21140a9ded0c1665e4c7cd7fec2908.nq.gz
    ├── 46fd94a7919598768b8d3288f120a9c2fb37b3e3.nq.gz
    ├── 486464c3de2bb8ae4b6388bd8187b47e35e5f8d1.nq.gz
    ├── 48cb694dce4d637b11ce40136dfe20b28965026b.nq.gz
    ├── 48f538e8b9be4c75b64d55ebe5d7f85274e03bb7.nq.gz
    ├── 490e3ae9023d5c34e2c757289fa2654f2ee0ca3f.nq.gz
    ├── 499c6f9bf8ea01980c98059aced7e2210247ed0f.nq.gz
    ├── 4a08a0b995c49625605ed73909d9e639c8b61724.nq.gz
    ├── 4a5177e9200482b491b8c2c10253ec36f3c2375d.nq.gz
    ├── 4a6a96d09e1b4630bd6789a8411ef6f376eaefa8.nq.gz
    ├── 4aa86177017c9a9d70b1a6f026d00b65463e5b01.nq.gz
    ├── 4ab2c5d6b6645f702169f81d8691cb71fffee8ef.nq.gz
    ├── 4ba1068ad2191ce8d7e59cc192b929c625cb1ce2.nq.gz
    ├── 4bf2c0ccefae8a3dbfd8838b5a079763c31f0f45.nq.gz
    ├── 4d7ac69aa4a91732840061c9d7e27c60ae136347.nq.gz
    ├── 4f3e86801652ed629d67bff1b8555abd74910091.nq.gz
    ├── 4f8214195775f0d1b8bd774557d5e11a88e70632.nq.gz
    ├── 4fd92e23c0be41ea7b641b5de71595483e7061a3.nq.gz
    ├── 4ffe0957da4ce854d7f82ae3ab24759d8725a630.nq.gz
    ├── 5004b57966e06d09b70831719ff493b15de2a970.nq.gz
    ├── 501df6ddd2fd6fd6a2c41908d43a0fd71c9c4f6f.nq.gz
    ├── 51165c1e0cc8f39e72695f3157eb923433cb35f6.nq.gz
    ├── 5195ce9a538eceb4e860635e94735c12bdecb82b.nq.gz
    ├── 52e0295c4e26f2103261a402b2c47a3105f9be5c.nq.gz
    ├── 5383b90a41f0027e3803de2b13f01a868df80a5b.nq.gz
    ├── 54fe063183d87946c02ceffc2ae9202b21f2a1ec.nq.gz
    ├── 557554f94c02f00a781603c3ae9cfe2cd318ee15.nq.gz
    ├── 55db596024ff8936b274fd0e12197dd116af0472.nq.gz
    ├── 55ea2a7038fad13d6684221d8a565075aebdd78f.nq.gz
    ├── 566ef42e51a2f920f34b87205ac286d03854a647.nq.gz
    ├── 57e27524a7c31d81a24b27505d1ecdab6c76da9b.nq.gz
    ├── 58185bb4760d9011948917440f82235b185e7470.nq.gz
    ├── 583a44f8780bc4402a5a3aa83afd5e1dcb90077d.nq.gz
    ├── 585b35a858dafa614eea0179a880cd9912803942.nq.gz
    ├── 58f39dc98ce48b902b7726283d6893269e00879f.nq.gz
    ├── 59b03c83f3a5bb722e6c12b76bc3840c7f04dcb2.nq.gz
    ├── 5a195be213ef781b5851e99bb93f66af64a96f83.nq.gz
    ├── 5a54ffa3a324e746429f06ab5b0ac6545e62b714.nq.gz
    ├── 5b87bb66d32ce98cfbe897d7fc24c1f0d81475d9.nq.gz
    ├── 5bef0a18eee40c3046b69c7dbb7176d06e18f9ec.nq.gz
    ├── 5d420f2869f1b0e8c9dd600de86c9b7ae609c286.nq.gz
    ├── 5ec11a263f1b6faea0f48a58de74aa40db92f424.nq.gz
    ├── 5f08af26989df7421840accb4cbcde3539354463.nq.gz
    ├── 5f670b185bb1ac624fcb5a9ebc3be5f092a66763.nq.gz
    ├── 5fe91fa6b69ba048e5521b845e57b6f03c1e322a.nq.gz
    ├── 60299b5d071629400b989327144e4f2a4d05ed1a.nq.gz
    ├── 605a4a0eb08dbb91b7b83a4f9858c4cf9252d328.nq.gz
    ├── 611dbca2db7fb8721a124289f5b8b7560e493d30.nq.gz
    ├── 6179b87b6a4ce77e5d1af520f0385269db5474d7.nq.gz
    ├── 61944b6f6b7f858108cf20caa913935997e2f7fa.nq.gz
    ├── 62894d0aa33ca357ce54cbd2781ac7811a1043fe.nq.gz
    ├── 62f8121957a47384f81d1a54f5805cc72aacf96e.nq.gz
    ├── 63a7430722d8ac048e684c5785553fd353a31510.nq.gz
    ├── 63c2abfa6f45030082649aa71d40c7c49e81c1a2.nq.gz
    ├── 6529e714c03fc67ea630954d61a66d5878ff54fc.nq.gz
    ├── 656d2579a4b795745f5cc9bd87a6c5d8a3992473.nq.gz
    ├── 65d2a56d0f99edafe83feeb2112d189297cf42d1.nq.gz
    ├── 665f1632ecef45392ddd60a3fa0a430f8076938f.nq.gz
    ├── 6758e5be314cb8df740aaa035fe7ac380b6ae2be.nq.gz
    ├── 67a7b4aff3ec9d34cd3a01b0177e822e858c4d60.nq.gz
    ├── 681a17d00743b7b46efb82137c6708b7f8b63f60.nq.gz
    ├── 683b919b79ef9ac69d4f68e7acf5c9df180a6f85.nq.gz
    ├── 68fe35d9786e4648272b4849ceebb6c5bcf81e09.nq.gz
    ├── 69a12c15a504806bada62df6762bbcf96fa71727.nq.gz
    ├── 69ac583549aff89b24a60a2848c52b624cdd3b03.nq.gz
    ├── 69d8cd1f89a352a57b949c82efd8a54cd5dffc09.nq.gz
    ├── 6b082f06dc3471a3a1a91df99d8802a57960ae9a.nq.gz
    ├── 6b1ae8d2a2e729e8a05cef73c2b3bd928dae3a2a.nq.gz
    ├── 6b245b744120e592a2477f617650624d76a397c0.nq.gz
    ├── 6b681d31a308b415601424f15684396161ed618d.nq.gz
    ├── 6bad4b0e550f4e53f72f5c21258408badc04615b.nq.gz
    ├── 6bf6724682ff868fa35e32e4be6abf6e17540f11.nq.gz
    ├── 6c7051344d2719c097f790e7fd952385076d686a.nq.gz
    ├── 6c74f89aafb3607c6d4aa38062d6eda21f3889ba.nq.gz
    ├── 6d50b685dd7d312c31b5bd2f0d4d4d0138319553.nq.gz
    ├── 6db192bfdc93db3e74c47f657f9fe7a84631edbc.nq.gz
    ├── 6ecf75e93389ee243b1f8b08ebb81626c305e1d6.nq.gz
    ├── 6ed9ab79dc35264c2c454329dd06701fbb308c91.nq.gz
    ├── 6f20c93d3dd6c23aad0cc7ef53eceb34d0720598.nq.gz
    ├── 7018134b2bfa5675da8937eebf4f38a49ba2d08e.nq.gz
    └── 70b65af5ec1dff93cf08747be908a2238583eed2.nq.gz

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

[qos-ch/logback](https://github.com/qos-ch/logback)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*
