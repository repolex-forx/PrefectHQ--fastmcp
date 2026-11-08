# Repolex Knowledge Graph of PrefectHQ/fastmcp

RDF knowledge graph data for [PrefectHQ/fastmcp](https://github.com/PrefectHQ/fastmcp), parsed by [repolex](https://repolex.ai).

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
rlex download PrefectHQ/fastmcp
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 936a9659d871318fc314e7210a191884eeeb8d80
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 936a9659d871318fc314e7210a191884eeeb8d80
│           └── chunk-001.nq.gz
└── blob
    ├── 01ba8c32f5ac19719cbb93ca5189850dba92df8b.nq.gz
    ├── 01f117531b57648319e737c2d21074043894df09.nq.gz
    ├── 0204b5c30d7d09672dc5de1b158bf4c3f710f5da.nq.gz
    ├── 02329ca60620ea9c70ce05314127e6d86b2e52f9.nq.gz
    ├── 02fa36daec71b9899d67d929a7d3b0be1408906f.nq.gz
    ├── 03a3f7b1164bf4524db4209dde89ae3fccb69171.nq.gz
    ├── 03aeb93dd646857f4c95f3ca46f38f2b98e3a342.nq.gz
    ├── 03f32cbb836e7f5f038e95be92015f82f6f6729e.nq.gz
    ├── 04ef45aff4c51a04f99345c9f3ae4789765682f0.nq.gz
    ├── 052675a59145e966f6cc55c0c691489a13bef9b7.nq.gz
    ├── 0549ff22894f3924efbb9652c9bb43e89d92f71d.nq.gz
    ├── 0598fe6af65e3988aa6b4706e26cb1202ca904f3.nq.gz
    ├── 05c6e5d7b83738f7c873db8f62c8b03cb1931c31.nq.gz
    ├── 063fcad011a6b985fc80600d39ae314ae1e2f1e3.nq.gz
    ├── 06476f71b4385a79169387c0be22a569f8ce71a9.nq.gz
    ├── 065c28471bfdbd498de84ef6dece3fcca45f0b71.nq.gz
    ├── 066f5b1eaa1e52870c58438850d0677e63e074e7.nq.gz
    ├── 06fe6285d0357021a0eb5f5621f05639975629ac.nq.gz
    ├── 070fd9b6cb825e9733cc47d936138312bc3a4216.nq.gz
    ├── 07a8db5497de37cf70d8c4e8a2b7863d3f63f604.nq.gz
    ├── 0808f6878ffc59820d79aa8e113e1f1880b34dc0.nq.gz
    ├── 08812ba9b064891fd437f113c3a7372a4226eed2.nq.gz
    ├── 08b616dd4322ad8e8ccdfe6007d7a653047583de.nq.gz
    ├── 08f5c9786a51bd5c33278cf4dd5f0001fe0dbf84.nq.gz
    ├── 0912054939d28617d64da88c41fe7873b0eb7cdb.nq.gz
    ├── 099a4a0429ffbdf75896b723c3f1c521dc40dc92.nq.gz
    ├── 0ab4e0c01e9bc4b99ea6b6a63094f01ba6831cc8.nq.gz
    ├── 0b56ddc65db3a43ff88dfc6e9aaa8d9ea88b538a.nq.gz
    ├── 0bad9828a4ce8671e2ce3bb01b430428570c3258.nq.gz
    ├── 0bb8d8177fa0303432a679f927960887b36b999b.nq.gz
    ├── 0bc6dda6d86da556d61bbd42edd77d3d070c030a.nq.gz
    ├── 0c35b6fe4b4e64fac20b73364d9f3d6a6ace3eb5.nq.gz
    ├── 0cf914ee33fe2627b8bbd08500b1278d282268fb.nq.gz
    ├── 0d3a71ac7bc686aa8f71c7f283d0cda86c79c5d6.nq.gz
    ├── 0f4980cfdb5e2c8f27f3604f7a3d0a5267e3c0fe.nq.gz
    ├── 10073cfff97c180d14d5708ef03ece42529eb0b5.nq.gz
    ├── 10fa05f168379d1f624e120b8829e561cd2a9a48.nq.gz
    ├── 1178c09af1bee9483d4485353de47e9ab9106c0b.nq.gz
    ├── 1226cda642c6ed85612d0e554a60ccde5cf2225a.nq.gz
    ├── 129ad5a6744db0e941d646aa1878386cd9578308.nq.gz
    ├── 12f9f6fcdfdcfc9f39b8b88daecfbbcf1c959e58.nq.gz
    ├── 13e5e060e27cf07dab66908dbe5568c1c75cc4ba.nq.gz
    ├── 14f9a9d5908942b4f489cf97c3a81d95a65be856.nq.gz
    ├── 1594343a50d7a317ce0f2f964963447c183384c7.nq.gz
    ├── 15f3e9390a260a07513028f73d9819b56ff907a1.nq.gz
    ├── 15fcb1dc34785a8c1a01561dee97a7affa7a09c1.nq.gz
    ├── 16191affb62f1584450a11b409e6d504b195c516.nq.gz
    ├── 164e4ffbf784382bb13317dbfac375212d4d90c1.nq.gz
    ├── 16f2f9829b7fdb1d06d25bcc76577dff6e20c2a4.nq.gz
    ├── 178b3b25068a9a9a3c29b7ca86812c4acb35a6d2.nq.gz
    ├── 17c4544a6d6abd87905b1d612fd41315104d27d2.nq.gz
    ├── 18c3bc6f9f964a597eac18e55ee207a5465f8cd8.nq.gz
    ├── 18d56f2e72321b59df75b3cf6feeef01faaff877.nq.gz
    ├── 199bff1bc05699639c121a74de16e4d4ac601c8b.nq.gz
    ├── 1b17ab6ee3bb6bef998a705cda8e45716ab99ed4.nq.gz
    ├── 1b43da59e79d2116424c01bef2b23ada5dbf3245.nq.gz
    ├── 1b4da47be4ebc8baeb1b29465f6f9bf3296c782d.nq.gz
    ├── 1b7c30a0c2c4723d0522f6f7a92e8dd628d6edf5.nq.gz
    ├── 1b7dfa9c771f65bdf77a2c2cf327740754a49e68.nq.gz
    ├── 1c29c8ad7f4548183b923c29dd66a7c1d79acf78.nq.gz
    ├── 1c36e6cfda27025d8b46c2ff5d79f050ef165045.nq.gz
    ├── 1dc8fd0a5ec12581c84e4853e37302be86b93f56.nq.gz
    ├── 1e109b76ad859dc7f320bebec397e7f8abac0a77.nq.gz
    ├── 1fc3795541611a5053b683239f841a2f558aa58f.nq.gz
    ├── 20007f3e5462c75e5137f766e13ccd7abbbbde34.nq.gz
    ├── 214cd822287982d9f3d0dcfd732c0aa415635f8c.nq.gz
    ├── 226fada9469e1531c57e2224354b0c6d5dd9e305.nq.gz
    ├── 22c6e734e1dccb620d4f36c8582c788395993d79.nq.gz
    ├── 24cd6328ca0fdf4d9038a86232087e1beba4c0f4.nq.gz
    ├── 2511839df8dda8b66aa9dfdb0ce3156c943615a0.nq.gz
    ├── 25b8580b02a47b250293dd7de62a0e96bf748328.nq.gz
    ├── 26d3e9dfc2dbd4ee2ec76117e0e535e134f05ace.nq.gz
    ├── 27776c1bac1ae5d968510f9cf47cc960a720696a.nq.gz
    ├── 282a51e1763e981faa91b849541ecb32da639cec.nq.gz
    ├── 28834f350971c8b9d8f2920f10538a2a24afb076.nq.gz
    ├── 28a6abe5a3e52bd92d4de1440c724dceae749e06.nq.gz
    ├── 2aad309a22e21a3901bb868b8d740401d8124e54.nq.gz
    ├── 2abce7f16538c03fa773ab5ed7260e494e716f9d.nq.gz
    ├── 2c25dcfc486c7a3511b1f016994cd369b2b41b9a.nq.gz
    ├── 2c8cb1b4632e97592492e9d37fd1084779ab3f63.nq.gz
    ├── 2cd1838f2d3b65e6811a50b27f0eaa6eb17aec1c.nq.gz
    ├── 2cfe806b1297dc7ad235c3326f384b0cc5befbc9.nq.gz
    ├── 2d6d747ff035e11df29ad76834e7c203b2714a94.nq.gz
    ├── 2e12fbc13d8166b14ea717414f0a49ff765dc266.nq.gz
    ├── 2e139aa8497a90221004175c73d14a1617f28e7a.nq.gz
    ├── 2f0ac00eb307d986842d0d170b5ba6614845f452.nq.gz
    ├── 2f93bc0ca392d6065187bc3fe0b1d69ce00b12a5.nq.gz
    ├── 2fd2ca4a59986e2f58a7220fb7e7fa0f9ad1ba8f.nq.gz
    ├── 2fe8589131f1045827b40dd8bcb0794b8b281efc.nq.gz
    ├── 30567e37e8588839b7a32555fba355926f8cd139.nq.gz
    ├── 30761f77ba7af7d8a37dd11de4c5db9d33cff569.nq.gz
    ├── 331fdb1943dfe4dc6219d1702aae83f1b9ed5e20.nq.gz
    ├── 346462736d83b14fa75cee7362a7602c89dce7d5.nq.gz
    ├── 346dc8cc80809d5005ea3eb2825b441e534985be.nq.gz
    ├── 34b2496aae70a7967f4846fa2ee257af0252f61f.nq.gz
    ├── 34d42d481f41e8b435dc192f07f6f49567200307.nq.gz
    ├── 35a71626e40e1fc0b79918fddb2e64326e546ba7.nq.gz
    ├── 36390326796b0b0d83e576abb9510be7b0a676af.nq.gz
    ├── 375db8e91e77ee0734b60461b0680f46db4ae23e.nq.gz
    ├── 378172e2a3025516ac185f968a82a6c45c4f8335.nq.gz
    ├── 37a0937b647854a402c666ced3eb6a17d984b92a.nq.gz
    ├── 37f33cf27a8c2615d5cf91232682024960d08fc0.nq.gz
    ├── 38604b92f48ad8adf0aa82028c214a96e6df589e.nq.gz
    ├── 38f9434a02cddffd6f9b29d0f86a7ad12335144a.nq.gz
    ├── 3909565f21a9f3d4222d0f345052fe19436d98e9.nq.gz
    ├── 3954dab07c1524dc0ad59caba386912dd284b64d.nq.gz
    ├── 39a2ba77b51362385176607d921ef6831d98bd42.nq.gz
    ├── 39a9973a4a16d5c57baeba289fecb5dc4fee1f2c.nq.gz
    ├── 39f06da41c6d5dfbd57bf337c7268c4e9451bfe5.nq.gz
    ├── 3a9d3bf46a2ff58f13f833ff2b61aef978ce2f4d.nq.gz
    ├── 3b0361ad87438976fca9c63bcd2ad89c80caf205.nq.gz
    ├── 3b3b4ef40c349b975170250528d4035337ac0fa5.nq.gz
    ├── 3b3c012ef5ae1d02d5ff30dc4be2bf5cb7aa2906.nq.gz
    ├── 3b65f9c4e859223fc84c4344db46cf8dda67e3fe.nq.gz
    ├── 3cccf548f067f26ac2957cd02a30c72d10a91d3e.nq.gz
    ├── 3cdcf3be5cfa1cd30938bfcb3828a35f7838f9b8.nq.gz
    ├── 3da91617778218c4fb42bd52a3ac5356a97751e6.nq.gz
    ├── 3df32919d5e50c95f99977751301f09792b81ebf.nq.gz
    ├── 3f7bc09509ee684fd26876e1787c093a826d38e5.nq.gz
    ├── 3fbeb494064cbb60fefbde870637b41baf2fd16f.nq.gz
    ├── 3fcca5898dfa33f10c36183dd26c8bdd13d4500b.nq.gz
    ├── 40b3cc5da2dcd33960585d885ba8838ad4528c0c.nq.gz
    ├── 40d80eb4de5a26cc00493e7f95e6af19fb8c3ef3.nq.gz
    ├── 40f116bf949c8aafee3b9b388a9789e5c47e5baf.nq.gz
    ├── 411a2e0f86d4205cb8b5836b08b8e6098f558503.nq.gz
    ├── 41896f211af5b2df07a326d4c153207e5d08f61c.nq.gz
    ├── 41aa450d8b2fcd4a2714b25c43d2961f0f7cf9f1.nq.gz
    ├── 4281e817276362f8a69861bc070d01d49fe53f7a.nq.gz
    ├── 4437538d2ea8cf4f37d736479ade1678cbd4a817.nq.gz
    ├── 4448e0012bd4b6b00ab5033315e1ab6ed4ff3567.nq.gz
    ├── 453553de2dd8fce035ee8c8e2c5aaf55ca48cd17.nq.gz
    ├── 464b6e6f82a3d6ed1b4622a0a6caa367c7989eba.nq.gz
    ├── 4653368be89f50a77c048477f153f39967833f65.nq.gz
    ├── 4678f4e31186fbb0b5fa8f3ce732c2b5ddce57bc.nq.gz
    ├── 476e68b89c67bf14ac67d13ce1029cc8ae870817.nq.gz
    ├── 4776eedb520d20f72d86a7e89a6684230e7009d6.nq.gz
    ├── 482f94f112439b6a148f60f1975f00d2dc87d662.nq.gz
    ├── 48a536632790a3c30a51b8311c310255fde08ca8.nq.gz
    ├── 4930c25d96abc68750161d3726916f6852d63fcd.nq.gz
    ├── 4993d73564ef14fbe459c05e503dcef04e2f449c.nq.gz
    ├── 4c261f24ab4fad1de69e7cb7c91cd487959123a6.nq.gz
    ├── 4d6a996e9b75956b14de74f297df6326e91675fd.nq.gz
    ├── 4d6aa96b81fd24bd2587d1e51e2a7a655e40154d.nq.gz
    ├── 4d9635e34db7002138d89a0e49d12d940c79f1c3.nq.gz
    ├── 4ee4e7f5763ac48d2bcf1d82e08f2d11fc7536f2.nq.gz
    ├── 4f9ef4ec2e7f0851d5b49b1086ad65846f438e89.nq.gz
    ├── 4fc6a1c648006cc7d2c21e773e3df2aa00c2c1fe.nq.gz
    ├── 5100237bfa2e6bd9368ede5892fb6e734572bd58.nq.gz
    ├── 5230477ecb781e2bbf1d4c4c17b4174863520532.nq.gz
    ├── 5397d75e4dc8b53c18e8a5927cb97b5ab9999735.nq.gz
    ├── 53f4f4a66c6e20b67e82b811f1bebf7f9f1d9cf6.nq.gz
    ├── 54312337be86d24ab5d4ef3f176c32b8e685dfe6.nq.gz
    ├── 5585edcdf5e01dd6085c21fc45ca4827d180abdd.nq.gz
    ├── 566cd3ea4d3ba47a238bdbc5bd81db5ce6f60877.nq.gz
    ├── 5716e1f735142a69faae46d0e481774b5fb1d00a.nq.gz
    ├── 58593c5ff164a1c269d104152937d2e063e59a33.nq.gz
    ├── 5859c59c21a0d498f10c171e4a23524651f44626.nq.gz
    ├── 5984512378458a8195ac27c3a7c5944382e26da5.nq.gz
    ├── 5a28fdc126a13f1a229cce59162d6a5ddeabd90e.nq.gz
    ├── 5aed17c4bb44981814653c75c0ff83f5a93e80b7.nq.gz
    ├── 5b831770d49737d5f47cabcacb5c371d518a6f28.nq.gz
    ├── 5bd6f4a8fcdf94c836d4fbab18089d52d40aad44.nq.gz
    ├── 5c920063cb3cdc642ac9978a7f319d22b140a462.nq.gz
    ├── 5ca2df003b9b93491e907db7c5f51f4f5dd91a50.nq.gz
    ├── 5cba992c4eff3fcf1e41a6ec1965ba2373b8648f.nq.gz
    ├── 5dc7932e49d9c9ccdd767b471f639d5df013eb05.nq.gz
    ├── 5e211a5e9553bf201d756b2604fe5eda55bff025.nq.gz
    ├── 5e4ff731b71ad383b5659fa24aae0ca2b7b743a7.nq.gz
    ├── 5e72fb0c506e94615a11210a1364cfb65b606913.nq.gz
    ├── 5e90c43936cf30aedb8702f5e40deb310dcd2820.nq.gz
    ├── 5f1f39bb2f200a25ba397ba3d9adc853bba37d02.nq.gz
    ├── 5f53e3c7fb13ebcb156049e70ca07b7a02420cf1.nq.gz
    ├── 5fe082a6306a8b5a381a696ebc70898a79ae4783.nq.gz
    ├── 608af8cfe41a56a4c00cf79b4cbe886329f8fd12.nq.gz
    ├── 6094ac56aaa369b5fb6e0b3bb2ed0504f600e896.nq.gz
    ├── 60dff92b54baa90bf095e8edda7d41b9e5139ffb.nq.gz
    ├── 6108eeff665ec26b329f74ff3d5dc4f485aa55ac.nq.gz
    ├── 626fc7798bc24cdd4eb53f426e8a37de7595c662.nq.gz
    ├── 62892dcfd3b5aa9cca9ccd5010a7bd18fa4a030c.nq.gz
    ├── 62afa8df279c9ad8f80b64334cc7b0f882b4f466.nq.gz
    ├── 635defc0bf31eefc4e48740cc6b642d22288a046.nq.gz
    ├── 64e623b693f028a33eec0df8b4668045ac9fafbe.nq.gz
    ├── 657a1c14e98e55ea8e30c7d53226ff5b48000c4b.nq.gz
    ├── 65e60ef1e54e6f6e1d53b704bb43f7b922e71032.nq.gz
    ├── 65fb50b8d85fc87403aae0ce1bace49f4fd44d1b.nq.gz
    ├── 66cafba3e8f4022372eb1fed3e3a681a85535e56.nq.gz
    ├── 6890558b164a069fc5f75af068f6835b790ae403.nq.gz
    ├── 68e1c1fb93b31ba2507119049c1b2bb8755c8ffe.nq.gz
    ├── 690f8d3910d18ea3c3b10e1db68e69ee6c627864.nq.gz
    ├── 692ae921d9f3112205a4116ce4ebd9eeca39b282.nq.gz
    ├── 6a5c76c3a1f3cb2bfa96014a99279d8ae8486de4.nq.gz
    ├── 6ad1dfe576460c8d8375b2247ce4aed3e81b8e7b.nq.gz
    ├── 6b142da2996ef645bdc4693fa6202b2ca6f245a0.nq.gz
    ├── 6b32268cdc15abc2b6d3e010af5dfbf38c2b75be.nq.gz
    ├── 6b5b92c128f5b6e448fe3d5d7298b12916f10357.nq.gz
    ├── 6b845c3bbc27d6871eb51f8219d2bf2105202889.nq.gz
    ├── 6d0f58fce1e5409ab13a1a755859850dc72caecd.nq.gz
    └── 6d2e20e3bb47b32d50dbe23405a223528c466401.nq.gz

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

[PrefectHQ/fastmcp](https://github.com/PrefectHQ/fastmcp)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
