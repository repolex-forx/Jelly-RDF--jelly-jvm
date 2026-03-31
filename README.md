# Repolex Knowledge Graph of Jelly-RDF/jelly-jvm

RDF knowledge graph data for [Jelly-RDF/jelly-jvm](https://github.com/Jelly-RDF/jelly-jvm), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download Jelly-RDF/jelly-jvm
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
└── blob
    ├── 002ee69fbe60226e3ebcb57946eb2878745f7cee.nq.gz
    ├── 0082815181ceb33617932e377eb33cc9de507d19.nq.gz
    ├── 00c25f526240e8f8a2d0a2661fd2113401deba1e.nq.gz
    ├── 00ea5914c2e11d5db1203e5477f6109f9b158334.nq.gz
    ├── 0109ba374287258e7bc45c4edb51e312287efcbf.nq.gz
    ├── 014ba6429f8d3b0a1945370cd5c0ec92d5018c61.nq.gz
    ├── 01c7bc1f6262d7c947d316d0faa721d23c7a6b63.nq.gz
    ├── 01e05563f268d4280ee3216f7a3e5503c362d17e.nq.gz
    ├── 0205e490a3f6a30a66f4593f93a8c6a32e731795.nq.gz
    ├── 024a5c18f7367dc7a19bfdd08acb9c1aecbf7c0f.nq.gz
    ├── 0265539d58746add1a0b7efca530000ad27f01ee.nq.gz
    ├── 027196336278feb5c79788623ff24f4fb66737de.nq.gz
    ├── 02804f885e93af65856dad0f297e8fc6b0422077.nq.gz
    ├── 03044f16511d0a10a47b6c617f1c79b7086c0d82.nq.gz
    ├── 0427eb8e5efd455a0c0893ebbca78564eb76e001.nq.gz
    ├── 042d18cd41bf879e9ab69bb13f73c7e75f89d6fc.nq.gz
    ├── 0472d79f772ec13d876c5a625a3532199dee3884.nq.gz
    ├── 049c47f0b1a289368f87f4495164c458164731c5.nq.gz
    ├── 04fd28affb9b03b00e8d01a5f6a699a04bb5d14d.nq.gz
    ├── 054efb62ca25249dff7226ba8754b1681aad638d.nq.gz
    ├── 057a8dfe25327a26c666b7aef343eebec18d6150.nq.gz
    ├── 059a94e2884e40e3a2d4dc3ce2a18a655e76746b.nq.gz
    ├── 05a8f1e1022b5dd5f5c2722884687acc3ef39a02.nq.gz
    ├── 05cb6c91b6c16eaa594ff5e12868f5be5ddf62dc.nq.gz
    ├── 05cce46872016e17e9e6613f85ddc2003ce940f5.nq.gz
    ├── 05d97ed08988356c36bc10518b23153b164243b2.nq.gz
    ├── 06152ab17803a04fa30ac5b15f037e5fd990aefb.nq.gz
    ├── 062aeee303b02be62f065de8889c55f1e8ca5e6b.nq.gz
    ├── 062dab398c623c8a794c2ce8085ded7965d78c94.nq.gz
    ├── 062f17ca01f12a06cb80a41ca103c9c199fda84e.nq.gz
    ├── 0630ea5084f78a3190f3247bbecefe81c905ad40.nq.gz
    ├── 0660a8858d97e47723070038eb562a6cae18a83a.nq.gz
    ├── 06c635ad70abbbdfc461347efb570289f54cbe45.nq.gz
    ├── 06d4c4164dc96a30f358d274e14a6126e23e66df.nq.gz
    ├── 06fc0003ef950df877b572d69427dd61b30ab771.nq.gz
    ├── 0710698b80458612dca59dfec97d500002b8567f.nq.gz
    ├── 074c633a8d71022a41bf5997c3e6434fa20eae5c.nq.gz
    ├── 075e984e0f193b980bb2d769d4490750d632284b.nq.gz
    ├── 07e23e7f05f77b365a947085a4c5049775ef9636.nq.gz
    ├── 081dc2d92b1fd9c231ec989d9745b4fc77ef462d.nq.gz
    ├── 08383c314e680daa081a7deca65cf261a8f3d08d.nq.gz
    ├── 0849b1e93f1075b23dc15f40d3e8c971087689c9.nq.gz
    ├── 08a599cb7c64c21b70b9cf7d34628e4a9a95eff5.nq.gz
    ├── 09118b3bafeee3c8ce404b1eb90486ecfab6bb08.nq.gz
    ├── 0934b20e289b26554fafa6fc47e6ab96607abc96.nq.gz
    ├── 099c0cb3dc7e38720f948253aee15fc8aaaabe28.nq.gz
    ├── 099e010f70810f78c486663706f59cb0b824bcaf.nq.gz
    ├── 0a4f0d924e7e192236b397c695fbdcb1b2625617.nq.gz
    ├── 0a746ed30169df30cb51c0078fd91821e6f6f692.nq.gz
    ├── 0ab80b948526ba41688580dd24b9d1973f6ae79e.nq.gz
    ├── 0ac00268fb24faf384a4153c7d28e6ce7034e756.nq.gz
    ├── 0afca815c5e3a03866f46632d60b913a7b2319ba.nq.gz
    ├── 0b5eb315cff2101724d6b2760d1f136a1706886d.nq.gz
    ├── 0b75bbe496a4e7d05c89ec50f7259d7063933be2.nq.gz
    ├── 0b91cef914514e598467ff16ff0d46138a347557.nq.gz
    ├── 0c332f1b94923a145445ec8cdbf9c384317329e0.nq.gz
    ├── 0c5be846d3800bd11c9939de20f1258bbac94854.nq.gz
    ├── 0c7c8c3cb47a45e10508901c5a5d1236249fa6c5.nq.gz
    ├── 0c7f6fd2898b8a5ad7ffc25823ef9a393a89e15a.nq.gz
    ├── 0d33f2e2c1b07f9b5bb4917b71df645f2e5f7579.nq.gz
    ├── 0de7bf5a150b250763f803c45ca8134df077315f.nq.gz
    ├── 0e652f84b87bd2048575a50d678a3a799a696622.nq.gz
    ├── 0e89115a5acdf3643045e8b1b391d5da0bc50642.nq.gz
    ├── 0ece1184cc40e9989ca8b541337d0a079b963f9d.nq.gz
    ├── 0f46d6d2dfe2b7115462b883e12f9e714358beb5.nq.gz
    ├── 0f60e4b51da6e0ba89491e5d993cff9df0027cf0.nq.gz
    ├── 0fa0da12c00559a0bc61cdc22c7fda8021fa4759.nq.gz
    ├── 0fc40ae38e7126e1692c5972b64b9d60d9086dd2.nq.gz
    ├── 100c307a47d6b598ccc37149e152f3a255fc31f8.nq.gz
    ├── 100e413c5ddbc2af9f72ce70ad867811487f6135.nq.gz
    ├── 101a09110fc9fc993a70d475b5f2a50cf6625c56.nq.gz
    ├── 102d0878700cf36ac61e2c826946b64310e179f8.nq.gz
    ├── 1077d05c513dcb5882a0bccf8a5c85d8a7bcc7d7.nq.gz
    ├── 11225fe3835586bd58714c5d36d06d02d3f3b22a.nq.gz
    ├── 114e30a93292e9819c19247762eadf799a80e2d1.nq.gz
    ├── 11a538782eb3c6a5f442344a3cc4ca4854e84afa.nq.gz
    ├── 11c9785f8b2dc7656b714843a81a7a0542cb30a1.nq.gz
    ├── 11d2fff1514f302e54d482c3643b4794010ae389.nq.gz
    ├── 123f7a4bf5ecaa49c804977d6115a6db6bf1279b.nq.gz
    ├── 1253b011e093aae899fb9562b531b609ffbdf4cd.nq.gz
    ├── 126d43fc9faf42b3491e78e1dd9420a0f09bc5cc.nq.gz
    ├── 12d3d2f7903a5e8faa70050722924ad52065d8bd.nq.gz
    ├── 12d9077558bb4a2592f01d54762bf7697b4cea8c.nq.gz
    ├── 13425a90a4837d94361d73a14b0a685da1ea0d93.nq.gz
    ├── 136f452e0d88d4ba3794b62bdd6e1bb4d3d5aa0f.nq.gz
    ├── 13ac4e30ebc57f36920fd333f17513cd9ddecea1.nq.gz
    ├── 13d21cc85e643e6657b67f405643387c65d92e11.nq.gz
    ├── 13f26942748e43b11a3fb4b700574f1fa1bf866d.nq.gz
    ├── 144da0ed6e1edad382b4376ca3471f5b13d546cc.nq.gz
    ├── 1463ec8623e71759c587982619d395c5c7ffa7b3.nq.gz
    ├── 148b47c130c4c5909363336de7c515f1bdbcf2a7.nq.gz
    ├── 14bbfb04526ab169f5af42dc6f1c19b94cb6fd3a.nq.gz
    ├── 14f81d4e36b9e3b346088bc409e56af8f5d987a0.nq.gz
    ├── 1517bcfbbf6955c3d7a85e04d7903cc2d6978ac3.nq.gz
    ├── 1525b2457d53b234226e2e1b6bcf481f7352ccab.nq.gz
    ├── 159a1408635dc7be1624a4b379e646ab0438b769.nq.gz
    ├── 15ba51fdfd748035e95add6f453d665a11efb8a9.nq.gz
    ├── 16150defe5949491a458243734151ebe5584be70.nq.gz
    ├── 164df4aae201fed847c36ce6cdc8b573b2afc41a.nq.gz
    ├── 16babf78c1bb84c493832aba4e318f5bab3a90a6.nq.gz
    ├── 16fb9047c5ab3c72e252fdeeda7d0ba282ecc668.nq.gz
    ├── 179eca2449a3cff67ee089d3940c3a85b44ad8d3.nq.gz
    ├── 17e4fa9a32107eaca5fe1873a7ff59c25215a7b8.nq.gz
    ├── 18139e07c60d0a66ad283a2bb5c90583f27d05d4.nq.gz
    ├── 1820ce75c0afcd60e2d15f644f59b9e0186d6daa.nq.gz
    ├── 1834da29b4aaf134dbd1709bd14d2c1676fd8d63.nq.gz
    ├── 1838da02fa5c4b0b086552a942dd4d65e5e48a06.nq.gz
    ├── 18755f284abeb43b4cf9419d6f2b3978cd7edcd8.nq.gz
    ├── 187ae1d8171547094e2c2f8c3bf3c0ab1758a42f.nq.gz
    ├── 1889dcd215234c863672d88b27a2f08c5c4c6601.nq.gz
    ├── 1889df63d941c250ee0d3084415f7c7d7fc41d13.nq.gz
    ├── 18989c870fcd77ef86380b3e72a169f5b42d2e04.nq.gz
    ├── 18b3ebb2e4d5fc73f211d9727bc631fb9797dcb5.nq.gz
    ├── 18d27db13c835edd32406612a459e15050cbd7b1.nq.gz
    ├── 19d5970d6886d77ea0cfada668f6c7fce729b731.nq.gz
    ├── 1a0ea57004da39f585e226653b61d919220b9a30.nq.gz
    ├── 1a2cf0d16a8ccaaf24939ccae2e3bfa882a25f51.nq.gz
    ├── 1a36ff9aa56422b59bc9e841c502d6aeef52d625.nq.gz
    ├── 1aee4090c0cb622d1a8b7a6f160b63378bef4bff.nq.gz
    ├── 1b8489d4737c6a8635cca9083ea4f241d06b91d8.nq.gz
    ├── 1b9e6a47dd34edd7c46b1b59d38e8d97b2cac038.nq.gz
    ├── 1b9f9e135ee45835645827bdc4534711d5b22fd0.nq.gz
    ├── 1bfbb98d6d2eb6caa0499cc954844c1ee031ea63.nq.gz
    ├── 1c327a169a64d773f3b5076ecef33c2a99f78db2.nq.gz
    ├── 1c7ce999ff834ee8d15b8c3ad37c1eca3e24edce.nq.gz
    ├── 1c9c797a2355aed4ef0846e3033b8ad7e09d8a32.nq.gz
    ├── 1cab81768ebf8b4751350d04b2f24c4c9979fad4.nq.gz
    ├── 1cb28ee1b54ee33e28cd74aed5df56b7aa993c0e.nq.gz
    ├── 1cba3641d3cb3e717991498d08cf439f748ada57.nq.gz
    ├── 1cc13a9ff997eeb3f07743e0ca1a18f69c654413.nq.gz
    ├── 1cc9bac07346aa84e40cd04366fbfbb5e6f13036.nq.gz
    ├── 1d10b3c79ac31918ae0fac0e714af6b274fc63a9.nq.gz
    ├── 1d87233c37a34274d10ba97c9816e0564e1a94e5.nq.gz
    ├── 1da4ea6172791d73d82bd697c9f4e0dbd193ec9b.nq.gz
    ├── 1db230a9fc284a295e51bd4efa19e4097c16a77b.nq.gz
    ├── 1ec84540af0edd38f3a6e8b95657b295349b7caf.nq.gz
    ├── 20258e53e0d849c62871c357dd41d34be54eedb9.nq.gz
    ├── 202b982c831c6268283a42292f395837f27deded.nq.gz
    ├── 20fe7afe41ea672672a057e421b5dc546df0d21b.nq.gz
    ├── 2103cf5c9f0489f7cfabf5621c1d0f2740360380.nq.gz
    ├── 21296306fff0c14ac4e7c1c2ba4ed31534b03ea8.nq.gz
    ├── 21483e5815a2f10e5c9018f8de7289eabf2c1d64.nq.gz
    ├── 216cc7274346d735a6d61d3a6ebd22686845dfd9.nq.gz
    ├── 2171d5ce17b799d314ab6af394d890df4d726f37.nq.gz
    ├── 21ed439405d222f7da9b2f4cd40d9d4a146f334a.nq.gz
    ├── 229b6b8868d54c2302888bd143865924d9661ad5.nq.gz
    ├── 22a5e259939224213527b002d4c8b3278d7f7eb4.nq.gz
    ├── 22b5c4857bcd43a8e649925e7f7835f0c158d59d.nq.gz
    ├── 230ca349149479065429a402a43d801cc0d042b8.nq.gz
    ├── 2313936cbe063645a8d85ff89c8194ef920622d1.nq.gz
    ├── 23978ee36efeb49e1bf8b102c293fbdb108be371.nq.gz
    ├── 23d95e638c7b4418801eabbce9ba3176a24f8575.nq.gz
    ├── 23f7d97938020e99efbdd357b9eaa35430295065.nq.gz
    ├── 24447235b9d6e00474edb3ddc4316434d31ed8b5.nq.gz
    ├── 245576c2a10b251373cd27e36049ac5fb9d21bcb.nq.gz
    ├── 245a3a51cf22e6ddacab658d4d2400dbbf53dc2f.nq.gz
    ├── 247c43c09a27806569e878f115dd0567b354fa9a.nq.gz
    ├── 24de66c70808974577016c45d89f9d741170ca51.nq.gz
    ├── 2504f6bd9f9adc43e31030f21fb3f49fab6de60c.nq.gz
    ├── 251d0fc8156626377b21c2a6e9020fdf57035745.nq.gz
    ├── 25203f9b417dca2f71b60dc09becdd82fcd35a03.nq.gz
    ├── 252042cabdbccc1ba4d9bfc3499dad99673a1c03.nq.gz
    ├── 252e0fc8413caa710be7f66c0dd0465e4a9a100b.nq.gz
    ├── 25b1de82df35c3d05da496701b23a18ee1d08e1b.nq.gz
    ├── 25bc01393d34a4f46af92bf689aead3fd9649c92.nq.gz
    ├── 25ce3a600a9753717b7d66c78e5f058793a1d2c6.nq.gz
    ├── 2610455117fb9b8f142d59c5ff7ede9f5ae132f5.nq.gz
    ├── 26137fde78c6f294dae6a7a348fd32072cb16a7a.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 26d95db93a1d2cb9c490b5cfdac84594e2e81a58.nq.gz
    ├── 26fa57936590a084a831d482f3e12002e8d529b4.nq.gz
    ├── 27868f7b19360eb831e73ef8166a7d2cfa9b926e.nq.gz
    ├── 27ae2be0ba9c6ecba4372fc3228995dc3e423de3.nq.gz
    ├── 27af13b0772e32b559597d3314107e354ce681e9.nq.gz
    ├── 280aefd356111d7da341abcadbd5feae85845a49.nq.gz
    ├── 2814cce53f21a45e02d8fda0316fb88496e4724a.nq.gz
    ├── 286b34de5f1d4288f31c7033a66d6658f65f94eb.nq.gz
    ├── 28902b9d968bc088680ca598c66b755b3ac8cfe2.nq.gz
    ├── 28a2aec23bbdad51afac17df0c0df86f02ec336e.nq.gz
    ├── 28b29b3a4a034a21bf85daefe89db6d449d8882b.nq.gz
    ├── 29abd396f6b2de5c79f6075aa52e4a7ed9865c1a.nq.gz
    ├── 29e00ec607b04038efcd095894392d6c2b39ca3f.nq.gz
    ├── 29ec5040cd9c9c53fe8428503546ad159140992e.nq.gz
    ├── 29ff7741204b888b4979be9c5ee5e62669c73ffc.nq.gz
    ├── 2a069a4ce9f7da43559d7546042ba8c813c573a8.nq.gz
    ├── 2a0a6a2a4236505e74f248cfd9deba4ca3a28558.nq.gz
    ├── 2a5f6512c689c07e3c87dd7eb8ffe15d3695781c.nq.gz
    ├── 2aa16fe66058cb79a314799d6fdc6192b6a7ebdf.nq.gz
    ├── 2b01245b6ce97eb53967d8866d5b616725cb8c68.nq.gz
    ├── 2b11c7970737cb92750277d447ae40d462feb776.nq.gz
    ├── 2b1d0cdda5d99879e89371eadb1b79ffc5331b1e.nq.gz
    ├── 2b2aedfecd1bec522a15995c40425a9792982029.nq.gz
    ├── 2b49b7b66fcf34053cc685eb57b4be3f4942c817.nq.gz
    ├── 2baa9e0463cdf9cac7b78621d7346487a4cc9567.nq.gz
    ├── 2bdcabee9e8571554d0473b46ddd91f99ec9e68d.nq.gz
    ├── 2bf041685f96d7dba95a9ba26b5d214d903d3ee6.nq.gz
    ├── 2bfccd089d6e5839e06a5b0192fc5c4980dde2e5.nq.gz
    ├── 2c02f4c323d5a52b69f8098e508aedd8d4b8bd1d.nq.gz
    ├── 2c0559c71191635bb6f09393febb35f1b19457f3.nq.gz
    └── 2c25aa58e7ffad3142dc4845816533069307f69d.nq.gz

2 directories, 200 files
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

## Source repository

[Jelly-RDF/jelly-jvm](https://github.com/Jelly-RDF/jelly-jvm)

---
*Parsed on 2026-03-31 by [repolex](https://repolex.ai)*
