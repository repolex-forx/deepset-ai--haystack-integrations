# Repolex Knowledge Graph of deepset-ai/haystack-integrations

RDF knowledge graph data for [deepset-ai/haystack-integrations](https://github.com/deepset-ai/haystack-integrations), parsed by [repolex](https://repolex.ai).

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
rlex download deepset-ai/haystack-integrations
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d96d7d38dffe78f17decb98ffb2e40104a6ec476
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d96d7d38dffe78f17decb98ffb2e40104a6ec476
│           └── chunk-001.nq.gz
└── blob
    ├── 000b4cce8bc6e24bf96c0b275956cd6d231d452c.nq.gz
    ├── 002425bfc1688a4bc22c2248c1c3cea95cd72654.nq.gz
    ├── 012303287527ecec6e722243a9c1138e282fb35c.nq.gz
    ├── 01bc4d63c26fb10d9aa797fa62755bc1aad3974a.nq.gz
    ├── 051a6e79394e91284bcc5b33b62ce0f19dedf362.nq.gz
    ├── 051c1f26e10b65f608db89b0c398f41bb0596838.nq.gz
    ├── 05f51371f17777f25bae1acb3f7967bfe3a935c6.nq.gz
    ├── 06670d82f53a086d16b2153a6f63d6adef712c86.nq.gz
    ├── 0714fd8d9fc60e18c3cae00f4326ccf4aab0d2d1.nq.gz
    ├── 073795fb07fff06c19980cecc897bf2893dd6aa6.nq.gz
    ├── 078ffbbe3e80785a8ed1f0dd5349f2320ba92520.nq.gz
    ├── 07976066fc7cda9d3f4a7f65f19272ac125f4274.nq.gz
    ├── 086103b1ab21bbaf085f5cf4748d7948e2fe86c1.nq.gz
    ├── 0875063d2864b7decde5efaa5154384bb0991798.nq.gz
    ├── 08d293ecc3a0a829f7eeb293d6bdab0e1107db2d.nq.gz
    ├── 08fc9564158f5906ff742693737a5ee0fc177d7d.nq.gz
    ├── 092c1d0f9b2ee7febbc37461fb50c585663c1b2b.nq.gz
    ├── 0941c7ba97f985be89c1cbbe0871f3c8d91668c9.nq.gz
    ├── 09ceeba1571ddd1d14ec94e093f07db2640f162e.nq.gz
    ├── 0a36857e78e12e298b146c74e5a5cf5533980cd0.nq.gz
    ├── 0a40d431fc9c31d8c272e779bbac99a2522bcc9d.nq.gz
    ├── 0b12686d9579966558294ab2d08bf479241bd7cb.nq.gz
    ├── 0bc6d7ec963706f32bc97e6d5b95074d29f62603.nq.gz
    ├── 0cce883e2ada71f7a9362722badcc5571713150a.nq.gz
    ├── 0f891fb4d688ac091c6efe1e9a1f66d44ad467bd.nq.gz
    ├── 0fb79c939e655b2055c2f9e895a653a42afb5f6a.nq.gz
    ├── 10c944cb2fe7063bdc3ccfd564a081cb4096bc39.nq.gz
    ├── 123b3d6e2856e23a4d96fdb324a0c06dccd8f8e7.nq.gz
    ├── 12d4b8757a39c2503e23c2ad223bdaf3eb1e4a77.nq.gz
    ├── 12e7246f553c1b284bd4f40892f6aba07b65fcfa.nq.gz
    ├── 1354dd76c36420b5ca5debad808d432262729976.nq.gz
    ├── 14bdc8e690c8e0c1328a85d0e6762e583d8c42e4.nq.gz
    ├── 15a028e92abab0945b95013fcee22cd2ea642bf3.nq.gz
    ├── 1675f4cd2ef494646de0b86f7f77466e7bc532ae.nq.gz
    ├── 1784d441e4df652a65154b1a68602dbe2aeb433f.nq.gz
    ├── 17851507f2efd30a810e25c7edaf9fa3ec0da703.nq.gz
    ├── 180d1a02f4f792c1d0ec00b18cd306fbf9b1bc31.nq.gz
    ├── 197dfec8c5ba6a09e8b10e376fe554cb80dfcc58.nq.gz
    ├── 19f5642ac8796be723431b5c638ea927ddbe6931.nq.gz
    ├── 1cc4788848c4a23944e01fca814c86eb23491925.nq.gz
    ├── 1ec2c0caa485acbfc86c7603059662d1101af44b.nq.gz
    ├── 208fb4c4887cf8720b82db0bd6e6800ca49d56fe.nq.gz
    ├── 20dc6abb28aeb04cd9e275f41dc5b19547979b99.nq.gz
    ├── 2126d683863cba148e1ff353b8a386fd263d05c8.nq.gz
    ├── 217f360ad7d3b688745ff6071b873ee862aa382f.nq.gz
    ├── 21ce1211d686b3e7a5a73259c4e8914790274124.nq.gz
    ├── 21e7408766a2554e81cd0201dcd53fc3d9a095f4.nq.gz
    ├── 22e1ffb2ffdb2ed59decd31d7a1f9f18206a1131.nq.gz
    ├── 24423575d4088c6bfc17b811039b514421d69e26.nq.gz
    ├── 249cbf6caff345c271cd88b5e1b97222e99ba8ad.nq.gz
    ├── 24d78fadcbfa515c74c2450ec9042a3002c009a3.nq.gz
    ├── 25a073be675406b277b07201b83ee93940f0c368.nq.gz
    ├── 25e52d47f98d91087b3833e48a9d2951d6af817f.nq.gz
    ├── 282dfa0170f330a5ef2ade6661be9f4ad0c7c590.nq.gz
    ├── 28456c3a2efba70926ce5ff7dc0cc8ccf3975387.nq.gz
    ├── 285183cc99f70d6e244193221c588107a7410509.nq.gz
    ├── 299c77905c1b14eb37912d28b4e3eecef3a550c8.nq.gz
    ├── 29f3fb03e1ce021cee234d67bb27106cab6cf148.nq.gz
    ├── 2a5452fca09d692dbcccb229bcff8a723db7deeb.nq.gz
    ├── 2ac0f99c80b3e70c28286f134374afa5fd7d823d.nq.gz
    ├── 2b837397168c59bd5b6d5cc7bfd6fe686efe64e0.nq.gz
    ├── 2c97d2821c562dae4df4a33abb35e6c80e870d1c.nq.gz
    ├── 2cd5305734701bf6fa1d72c3ac4379be7c9f74d1.nq.gz
    ├── 2fdfc96597f84855842d81ee21665963c0e0fd15.nq.gz
    ├── 30b51fb4e1095309dd9a2a228b813ce565d2ae1b.nq.gz
    ├── 312bbbcda31d47dfcc009f42932e69b59dd16915.nq.gz
    ├── 323d7eaeff677a068730e7a1ffeec0c99bbf2095.nq.gz
    ├── 3368456f75879fd329c39eff98e6b1fd10e8d33b.nq.gz
    ├── 3379737e8845b9a718e0b020374a3482b4512d08.nq.gz
    ├── 33a740343ad1c4c7dc08178cb8a029f66e3d0864.nq.gz
    ├── 34aaab4f9d33e143be3ef48de70e831793256b4e.nq.gz
    ├── 35502d03becada1093f34125d9745c80b79adbd7.nq.gz
    ├── 35e909f796ddda1f27a3b4d7f2856f8401c951d4.nq.gz
    ├── 3676c0177d6f8735827c70595eae668315915892.nq.gz
    ├── 37333ca861cde828f0cedef983ebb70cb64a1572.nq.gz
    ├── 3788d682f380b9594ef19be9023d2e8f0a3175e5.nq.gz
    ├── 37c444ed89570322f05b15c9c8729709d32afe4a.nq.gz
    ├── 37ca6b75ca4d6c0ddffdfd40b305ec10084a9099.nq.gz
    ├── 38558e4a560c3d194eea31b5d49bff2bdfb02922.nq.gz
    ├── 388e7acb3b6edacdc6dcc5a05078b4789ad9b6e7.nq.gz
    ├── 38aaded688e3cfd06954a5d769d5f307801a6119.nq.gz
    ├── 3960e8c15c298a62df0075a0596348231a5f91cc.nq.gz
    ├── 398695516b2283259a41ee18e3c924a200f43288.nq.gz
    ├── 3cd1028ba0758d1e8fc4277e1c325d091acf13fa.nq.gz
    ├── 3d11eca93ea61166f4322e94ed2ff84b73b7c972.nq.gz
    ├── 3d28bd1ca9dcfd70ac1ee4225e22c8c94dcb0c11.nq.gz
    ├── 3d74e648a90a206a6a93539c837a93cfc46412e6.nq.gz
    ├── 3e96becbcc989317ce74ffaa4db67b46ca6f1425.nq.gz
    ├── 3ea2bb42071d21b8a55554063fbc3b67b12c113c.nq.gz
    ├── 3ef95551609dc64e8e1f471e091da17104382c5a.nq.gz
    ├── 3fb65147aa1f9854ef220cc24ac9bac53b70e726.nq.gz
    ├── 3fce66b34c998ae69645df529aa8381d62bff66a.nq.gz
    ├── 41a8d35aa834108cdfb86d5b9d8eef369367c324.nq.gz
    ├── 42ce1d746bcd3e7ef5472888d760919e1e56cd24.nq.gz
    ├── 44a9af97898f64312564c9c1b266989951fb8d1d.nq.gz
    ├── 478e7257d1998ccdae9187f72b0d2d2844935b69.nq.gz
    ├── 47df9d1ef7b61d52e1a973292659ed18e4692aff.nq.gz
    ├── 482339697ece6fc92c305907d23bed51fda3e5be.nq.gz
    ├── 48cb8c0b6642de9ab26a01623e43f686dcdf168d.nq.gz
    ├── 497fe175841a9c6f436346dab99710bd9d1b596d.nq.gz
    ├── 49ff9b984de4e128980c601ed27914aa2ee9b042.nq.gz
    ├── 4b5c0007e26bd95f4bc239af2bba749253c10ac2.nq.gz
    ├── 4b66ca54851f5bd2e93d323f305da21630d068dd.nq.gz
    ├── 4b98a6a39108d99bab4ca0111991d3848e2ae997.nq.gz
    ├── 4be73c48ec62410f9009bce6e9ad3b2ef42b6a8b.nq.gz
    ├── 4ca33f24dd5603f223a3e54a0054fac99efb3c06.nq.gz
    ├── 4d2bc708b7981ca15e7399902175bbf2b5e451dd.nq.gz
    ├── 4da8b7655009411cb213014e0f24534ab9c5b552.nq.gz
    ├── 4f58f23c34b2e81af172cec9e18e0f6bb236e217.nq.gz
    ├── 529de088928c15382ff7a3748a68ed65995fc19b.nq.gz
    ├── 52aa0807272ecd9f34e70c7bcf094019f879adb4.nq.gz
    ├── 53d55c7c3116bd78f6439d468695883e75f32369.nq.gz
    ├── 53f66f568bbc895890c31dd7d2d60f97057aac05.nq.gz
    ├── 54e0283c27358000b63ce34aef36294a136fb257.nq.gz
    ├── 583392a044c457b0abd809e1596ae0dab632f986.nq.gz
    ├── 594cd2016200c417bac510de5f65ec52373b097c.nq.gz
    ├── 5a108157a547c799bd07db2243ab447d1b2abf40.nq.gz
    ├── 5a1f9a5049e355e5dd9cb699968efc9be3cc7428.nq.gz
    ├── 5a2f720ca2762cfa9f92909ed4a9e568969dd6c1.nq.gz
    ├── 5abe7a73038b09886e09f32a86f7b3a1b6cae6b7.nq.gz
    ├── 5b56fba978407e9ac6719ff145932059acc1f73e.nq.gz
    ├── 5b7bcd04f614d71bdbb6380628099344b3d428db.nq.gz
    ├── 5b922111ab535686dc1c49a0c731ad8ee24ce693.nq.gz
    ├── 5d4b2056f8848f1a60850632dce6657a0ff9bc11.nq.gz
    ├── 5ebb7c7b1194a3a5e9614ab882deb0e67619b57e.nq.gz
    ├── 5ec335e47e38fa99137cb5f6b5819ecaf70ac67c.nq.gz
    ├── 5f53a0b2e13fc8e54447c839775dc7e9271d9d86.nq.gz
    ├── 5f86846a603126e1d1baa0eb700ce2f7303cd627.nq.gz
    ├── 5f88be079342d5969f6297c1ec51f117ca5715a5.nq.gz
    ├── 5f98c25f22f84619508bcb54aa8d090ad495ba1d.nq.gz
    ├── 6038f5153a938514c96e1e3952f6a8ea38022282.nq.gz
    ├── 607b9eea1acf2c43eae2aa3af7403b8bc5e27352.nq.gz
    ├── 608e4e1341e5663470690b79fd8e13bb6866c956.nq.gz
    ├── 610f10b4b7af7b35428551ebc487f8654fff0c1b.nq.gz
    ├── 617ed44f1fd877af540c895dcf49c504841ce315.nq.gz
    ├── 621f433331d03e7a4b540c72dd727c0fcea03170.nq.gz
    ├── 6225b8d11f64e75df241089227e55ba048550179.nq.gz
    ├── 627201b70898f06be75b3b516fb44142d6a9d409.nq.gz
    ├── 62c4875bb93bfc29d564f0160e3f08f677067f97.nq.gz
    ├── 63948fb681cbcf44c692c1b2c577eb51df4cba46.nq.gz
    ├── 64d58c9a6737e4f11d116670582b13262ae81266.nq.gz
    ├── 64d5e42ab0947b9d2ee86d2b745b01c5822961af.nq.gz
    ├── 6573853c9df863144458e15e6335f5347834a333.nq.gz
    ├── 65b4fb69a72c2b25ac379edf795297babca33db2.nq.gz
    ├── 66278020fa638f3a60adc9caf2838b8824045a19.nq.gz
    ├── 669fd1ad7a4374809b925f1d41a7893f2ccef26c.nq.gz
    ├── 67976269d1e8daee30b242d2d023bdfbf410348d.nq.gz
    ├── 6981fd012311cca1855cd0b43edee2bb4cad41ee.nq.gz
    ├── 69a91abeb7c6d071ccab497b63d4b3ad471448e0.nq.gz
    ├── 6a25c73ec68b437b20e0a4ac1492561dc5347ecb.nq.gz
    ├── 6ae3c7b35a4a929c454fc88a51189da168f0a39e.nq.gz
    ├── 6afdb8ee14eba1847d54b35b5a6ff8577660c171.nq.gz
    ├── 6b2467b8ec3f19b91f0faea68a779149291de0d0.nq.gz
    ├── 6cb3b705d018006a2bd4200ea94c9d5fb98b6f76.nq.gz
    ├── 6cc32970567afad292261c9f88dc828bb1c082c2.nq.gz
    ├── 6d77ce6968c0032a30ff3c24fce530ccee4b504b.nq.gz
    ├── 6de70667405125481649c88812cff508f4aca72b.nq.gz
    ├── 6ded6c402201601741b7e7af95c2683b90230fab.nq.gz
    ├── 6f1ac23689daceec34da628480a4897052820c6c.nq.gz
    ├── 70cf5181a0ef5b2436c7d98ccb519a9d8d802326.nq.gz
    ├── 71069c478563328e593105a3cb213cd2525882c6.nq.gz
    ├── 71c4dde9d76b673731c4bdf99f67dd62e9e73f40.nq.gz
    ├── 71cabba7c1561a759fba16405835e482debccfd0.nq.gz
    ├── 723800373b6756afc2df21d6fdd963f3feb93855.nq.gz
    ├── 729a6db95f5b85279c043dcf6570dd499393d6c9.nq.gz
    ├── 72e1f349927f4e9e7cc1293b7cac29de20ad727c.nq.gz
    ├── 73092d09a2175df349d9a7f61da9ef60f92df813.nq.gz
    ├── 746dba22679194a2d758d0dee96d7a2521cd8c8f.nq.gz
    ├── 74f5546fcd7e6b5821c10147cad5c6b6507f7964.nq.gz
    ├── 7734a4d7d7748719b28b38a9e0ce23b7f0bdf0a6.nq.gz
    ├── 77c19b85f0aaebcf52ba31bb4640e28a6fcc9e3f.nq.gz
    ├── 77c50c711c3541727379c64b181ee2a57778bbb1.nq.gz
    ├── 7b4493c91e3ad7daadc114f179686d51b295c554.nq.gz
    ├── 7b6492d0f6ee78c459c993577d566932627c34ac.nq.gz
    ├── 7b752463e67d011e3ddb5a453aae03353083aff6.nq.gz
    ├── 7c1ec511888d7cf6be828c5e7fc012a6de7c65ae.nq.gz
    ├── 7c750318da4477aa49b555b3a3f3f7e5c6060a2d.nq.gz
    ├── 7cf71b5c351ff4b5052ffc397ad6a8684220d087.nq.gz
    ├── 7d0ca403799dcd65727504ed6be8fd0fedd3f43f.nq.gz
    ├── 7f45e952cb5b0f7c7b15a860acdb4acc47b79c48.nq.gz
    ├── 7f583f21d5d4440fb1a6694ee2135bf54f34bad6.nq.gz
    ├── 7fd46b66c42d3d58bc23ce9ef33ff3796b3e4bef.nq.gz
    ├── 7fe2bc1fec55a7ee6d089f6574db6d23e6024f91.nq.gz
    ├── 80562af6b36933c3de5f3de1c1ad654f5581c941.nq.gz
    ├── 8072e8a840cbbe842531c700d98b6407e738cc3b.nq.gz
    ├── 8098a9d98bcb174c4b0ae42e498f0cd814ffe954.nq.gz
    ├── 80f5769b0d86ea92bdf7e93f6a8b80897c04520f.nq.gz
    ├── 821c42ce28390badcdc89636eac4c9b2316d48c2.nq.gz
    ├── 822ce1d497cd6aa5596a696cdcee75aa27a3fff9.nq.gz
    ├── 83632748ce1d5a626520499422fe97488432bc63.nq.gz
    ├── 83acf25ff993385f2252b1a2ba2fd169b77181a3.nq.gz
    ├── 845352ce532e147f969a617b834b90932cb27330.nq.gz
    ├── 846a465ffeb8e0b2a32e6f9f26f1ad0e57ded6ee.nq.gz
    ├── 8481e76a6d7383a3a9a6b83f8b97dd5e2b132c1d.nq.gz
    ├── 853618a86d26d111816d003785872cbe73c0fef7.nq.gz
    ├── 86b035fca58619ef09847de53c270593622e7b3f.nq.gz
    ├── 86d42c43a3c96d47ab645728d09080187eb6097a.nq.gz
    └── 86f17a8f04c3290b557b2cdedf4998efcaab97b0.nq.gz

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

[deepset-ai/haystack-integrations](https://github.com/deepset-ai/haystack-integrations)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
