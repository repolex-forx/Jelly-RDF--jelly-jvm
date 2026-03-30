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
    ├── 0082815181ceb33617932e377eb33cc9de507d19.nq.gz
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
    ├── 049c47f0b1a289368f87f4495164c458164731c5.nq.gz
    ├── 057a8dfe25327a26c666b7aef343eebec18d6150.nq.gz
    ├── 059a94e2884e40e3a2d4dc3ce2a18a655e76746b.nq.gz
    ├── 05cb6c91b6c16eaa594ff5e12868f5be5ddf62dc.nq.gz
    ├── 05cce46872016e17e9e6613f85ddc2003ce940f5.nq.gz
    ├── 06152ab17803a04fa30ac5b15f037e5fd990aefb.nq.gz
    ├── 062aeee303b02be62f065de8889c55f1e8ca5e6b.nq.gz
    ├── 062dab398c623c8a794c2ce8085ded7965d78c94.nq.gz
    ├── 0630ea5084f78a3190f3247bbecefe81c905ad40.nq.gz
    ├── 0660a8858d97e47723070038eb562a6cae18a83a.nq.gz
    ├── 06c635ad70abbbdfc461347efb570289f54cbe45.nq.gz
    ├── 06d4c4164dc96a30f358d274e14a6126e23e66df.nq.gz
    ├── 06fc0003ef950df877b572d69427dd61b30ab771.nq.gz
    ├── 074c633a8d71022a41bf5997c3e6434fa20eae5c.nq.gz
    ├── 075e984e0f193b980bb2d769d4490750d632284b.nq.gz
    ├── 081dc2d92b1fd9c231ec989d9745b4fc77ef462d.nq.gz
    ├── 0849b1e93f1075b23dc15f40d3e8c971087689c9.nq.gz
    ├── 08a599cb7c64c21b70b9cf7d34628e4a9a95eff5.nq.gz
    ├── 09118b3bafeee3c8ce404b1eb90486ecfab6bb08.nq.gz
    ├── 0934b20e289b26554fafa6fc47e6ab96607abc96.nq.gz
    ├── 099c0cb3dc7e38720f948253aee15fc8aaaabe28.nq.gz
    ├── 0a4f0d924e7e192236b397c695fbdcb1b2625617.nq.gz
    ├── 0ab80b948526ba41688580dd24b9d1973f6ae79e.nq.gz
    ├── 0ac00268fb24faf384a4153c7d28e6ce7034e756.nq.gz
    ├── 0b5eb315cff2101724d6b2760d1f136a1706886d.nq.gz
    ├── 0b91cef914514e598467ff16ff0d46138a347557.nq.gz
    ├── 0c332f1b94923a145445ec8cdbf9c384317329e0.nq.gz
    ├── 0c5be846d3800bd11c9939de20f1258bbac94854.nq.gz
    ├── 0c7f6fd2898b8a5ad7ffc25823ef9a393a89e15a.nq.gz
    ├── 0e89115a5acdf3643045e8b1b391d5da0bc50642.nq.gz
    ├── 0ece1184cc40e9989ca8b541337d0a079b963f9d.nq.gz
    ├── 0f46d6d2dfe2b7115462b883e12f9e714358beb5.nq.gz
    ├── 100c307a47d6b598ccc37149e152f3a255fc31f8.nq.gz
    ├── 100e413c5ddbc2af9f72ce70ad867811487f6135.nq.gz
    ├── 102d0878700cf36ac61e2c826946b64310e179f8.nq.gz
    ├── 1077d05c513dcb5882a0bccf8a5c85d8a7bcc7d7.nq.gz
    ├── 11225fe3835586bd58714c5d36d06d02d3f3b22a.nq.gz
    ├── 11c9785f8b2dc7656b714843a81a7a0542cb30a1.nq.gz
    ├── 123f7a4bf5ecaa49c804977d6115a6db6bf1279b.nq.gz
    ├── 1253b011e093aae899fb9562b531b609ffbdf4cd.nq.gz
    ├── 126d43fc9faf42b3491e78e1dd9420a0f09bc5cc.nq.gz
    ├── 12d3d2f7903a5e8faa70050722924ad52065d8bd.nq.gz
    ├── 12d9077558bb4a2592f01d54762bf7697b4cea8c.nq.gz
    ├── 13d21cc85e643e6657b67f405643387c65d92e11.nq.gz
    ├── 1463ec8623e71759c587982619d395c5c7ffa7b3.nq.gz
    ├── 14bbfb04526ab169f5af42dc6f1c19b94cb6fd3a.nq.gz
    ├── 14f81d4e36b9e3b346088bc409e56af8f5d987a0.nq.gz
    ├── 1517bcfbbf6955c3d7a85e04d7903cc2d6978ac3.nq.gz
    ├── 1525b2457d53b234226e2e1b6bcf481f7352ccab.nq.gz
    ├── 16150defe5949491a458243734151ebe5584be70.nq.gz
    ├── 164df4aae201fed847c36ce6cdc8b573b2afc41a.nq.gz
    ├── 179eca2449a3cff67ee089d3940c3a85b44ad8d3.nq.gz
    ├── 17e4fa9a32107eaca5fe1873a7ff59c25215a7b8.nq.gz
    ├── 1820ce75c0afcd60e2d15f644f59b9e0186d6daa.nq.gz
    ├── 1838da02fa5c4b0b086552a942dd4d65e5e48a06.nq.gz
    ├── 187ae1d8171547094e2c2f8c3bf3c0ab1758a42f.nq.gz
    ├── 1889dcd215234c863672d88b27a2f08c5c4c6601.nq.gz
    ├── 1889df63d941c250ee0d3084415f7c7d7fc41d13.nq.gz
    ├── 18b3ebb2e4d5fc73f211d9727bc631fb9797dcb5.nq.gz
    ├── 19d5970d6886d77ea0cfada668f6c7fce729b731.nq.gz
    ├── 1a0ea57004da39f585e226653b61d919220b9a30.nq.gz
    ├── 1a2cf0d16a8ccaaf24939ccae2e3bfa882a25f51.nq.gz
    ├── 1b9e6a47dd34edd7c46b1b59d38e8d97b2cac038.nq.gz
    ├── 1bfbb98d6d2eb6caa0499cc954844c1ee031ea63.nq.gz
    ├── 1c327a169a64d773f3b5076ecef33c2a99f78db2.nq.gz
    ├── 1c7ce999ff834ee8d15b8c3ad37c1eca3e24edce.nq.gz
    ├── 1cab81768ebf8b4751350d04b2f24c4c9979fad4.nq.gz
    ├── 1cba3641d3cb3e717991498d08cf439f748ada57.nq.gz
    ├── 1cc9bac07346aa84e40cd04366fbfbb5e6f13036.nq.gz
    ├── 1d10b3c79ac31918ae0fac0e714af6b274fc63a9.nq.gz
    ├── 1db230a9fc284a295e51bd4efa19e4097c16a77b.nq.gz
    ├── 1ec84540af0edd38f3a6e8b95657b295349b7caf.nq.gz
    ├── 20258e53e0d849c62871c357dd41d34be54eedb9.nq.gz
    ├── 202b982c831c6268283a42292f395837f27deded.nq.gz
    ├── 20fe7afe41ea672672a057e421b5dc546df0d21b.nq.gz
    ├── 2103cf5c9f0489f7cfabf5621c1d0f2740360380.nq.gz
    ├── 21483e5815a2f10e5c9018f8de7289eabf2c1d64.nq.gz
    ├── 21ed439405d222f7da9b2f4cd40d9d4a146f334a.nq.gz
    ├── 229b6b8868d54c2302888bd143865924d9661ad5.nq.gz
    ├── 22a5e259939224213527b002d4c8b3278d7f7eb4.nq.gz
    ├── 2313936cbe063645a8d85ff89c8194ef920622d1.nq.gz
    ├── 23978ee36efeb49e1bf8b102c293fbdb108be371.nq.gz
    ├── 23d95e638c7b4418801eabbce9ba3176a24f8575.nq.gz
    ├── 24447235b9d6e00474edb3ddc4316434d31ed8b5.nq.gz
    ├── 245a3a51cf22e6ddacab658d4d2400dbbf53dc2f.nq.gz
    ├── 247c43c09a27806569e878f115dd0567b354fa9a.nq.gz
    ├── 24de66c70808974577016c45d89f9d741170ca51.nq.gz
    ├── 2504f6bd9f9adc43e31030f21fb3f49fab6de60c.nq.gz
    ├── 25203f9b417dca2f71b60dc09becdd82fcd35a03.nq.gz
    ├── 252e0fc8413caa710be7f66c0dd0465e4a9a100b.nq.gz
    ├── 25ce3a600a9753717b7d66c78e5f058793a1d2c6.nq.gz
    ├── 2610455117fb9b8f142d59c5ff7ede9f5ae132f5.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 26d95db93a1d2cb9c490b5cfdac84594e2e81a58.nq.gz
    ├── 26fa57936590a084a831d482f3e12002e8d529b4.nq.gz
    ├── 27868f7b19360eb831e73ef8166a7d2cfa9b926e.nq.gz
    ├── 280aefd356111d7da341abcadbd5feae85845a49.nq.gz
    ├── 286b34de5f1d4288f31c7033a66d6658f65f94eb.nq.gz
    ├── 28a2aec23bbdad51afac17df0c0df86f02ec336e.nq.gz
    ├── 29abd396f6b2de5c79f6075aa52e4a7ed9865c1a.nq.gz
    ├── 29e00ec607b04038efcd095894392d6c2b39ca3f.nq.gz
    ├── 29ec5040cd9c9c53fe8428503546ad159140992e.nq.gz
    ├── 2a0a6a2a4236505e74f248cfd9deba4ca3a28558.nq.gz
    ├── 2aa16fe66058cb79a314799d6fdc6192b6a7ebdf.nq.gz
    ├── 2b01245b6ce97eb53967d8866d5b616725cb8c68.nq.gz
    ├── 2b2aedfecd1bec522a15995c40425a9792982029.nq.gz
    ├── 2b49b7b66fcf34053cc685eb57b4be3f4942c817.nq.gz
    ├── 2baa9e0463cdf9cac7b78621d7346487a4cc9567.nq.gz
    ├── 2bdcabee9e8571554d0473b46ddd91f99ec9e68d.nq.gz
    ├── 2bf041685f96d7dba95a9ba26b5d214d903d3ee6.nq.gz
    ├── 2bfccd089d6e5839e06a5b0192fc5c4980dde2e5.nq.gz
    ├── 2c02f4c323d5a52b69f8098e508aedd8d4b8bd1d.nq.gz
    ├── 2c25aa58e7ffad3142dc4845816533069307f69d.nq.gz
    ├── 2cb3feb14bea5da673453045147871c001325394.nq.gz
    ├── 2cb5b979a5b411fbf43400b4d55af0e45c825252.nq.gz
    ├── 2dab9d81fac958f0ad02a6611e1b59225938af2b.nq.gz
    ├── 2e1bc6bc65743e6f22486c7d48f72d2a81ae6075.nq.gz
    ├── 2ee196849df6bc0796371cccfabe38b327635ae3.nq.gz
    ├── 2f36220fc675dcfee2d234545c2efe1913a5166b.nq.gz
    ├── 2fe14266d13369102ea5a7526068acd5914051cd.nq.gz
    ├── 2fef99100d7534efcd8665146b0dabb2d8f8129a.nq.gz
    ├── 3028a98f9d1f0e30fb2b5957de45313c5abba3e9.nq.gz
    ├── 30903cfe4d31a6ee5a16ccb920c7a24640b6a70b.nq.gz
    ├── 30af9ace25b483a81ae7755fb879e7216f1172aa.nq.gz
    ├── 310ee4a73ee493b1a08bd63f4ad5bb61e0e48bc7.nq.gz
    ├── 313bd337d426a745e889a0f6308245c76d34624c.nq.gz
    ├── 31b4f18e7094039bc2bac6625737506ae133e5b2.nq.gz
    ├── 323bdddd5a564f992ea539c6918e003319c19441.nq.gz
    ├── 33555f4dcb4d7cc62923c9721e50f1eb4f101ef0.nq.gz
    ├── 339696921a4e7b6f15f2d92cc8a46002ddae5a29.nq.gz
    ├── 366c086d12b6b88a49924359114f7fce2de8d619.nq.gz
    ├── 3673e6c08cec571cef680ac2d791a26a1f38c61d.nq.gz
    ├── 3693081edbf80e0316fed2d7651d884d501b81c7.nq.gz
    ├── 3705c175fefda87f857f646445887f48160c934b.nq.gz
    ├── 375c70cfa3eaf840c016dc3156a0d5f8c122c23f.nq.gz
    ├── 376ccf5375535c11ef9b9fd178fe51aeb861fb7c.nq.gz
    ├── 376fb0167dbb655a01b18ec6fe414bbc3370a103.nq.gz
    ├── 37c371536f9ae709b71df2b5173cd4f4312329d1.nq.gz
    ├── 3864a065da5b0b12ae38be8894921c8a3815658f.nq.gz
    ├── 38a5a13f60c71dbf07645e1769d102acc324b554.nq.gz
    ├── 390f0494a3cab0dcb93533f72eb3d2b9a52d38ac.nq.gz
    ├── 3928f535642b48b8b54b3372e6144d6992752175.nq.gz
    ├── 395a082dbf3ad84b0ed5f226eeb260f2d91f3810.nq.gz
    ├── 39af4bd41fd6fa3c923b68ff91ba408e1e0427fb.nq.gz
    ├── 3abbd04a94ac47f5f005866ed92bdcb8cb5f49df.nq.gz
    ├── 3b118b4870f2ce4f4bd7632a91c32103ee846e27.nq.gz
    ├── 3b6410b74566c51e9e95f3d6e3017709825f6081.nq.gz
    ├── 3c19793e0af3c875f6341c71b1c14fbca339eb51.nq.gz
    ├── 3c295b1a63fa29cfbc1433945b8e5a13e00daeae.nq.gz
    ├── 3c99adca1c7a64dfdb68403f15ef604abe3e5d80.nq.gz
    ├── 3cfe17b975fd3da1eac90afc89079cff5774ab51.nq.gz
    ├── 3d0b9cee9d55411bacf5393ea891a470d0d7e5bb.nq.gz
    ├── 3d1585ce839bbec4aeef476faa747b626403631d.nq.gz
    ├── 3d3d3b5b6ab46cafc3ee0fa6a5930d311097f6c3.nq.gz
    ├── 3d4ff70412c0e367763c745825d6a1763878b7f1.nq.gz
    ├── 3d9904ab9719f7852d35af68e23c3591eb1e8518.nq.gz
    ├── 3e06ba82ce278adf24c17b76ef660eba0767adb3.nq.gz
    ├── 3f3b9322272a7dab015d25b64f888d2255c0b1d4.nq.gz
    ├── 3f663187869dd22f4b32b8e5deb91631742fcf87.nq.gz
    ├── 3f9149d28d3830a933413977eea50e04e3043ce8.nq.gz
    ├── 4019b0e42983a49d5380654d0204255da8d5de36.nq.gz
    ├── 404b4d336d1b48197c50a586cab61ee8b0b9302e.nq.gz
    ├── 4078ae17a008f48aafde4026a94151a1e9e46041.nq.gz
    ├── 407ce397c8ce658f49a4916cc930ec941c68e8bd.nq.gz
    ├── 408dfd3f4e80dcb75059fb4e881be99f17dcfadc.nq.gz
    ├── 40a32f51b65db48bd12b56e81c19a2f0a251da7b.nq.gz
    ├── 4133e0cab2161eaa40af8cc53aa3d297acf6979e.nq.gz
    ├── 414e5f7e6d8166cb7facbc3875ab9aebb24a685e.nq.gz
    ├── 41eed7fdfb2f07749ec181b3b28d4f11dd51478f.nq.gz
    ├── 4235cba3d25141e7930ad4292dfc338f5f8ef548.nq.gz
    ├── 42de9f82f348a2a49a2f83a5cfa27b4e63e6cd9d.nq.gz
    ├── 44e63a280c497f8b5b227f31a3b42d36af0c6ec3.nq.gz
    ├── 4528def6f57d2c2f593a0258ef99c6e02386e40e.nq.gz
    ├── 455feeb36f0b8de67e9d65a9510c6cc42debbde5.nq.gz
    ├── 458d02760e46b2094b4fb944b65e648e6b6da152.nq.gz
    ├── 4594b1e3fc9c85d26c8b8bd9294ee59ab04e5b1e.nq.gz
    ├── 459be3fa47566a3850b24d52a90185ca121ac4c7.nq.gz
    ├── 45e0ed31b5d6c616737057332b8ca78bd46dc1a2.nq.gz
    ├── 45f00b39c414bb79d43949054178e0da62a4baf5.nq.gz
    ├── 46231803efa8abfa4be0290d781f30a9b2833d49.nq.gz
    ├── 4676db57f99b6ca80a52feab1df783c4b8707f2b.nq.gz
    ├── 46b78bcf2e4a23378c252eda29489cbd902a6318.nq.gz
    ├── 4742413fec6860fde35ebfdcc1772fd21783c624.nq.gz
    ├── 48125889925da1fce22762cac19e73941c40d7f6.nq.gz
    ├── 48f4ac3ea5bac32dbe698e124e30d4e96c6bffa6.nq.gz
    ├── 49391df6d8d3a5cf6b069f20eecca47ed4b22222.nq.gz
    ├── 499d030cb999a7740a917d1cd19a91ca186bce47.nq.gz
    └── 49c3d14567811fc8667769b2978c95ce84d14f62.nq.gz

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
*Parsed on 2026-03-30 by [repolex](https://repolex.ai)*
