# Repolex Knowledge Graph of allenai/scholarphi

RDF knowledge graph data for [allenai/scholarphi](https://github.com/allenai/scholarphi), parsed by [repolex](https://repolex.ai).

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
rlex download allenai/scholarphi
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2fc30ed4d1c4c8c9848b12b8af61174376a7f425
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2fc30ed4d1c4c8c9848b12b8af61174376a7f425
│           └── chunk-001.nq.gz
└── blob
    ├── 00938fefe048b07fede7186d235179fe6ac2482c.nq.gz
    ├── 011f012eb5eb96f17f34b703feb2950e61e78c23.nq.gz
    ├── 0250307c0d10b0c0a38a8381361ec265ef3080c8.nq.gz
    ├── 025dc9040e5073bfd18da3464566163456f72534.nq.gz
    ├── 02b41d334c3777c976bbeae33ea5da00d4dd1e4b.nq.gz
    ├── 02e330e637d92f34f1a7d49fff073932542e7f77.nq.gz
    ├── 0496b3577555195f96498932403c030411769159.nq.gz
    ├── 06cf9ecf7a299e6a4dbee648f238e084ee864d58.nq.gz
    ├── 06d4d3769672390920ddd9d423f52d7908fcfb36.nq.gz
    ├── 08a71aea5a657573fc306091269d470685def3f9.nq.gz
    ├── 09361eba35b0939351f28ed16ffb0c462811fbef.nq.gz
    ├── 0938ec107cb39419872748a3a665ed1d0cd50810.nq.gz
    ├── 097a5829f793d88edc4060df8ab0869705f7c4f4.nq.gz
    ├── 099d29e11637b362d377b46a434d3643e85efb50.nq.gz
    ├── 0a1a8d6243e87ad04bc7e98ac3eb8aaf88162d30.nq.gz
    ├── 0a2f93245042375ebdbabfe17495d8b2d59d02ee.nq.gz
    ├── 0a5b4fc089c3ab39fe36f5ff396d3901d8a52f09.nq.gz
    ├── 0b7bdd57e4ae920f6bbd3f23f7e05d27f4777990.nq.gz
    ├── 0b8427a16c0f347dc36dc4b1619edb8e166d3b53.nq.gz
    ├── 0bc10329d32021064d76c9fc58e95bbff0b08d09.nq.gz
    ├── 0cfeeae8f7d8fb1edffaa79dab49d35d272ba267.nq.gz
    ├── 0d08ed3730f6edfe7165ed8d21521c0ebe97b234.nq.gz
    ├── 0e483d4416b8a2fbb74b5523ea54f2935259b19b.nq.gz
    ├── 0e4aa0a447367975b1d49a886f30c14180506bc2.nq.gz
    ├── 0e8d38d7a29119ec13531a846cb0e3b7af341bab.nq.gz
    ├── 0f2b8e4ad505b840f064e6ae4d772a740e3456ab.nq.gz
    ├── 123ade1b4049614e88b2325785f936c4e27e3631.nq.gz
    ├── 12bae83a910277a30f57e8e30a5a4ed2f17e2c37.nq.gz
    ├── 12d7af53679c4f1c6c26d48ff1e60642c3339239.nq.gz
    ├── 134170af3a954a366846dd52ebef617fab11ea46.nq.gz
    ├── 1392fc39a96d8ece5879b18d54ec78d23a4d6ce1.nq.gz
    ├── 13cb14b3908b8d9eded91b13ff8274099d2787c1.nq.gz
    ├── 14fcb0c100bc4b5e400c2afbcdc49d126f0cb3a2.nq.gz
    ├── 156c26b941c12a13130e7a7c181d13300a85de89.nq.gz
    ├── 1603c43c2dc4be0adcf42c5c9189c9911f6353ee.nq.gz
    ├── 161147354c938270316935a777456fae2e31b169.nq.gz
    ├── 165fc8bc01381b74b773f0775eabaf9f47b16ad9.nq.gz
    ├── 16ebcb8ef1e923710574bb914e19526f2545abdb.nq.gz
    ├── 17690d5567f462c1122b8591602f2ac59ca4ecfe.nq.gz
    ├── 1957f79ab95a970cc93eaeadec532661c5a1ae55.nq.gz
    ├── 1a37925295a20d130e8903c9a216cd94257d36b8.nq.gz
    ├── 1b9c2ef69686355aa1403c034a5434eab0b83dc1.nq.gz
    ├── 1bd8507405f6d733e5167f0f9366335d911eb4d6.nq.gz
    ├── 1c72ebb554be018511ae972c3f2361dff02dce02.nq.gz
    ├── 1c794e6c4483f85660a297cbb40208fbd27d709f.nq.gz
    ├── 1da6dc949cd6451c2d8ea39e1618d0323d2e1ec1.nq.gz
    ├── 1e1c51719b037dda7c556299629b3844f0caff3c.nq.gz
    ├── 1f862adb9beb5802d9541fe82b474b8312cbd394.nq.gz
    ├── 1f8afda21384d6341fdd417f33f2e7fc04fa3fdd.nq.gz
    ├── 1f90f83da745ff2470745ecf1c0c276b7179b088.nq.gz
    ├── 1fea71a22d7025f17d7241f129c6860af83f1562.nq.gz
    ├── 20d92c16a11926eaffd1618fba9d66faf2176a85.nq.gz
    ├── 21d1c284f0eb8dc1be5d0a4731abf4b12b4c9ca5.nq.gz
    ├── 22ef27a377e1f5e98bb04658535de6c8f5c30053.nq.gz
    ├── 233383194325ff31406f7d97f3a3c81ce18c85fa.nq.gz
    ├── 23576a9b38abd40d467d0838761d074823e4ee90.nq.gz
    ├── 24cd665654c884ebf17e37fa9f25d2d59d69d6f9.nq.gz
    ├── 25520a6fe58475cf3e16e254ef2ee0c4723b6644.nq.gz
    ├── 25cca5a1c39a7e5298c0234507dbb3b32f9dfdaf.nq.gz
    ├── 2618d9669ecc7f7bbdb1a4e2a9d8c88f8f8a838e.nq.gz
    ├── 2741f980f1a50f61ca87dfd4a85d90c97014c325.nq.gz
    ├── 2850dd217e33af7adb93b263dd8013a0e9cb758e.nq.gz
    ├── 2879109c4ca665361b1f10262a82dc98ac2120b5.nq.gz
    ├── 291e006797fc7f0e84d297e952630c719fe6eeab.nq.gz
    ├── 29fde117e44711ee59e88843147b24dd3bd65af3.nq.gz
    ├── 2b59bc78c00bbd52af6787f9f1ab866603e87037.nq.gz
    ├── 2bf85f485397619ae97c0e3038e8efca31ff747a.nq.gz
    ├── 2c8bf1b10698f2293688f31ecdb66d56dad94f90.nq.gz
    ├── 2caf4481c3a2479106baf8619739cfa1912335cc.nq.gz
    ├── 2d1cfd1b8be4540a87410b25964987f200da7ef6.nq.gz
    ├── 2f0956799b7689dc07d74d3fc7487f16b41ae25a.nq.gz
    ├── 30089305fc0f383d9946b589bd4827146598752e.nq.gz
    ├── 31d3bdb14f1d67953d18dc04e73db834aaa200f2.nq.gz
    ├── 31d9945c8e919418774f39473c0e6fdb956917bb.nq.gz
    ├── 32e5033d7db1b74644f29815fd96b7153d422e1e.nq.gz
    ├── 336e8c30edddcf17d31ddaae6d6d1f0ef4dd4145.nq.gz
    ├── 33ae18bad99c080b3e8e40eaa1e1e7bc28adf554.nq.gz
    ├── 3410f70dfa653e77cd7e6b9e2c69cb2e2869c7ef.nq.gz
    ├── 3479633053860e44ac7b77b250ea0064efb47fbe.nq.gz
    ├── 35789ad7389baf8eb8b2ab850e0a67bad74975f7.nq.gz
    ├── 36abd90db1975fdec3041fe36c11f15ffb0df05b.nq.gz
    ├── 382e82658d0edc42e4d1389253fcce0543ba7e2a.nq.gz
    ├── 38d2497da9112076d3e88876d03aedbb1437a1a2.nq.gz
    ├── 3a081dc97d007e966208110f9faf8c72b282480a.nq.gz
    ├── 3ac21244dff26830f46ec462f2dab36e1a18938c.nq.gz
    ├── 3ad8af5173850f4b645f9c94f4efe3379564b128.nq.gz
    ├── 3b3b6103b356200d05caf7fa692cadf2c1e89043.nq.gz
    ├── 3b97b261e822b6752906b31265fe567a350162d5.nq.gz
    ├── 3bce38104defe7e2b289dc3f2a960fa5ab865fc5.nq.gz
    ├── 3d2594efbdd303a8acd7015e776d844609a3bb9d.nq.gz
    ├── 3d7a6dd57faf783db8b79fb3a5cf00df3992a9a6.nq.gz
    ├── 3ee926083ba336fada34476a67f239363b51471c.nq.gz
    ├── 3fa07e703eaa56fa201db3e4ed6cde8bf849d608.nq.gz
    ├── 3fbc9ad9229c651c36ca7f8d096ebcedc27ca0b5.nq.gz
    ├── 40925e25ace9954a0e3092c1cd19a02eca82fd07.nq.gz
    ├── 412aab99686995542fbf821553e16e9e37c80f81.nq.gz
    ├── 42251c8b2efea80ba8ff924e6d645c2c9e241be4.nq.gz
    ├── 4246141192214e00d2b789685bd28591e355a40d.nq.gz
    ├── 42667e4b3124ac66d43d2cd243108c7689369c99.nq.gz
    ├── 42e7aef3de9ecef63bb29975fbc0c2e8b762becf.nq.gz
    ├── 435d58c19ab66ac77f6ac87e72a8308bfff88f4c.nq.gz
    ├── 45478b851b071892674d3a4f5225bef321577dca.nq.gz
    ├── 456b133248fd5310857db3e2b174730f6488371b.nq.gz
    ├── 4594a394cb90b17cba41f084f552d8ac78ddf7f9.nq.gz
    ├── 46155ce0960d32501a8e016421d23dfaa815384b.nq.gz
    ├── 470f29ae7046fa7b6b61239d85fba4b8693e44f1.nq.gz
    ├── 47851341c29b496bbf85bc021f69cfda7dc615fe.nq.gz
    ├── 478f94416467480605dc846edec806b657f2ab88.nq.gz
    ├── 4915f2b1a865b568b5d9598d5fc5fcc6af841941.nq.gz
    ├── 492a89a4357ffc891447e7d0cc0a14961b588e88.nq.gz
    ├── 493322184e7212a17c95bfb80d4c9ffd53affcee.nq.gz
    ├── 4938d0a91264b20afa4578a1dfea3ca7950793e3.nq.gz
    ├── 496743d68ae04b2ee36a6253c8a788223b80775f.nq.gz
    ├── 49d977e1f6e97dc8aa6103ca8c429593f9344287.nq.gz
    ├── 49dd923a56b9501ccaf5614b3c74a4785be74957.nq.gz
    ├── 49f9fdc291f24bee6b0e8b06b340f7d6b97088ae.nq.gz
    ├── 4a23dfcc5450fd512da881655894ba60397f5a47.nq.gz
    ├── 4a5e2b8a3775facabbf7e93d8b9b1b30297632be.nq.gz
    ├── 4b40f22bed2e4801c91c33f99d24ede28934ce69.nq.gz
    ├── 4bff64b541f4870d1623bc4b4d404215ff953415.nq.gz
    ├── 4d1298a5ffbce39133fc491d76e5e7ea7c5e2613.nq.gz
    ├── 4e7103001aa583bdcfb88d71bf6f97d72e978259.nq.gz
    ├── 4efbaa6758dce6ea82f9e03e81c0196cd806b266.nq.gz
    ├── 4f1551771ca9b583d87ce5812c6f1a69b12e58a4.nq.gz
    ├── 4f48aec2acd7d41c7bfddfdcd9196d160de25216.nq.gz
    ├── 4fc2dd3758038ca3c6c9505cf95af5df748a4a56.nq.gz
    ├── 4fd01fc83a3910f91a3a837fb17975efd095e2b9.nq.gz
    ├── 4fe15ac67edd1e2693b6b959e65aa3d2ecbde5db.nq.gz
    ├── 50ca1be523bb0c08437c54cedb531aa0b89be787.nq.gz
    ├── 5126313a1dee1a2eb2ad0e46f52ad12915e86111.nq.gz
    ├── 51275e54bee695c76a455579262ad642efe7220c.nq.gz
    ├── 513d081bc2d2f3eb64801a5e8cde86ef4455829c.nq.gz
    ├── 517c9eb52c12436598d68ea658f3742704b12e5a.nq.gz
    ├── 519ef6826e56b178cbad9d91adf0b7a870696602.nq.gz
    ├── 524e7139bcfe3a5738e2736003acc6765bcb10ea.nq.gz
    ├── 526117aac0697e6997ee4f9bd6d2233bee98c109.nq.gz
    ├── 528625c9cd7a6dace2903189686dd26059e2d0bd.nq.gz
    ├── 529c6a331bdbd55d8e0155cd716a641f78e37973.nq.gz
    ├── 5378e8c9e4793a7e4bb40ddf96060db32c1b16c6.nq.gz
    ├── 53d18daf7825ae12d99406068073d16ab682737e.nq.gz
    ├── 53ebdd16cc5bcdc177caa128fe0a5feead4b8826.nq.gz
    ├── 53f3630000b722da5fb38ae9773d5cb0ce16913c.nq.gz
    ├── 5425994c0808680d14c5a214b450622ddc002e46.nq.gz
    ├── 551f5aaac457f6f8074b76bcf76f6f4d8a8e0a1b.nq.gz
    ├── 55be2d5626f99a380fc4a4ba758e2b91f3b017c3.nq.gz
    ├── 55e0bf2ac110d8ccc21f96229808824ce8f381f2.nq.gz
    ├── 572643fd21107dc590e8dc8fd3a938eeae5952ab.nq.gz
    ├── 57a86b35bb5c9ac5f183766fd6f1569c77e88d80.nq.gz
    ├── 584ba55881f9a192ddea645d6d8525bab205e289.nq.gz
    ├── 5996b74db1e0c7c4ebf2b2f8a09fb4499d3119e6.nq.gz
    ├── 5a548f809e4d8cb251ba73c96d84d40f8175d3e3.nq.gz
    ├── 5a909a251a63e85c20cb82beebfd5f5f69c833e5.nq.gz
    ├── 5aab8a51f128e2c500a5affb1919064cd5eff0fd.nq.gz
    ├── 5b0bfa239a246b9840d03a9ed9f587b698a0649f.nq.gz
    ├── 5c13f77ff003460753a39d9e406c0020231cabda.nq.gz
    ├── 5e85d2fc34f216e5ec0d3ac9f02c35dd81f24778.nq.gz
    ├── 5fd4c2ec58ab5b59d48eb37153fab5e5ac36fd45.nq.gz
    ├── 60f3429e824ebc9cf950d3bd690013015874a9c5.nq.gz
    ├── 6126d881d7d3528eb107ac1a6ca565d480ddb6f1.nq.gz
    ├── 614196d17bfc32ed0b027cbceaa54a33d32cb43e.nq.gz
    ├── 61694095a0d713871fb7b1d6d106f050e2712225.nq.gz
    ├── 61be2023004c7c950f9359e977bd188af1a2d796.nq.gz
    ├── 6341bec1bff78603431288c0ea833836bf8e6445.nq.gz
    ├── 63464ea0753d388803270b3d1aa01306567ed8da.nq.gz
    ├── 64c78b5a911e41a0b6aaf97638089be60e501deb.nq.gz
    ├── 664c038245138ad0cff989da1e510b681f595e46.nq.gz
    ├── 6671831a79a08218efc57a670a1dbfcb381e6230.nq.gz
    ├── 667c963bc9d6a795f4b0d4e681e6a7bf54af25cd.nq.gz
    ├── 669795545731e7d9ad3bb158a845cba469da63c9.nq.gz
    ├── 66ac68567d7970dae0fe78571075d1731dd2aa32.nq.gz
    ├── 66c1564ba86c70ed87b2f5f26ce99486d1012f56.nq.gz
    ├── 671886bcfe6669b88ca4f9f5a439fb141949f26a.nq.gz
    ├── 675d6da2c09cebd7e2375d94cbc43de49a28a6e8.nq.gz
    ├── 675dfbfbe216e37eb10986c0600ecc562e9c2c17.nq.gz
    ├── 691654fff718976bee0121be8ae6cc5b50cc9651.nq.gz
    ├── 69947c92fc5bdf31d6f8c81523bf0a769c914d3c.nq.gz
    ├── 69e12c16d9880e90e27d11aad508a3a00aa46b99.nq.gz
    ├── 69f83dcd66a5a1637475fd24dd5947052aec6d1c.nq.gz
    ├── 6a2544e2eececbc7aa284eb85311fe66fb198f1c.nq.gz
    ├── 6a50e2d7785fcce7bfa2fb86d489e17f969f6e27.nq.gz
    ├── 6a67826e0c99fa8e61bc5efad401aea042b29dab.nq.gz
    ├── 6ad9ebcdf5df5a2aa8d39e01371fc8a5e4663db4.nq.gz
    ├── 6ae5212b75d6855aa2cf7964de2b27650a6a2b80.nq.gz
    ├── 6e24269666c00b604f09bbfc266cae6d62d86fb3.nq.gz
    ├── 6eab013688b9771ee7558d8efa679fb9e88e53f9.nq.gz
    ├── 6f13a04c8bf3275d89ac480ac25f7d3fd88fb02b.nq.gz
    ├── 6f69991ecf1643e934c64ac21221c372a9d5efd7.nq.gz
    ├── 6f85ec061ea167b1718d2865cfc1e53370f11b7a.nq.gz
    ├── 6fe291459d8f0ecd434d02d1ec220e447b50f4fd.nq.gz
    ├── 70173651c7e2a3d53492f234e7444c9d775b3b2c.nq.gz
    ├── 71cd16df576f158da70e8007c946cf25ad25e397.nq.gz
    ├── 71df592fb0cb50da35d669010dff0900f3e55b9b.nq.gz
    ├── 72ab55ebf270e855928094dd99efa70e54006903.nq.gz
    ├── 72cf83427329d18925127b4a02f93fb592a593d6.nq.gz
    ├── 73142ea05ac6a4769141f9b5abdde4defe7950fc.nq.gz
    ├── 73ede3e97e6d1139b9da2991780624131fc3d2f5.nq.gz
    ├── 7529b24bd28e12b2f21f0d1bb709e9988d31e33c.nq.gz
    └── 7542bf43e379e7449b59f091a80bbc75eef26963.nq.gz

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

[allenai/scholarphi](https://github.com/allenai/scholarphi)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
