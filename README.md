# Repolex Knowledge Graph of spacetelescope/webbpsf

RDF knowledge graph data for [spacetelescope/webbpsf](https://github.com/spacetelescope/webbpsf), parsed by [repolex](https://repolex.ai).

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
rlex download spacetelescope/webbpsf
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 95b37d2263eb60e8d6967239e166f6932724d5fc
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 95b37d2263eb60e8d6967239e166f6932724d5fc
│           └── chunk-001.nq.gz
├── blob
│   ├── 0234de72c4439ca564f194972d06ff5f1bd6fb5c.nq.gz
│   ├── 023c473a2dc6568441c462cb21b63a2f519172c1.nq.gz
│   ├── 029addfc727896b301a215517a19ad081d100d3a.nq.gz
│   ├── 047dbb1232bdf4af1929af46a8b6b987c1364d97.nq.gz
│   ├── 05eedc6fe9403bf3051690d91b5c3f1dcf2d7a96.nq.gz
│   ├── 0d3ddface5eb4a7a5538b9df052090563c7786b7.nq.gz
│   ├── 0fb01cb2053a88318a18643df98181bb50f46a61.nq.gz
│   ├── 0fea5936be5494947f3d894bc0974eff2537394d.nq.gz
│   ├── 10554b877e080cf915fc834728e00521b9cbeb46.nq.gz
│   ├── 10f8d1e017b37e2fc22bafd8e178cc633364c2f7.nq.gz
│   ├── 12bb2c71b09a61c8c57935d92a65d0f96d48e9ba.nq.gz
│   ├── 149b7657bc9f5fc8b0f215acc155e620fb5fd350.nq.gz
│   ├── 164465a0157907d2c5ecfc0d27881975d1b86875.nq.gz
│   ├── 197c58c733aa7a1a54daeb9c892e78adf1e7ed42.nq.gz
│   ├── 19979683b056f72057274a78f1b0267d82085f7a.nq.gz
│   ├── 1d2c3d65bf5a95e46bca57ae42f735514ba9ef02.nq.gz
│   ├── 1d5bc692e6e97b5168591fa3c11d2a2204eede23.nq.gz
│   ├── 1dc0efee93ae4997ef9ad5ebf370b7256ee25664.nq.gz
│   ├── 1ef44ea45e7f795c9a0931a13cb0fa7e44138e1b.nq.gz
│   ├── 1fe59cfe366eda3952e6a0d75cac1982315b2d85.nq.gz
│   ├── 207e4367a7f8d811c3ce5beb51cd2cd1945d128e.nq.gz
│   ├── 219730ae33c8e73268ec6f01f0a3a9411f97f3f1.nq.gz
│   ├── 21d73b13401d7eb1434ff730e787e61df220b734.nq.gz
│   ├── 24e15073cd9039d1ea211a92422bb00a18fa8a6f.nq.gz
│   ├── 24e751f5902b4448109a20e9352dee3b9e0b7bcd.nq.gz
│   ├── 25f9ab995c1b18beb2bc925b82febc0e374a0e34.nq.gz
│   ├── 26bc64ffe6457a2de5f5a58dfb29db78ac16ee61.nq.gz
│   ├── 281fe8a71b55a90441d515026d20e9e0dc9a8910.nq.gz
│   ├── 286b2c898e60fe66cd010c4e0abdf9723fdd5a55.nq.gz
│   ├── 298a7d5393c87db8b6bc8a19dd26423d1da8b549.nq.gz
│   ├── 2c12c2f6d14b533cd9d7794a9346767028859eeb.nq.gz
│   ├── 2e088ac971610c079180dc9c2d088a753a579ce1.nq.gz
│   ├── 2e8d7bf10290f92d4f6beb09efa6f3743d19acc4.nq.gz
│   ├── 2fc878ea71e8c47936e3687ea3aaa200007392e1.nq.gz
│   ├── 301649dd3e0e72fe0d1348522460bcbbf5b1c1c9.nq.gz
│   ├── 30259d39ef02619fb25a57181b3983a86b1b6b64.nq.gz
│   ├── 32177ad03fed708da5c9f14aed67502ceff000ce.nq.gz
│   ├── 323e1a9bbf3bf87006e3963882079bddfab3954d.nq.gz
│   ├── 3598de732698a66e12d5beac6198a60a937916c9.nq.gz
│   ├── 368263cab48b3322f185a71a8fadb6d33ae1c85e.nq.gz
│   ├── 36eb6b28897b29afe7ad59b92ab08e335ed68910.nq.gz
│   ├── 3756296949d651c42230a0a122d3ee620a9ee522.nq.gz
│   ├── 3a3e8a7450d5d0405114665810d5344b0e7b2ceb.nq.gz
│   ├── 40efa4b57e5095e1d866ca343a1a80c1adf1cdb5.nq.gz
│   ├── 432267972c8fd559ad75cf869713e3dea797a684.nq.gz
│   ├── 4534aa0015cd823aaae4eb1101b117c0f7088490.nq.gz
│   ├── 45b05d1a9c8bb4b5e113b50802d134cc658bb277.nq.gz
│   ├── 45f1af2d3f604dc332b4fe374395675d0c9e5b7e.nq.gz
│   ├── 491f3e4f284c2b0c4beb772d895cdca1cc46d5c8.nq.gz
│   ├── 4930d62717c3c66a2a77992cbbd042343f843337.nq.gz
│   ├── 4b8cf8ed9072472be52c3ba5760c7c2f299aba6a.nq.gz
│   ├── 4c3c4a2cdca0e3500a183dbfe1ae0daf2f03b5d6.nq.gz
│   ├── 4c75b4f5c70226ef2eefd2e600bd1a1a29fd4af0.nq.gz
│   ├── 4cde0ec9eea46a9ecbeed684e1d29add7bb50516.nq.gz
│   ├── 4e476be2bb388a05ece6d275c015a31adec2c491.nq.gz
│   ├── 5147e70d6655a6cc3c275939fef83dfff4c644eb.nq.gz
│   ├── 538a2710044a504ca0d4d6618739288778659ab3.nq.gz
│   ├── 557e8e2794cf418fbabcf3bace63149cb7b46788.nq.gz
│   ├── 56c336367229e9116dcc8227d744654f978b75e0.nq.gz
│   ├── 57d01526e64a17de6525d734217a4edb416dbf24.nq.gz
│   ├── 5b11b4c2592e7311f2b3493867379b65d8e1e403.nq.gz
│   ├── 5c65df8d76055dd2ea5fe301079c3745a400d4f8.nq.gz
│   ├── 5ef5f9f36ce6ce182f9b7fb86bbab4b4a6a996b0.nq.gz
│   ├── 5fc12b1ea5e5b22578a70d66bc42c7eda3f962ed.nq.gz
│   ├── 60ca482dc6265c6baa61f1ec20469cf95e4ce721.nq.gz
│   ├── 63b86fb657b0797a718b549994589cf9bc3d9fa4.nq.gz
│   ├── 685e5fab07bdb5dd61439769b406b078e924bc56.nq.gz
│   ├── 688104b1d330da2f2f5d1aeab448713664b56278.nq.gz
│   ├── 69452535fe7f26e15515ba89e8b42b04d3919377.nq.gz
│   ├── 69e5f761b7c4979a89d479f4fa3d01e61b262555.nq.gz
│   ├── 6b214a5c09d3a2ed5399a65ba6100bdfd0b070ca.nq.gz
│   ├── 6bf5fc9efda96716c9387eb3a068932af4864877.nq.gz
│   ├── 6cfecd46ff344bd46549e8a0a4fc7a20f095e42e.nq.gz
│   ├── 6ebc99b06c5fec6e188fa560ce75e773dd56b94e.nq.gz
│   ├── 6ee08fb8078bf7c9e47eb3465adb453743c8679f.nq.gz
│   ├── 6f9e1546d49f36319fd2c059579b1fb429de1b85.nq.gz
│   ├── 70e959334e4ea3e3a94cdb82880b0db55422e16b.nq.gz
│   ├── 72c7315eda5eff517bc9b107b4ec921954b3e19d.nq.gz
│   ├── 731b1917299d4928350910af5ef5064441ec6544.nq.gz
│   ├── 737401e6f95a4e9d4abab4160425da95ef58c5ee.nq.gz
│   ├── 737797e58a4057679696f3d8afcf76bb4670dcd9.nq.gz
│   ├── 742b479cf9efb344ab05f5afaf610b8620759be8.nq.gz
│   ├── 751ead2086a1bf9ef275fff63151b02b961455fa.nq.gz
│   ├── 770fc3539bf8d2ab02e19b70ce787dc5840be967.nq.gz
│   ├── 77664d4c2d7a1d6d4682bbe23d90b1e6e3d4d11d.nq.gz
│   ├── 77ae65fe14e450ab6590fed994085eee9585c1d4.nq.gz
│   ├── 7f00272b8c872c073d8b2395adc5662af2b7a9af.nq.gz
│   ├── 7fb77bb34d650f53a76eb56296859b66cdcb5819.nq.gz
│   ├── 813ea9860f0149ede423f6d7c3f3ebd7f549e6b8.nq.gz
│   ├── 8255943cf38d65bb27478896c519d99141d46f07.nq.gz
│   ├── 8275f68d6ffbb25a5d48b5199033ef1c6db0e441.nq.gz
│   ├── 827d86b3ddf4e0033289fbd8889874044f006309.nq.gz
│   ├── 8369f84e8998536eb9abed112036e6a24e371d90.nq.gz
│   ├── 84428129941889285f11498e6834b7be5596f786.nq.gz
│   ├── 87d71fa05666be11ccb5102f27d979996725f680.nq.gz
│   ├── 87fdbdad7f99cb2bbf50eff135cd26536e056c81.nq.gz
│   ├── 8ba17f694512e7d92e9b93577dc2557d793c23d0.nq.gz
│   ├── 8dc9d9b69d098cbc173d85d95573990442ea6ce4.nq.gz
│   ├── 8e904cfadc609d394cbdaddc87d80fc6c00552e5.nq.gz
│   ├── 910d83e086242c40ed6ab0c62625fe5e18df356a.nq.gz
│   ├── 917d34a760939f3f73f310c8d2bc46740146ea04.nq.gz
│   ├── 92107e93e7cc0d799d59aad52109821a63523ee6.nq.gz
│   ├── 93872a4a4f0bad75dd25df23cd26f6cf3b0e00a9.nq.gz
│   ├── 93dfe92b9c98e009c2f75b6477817411d3a15585.nq.gz
│   ├── 947bfb8dbfb03ea56679b100a64c8a6f958dc794.nq.gz
│   ├── 956bd45567558ac99e7017bbcc484e72174bba46.nq.gz
│   ├── 956ec8484aefd0b28e194f026fe0a535395f7d07.nq.gz
│   ├── 960a110d79ee041a1b092c973aff0f0d12716f02.nq.gz
│   ├── 9628034aecaabd9251481d4710d8f3676d732929.nq.gz
│   ├── 96b8cda74d159d4f7969a2a7a26e6f307c2078cf.nq.gz
│   ├── 9896f70d85b015defbd8cdcb3f98c958df797f2d.nq.gz
│   ├── 98e048a37b670939b2b4cd651a1c320aa9ffb34e.nq.gz
│   ├── 9b4c43188a933a6d503555dc5db4d26b723341ab.nq.gz
│   ├── 9b6a3964da6ff6a39ec13dd48a44a5ee00e57201.nq.gz
│   ├── 9c5d9da0f2af6c2e4f5aac53ecf3246cc613efe4.nq.gz
│   ├── 9cabaf5238d62b16f3ff3c1fd828130815f33324.nq.gz
│   ├── 9f64eeaf3313abe56a75f83aef763dfd196edf78.nq.gz
│   ├── a2c6cebebad0e1be3d94484e5d855a0100fda0a9.nq.gz
│   ├── a3feff491e5b65704dad422b17e4f3593837338e.nq.gz
│   ├── a631c0cf7ce08ae2200c7553d4c839f37324b56a.nq.gz
│   ├── a71eacc881db778a436751babac1a738083ebafb.nq.gz
│   ├── a9b1d19c8d0c3ebc61cea873302125af388f8c43.nq.gz
│   ├── ab438c0a6b3276e67e96aac500dda4c99db59854.nq.gz
│   ├── adc3ac01d22bc6f10b9b73279281bcd87f5dd6fd.nq.gz
│   ├── ae36318c3417775c62aa00ef4bff8149a008348d.nq.gz
│   ├── ae43526f670e68c69d988161d6c65ff768bc4576.nq.gz
│   ├── b08c20e8c2d6581b3946799f676aa470aa9caf65.nq.gz
│   ├── b2633680c161e3a74f359a5ad25e8394e9c0b655.nq.gz
│   ├── b2afab52feb55861271e8eb56c1c24a5a578d06a.nq.gz
│   ├── b585fb19ea9f3c6eaa1475aca6da215bbfd6a09b.nq.gz
│   ├── b5b8fd958d76c127e34f3e61baff9ce49bd80ea6.nq.gz
│   ├── bad6db47f1f91348765cb98a9fe4fb3767ae44e0.nq.gz
│   ├── bc3e18f408ef0f01543300bc3ef7825c8d46afb5.nq.gz
│   ├── bc76093ad41ec8566561982d16ca854adf2da15e.nq.gz
│   ├── bc7d0bac8f2f5b2128a1359892fa53c2c8b113ac.nq.gz
│   ├── bcc5e452d8dd69715c7bbc6e145e779a876a54f5.nq.gz
│   ├── bcd68c6523a9792962430d01e4d54186867b11f0.nq.gz
│   ├── becbc3464918f10ae70c545136e0a976b72f83fd.nq.gz
│   ├── bf9da76d49191a8350801b7868516f329d548b49.nq.gz
│   ├── c05f748ab094137c40d24ea9e58dfcc38224c8c7.nq.gz
│   ├── c1eadf48b27088d95d353d688f02c8dc1885cbe3.nq.gz
│   ├── c1f45b9b34d355b08db2ab206d625b8b39ec3c30.nq.gz
│   ├── c2bca3af116dc3c3f50313c7f5620c74ff255837.nq.gz
│   ├── c46ef35016ac8936c2b4156e45d38efec8249ee8.nq.gz
│   ├── c5ba7943833ead74f7790b42bb3d85642258744e.nq.gz
│   ├── c85b423656cdff5fa797202a2d0b87f97e0b3480.nq.gz
│   ├── c9c63108b233ca8aece5eccbb042ea1f793abc73.nq.gz
│   ├── ca7b8a1be1ddc21ac767194422490f7a65e8978e.nq.gz
│   ├── cab1929fb045bf7e53ddb3fcb148103f9ee27797.nq.gz
│   ├── cab939503fa90e58d04ef04d0631dfe9ceeb0238.nq.gz
│   ├── cb3009c8523772a8d3855e535275c0fc6cd2ecc4.nq.gz
│   ├── cbb482da26533bd05e03bcf95117b697c88ead2a.nq.gz
│   ├── cc9c6e50ad0c534cf37224f7b48f4101aa6bb1b1.nq.gz
│   ├── cd3d83de58ec2cd66df63abff33036315afff011.nq.gz
│   ├── cf4253de25bf5fdaa67551fa928250cdf813d7e8.nq.gz
│   ├── cfb01d950c975219709f6ed4897f4bfe4ba602c0.nq.gz
│   ├── d0d1cfaea3d9de4295433c1d28c064cd822525dd.nq.gz
│   ├── d1d912d03943b1f657f3f92a1a60e441424e5807.nq.gz
│   ├── d323b134051e265a2da916bc098c95c1f8165d01.nq.gz
│   ├── d46efe4c2bcdb896d788bec7bc84512ac04a4118.nq.gz
│   ├── d680e8440fd535947daf7432838421aa9317bbd6.nq.gz
│   ├── d9f233f22a07e71f957e88f300c6ed5cc74e8d47.nq.gz
│   ├── da3e5b25fd4192b13bea486810a290f58a56a837.nq.gz
│   ├── da4eddcfe43a646692d6b9fbd59ff96ec79b2ac4.nq.gz
│   ├── da9dadcd56180c1212430d0f87ce1e95c74043a4.nq.gz
│   ├── dc4412abd969da1ea33de53193f6050f8bada472.nq.gz
│   ├── dc9fb3514282ebd581347751b117d242daf584ec.nq.gz
│   ├── def23240745d6b7a83c69f5e7f3dabf1b0d3a245.nq.gz
│   ├── e573cb856dee8069ab7380b023f33a24325ad30a.nq.gz
│   ├── e61be0fce5a19e67fc2a358e6011765c066afca7.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6a824e459e6d6c44ebf7a0067c7ef55a2203aee.nq.gz
│   ├── e7bb0369c74e4f089fa38f5733c30303949fdd32.nq.gz
│   ├── e951b63b57b071ce42e38a096593c98edc7ccc6b.nq.gz
│   ├── ea3075678b6a834892997bcfa4e327016b7a032f.nq.gz
│   ├── ea82dbe364955b0d38ecae12e42f1c58eb23147d.nq.gz
│   ├── eaf0acea14fc7cdfda2b6a56e3d33383a0af6559.nq.gz
│   ├── ebfc6acccab0d10ba8aed9bbd07cb38b0305c113.nq.gz
│   ├── ecf5d62fcef2b89e9e6a8e7b16021b1b774db90e.nq.gz
│   ├── edb4449f809d3c24b4e6ae44cdb5da73e370632c.nq.gz
│   ├── f062acd36bdc17a7f9d28be155ff49c77161a40e.nq.gz
│   ├── f0deff3a92f2646dd50fa3c6d38604b25ada5734.nq.gz
│   ├── f27d8a7a59ede0b4d67af67b03fc7535bdcc0ed2.nq.gz
│   ├── f31ccb545350cf391c38c9ac61644b8fa5c3ea6b.nq.gz
│   ├── f38315b22a4929c146aebfb5f2671bb16c003fd7.nq.gz
│   ├── f45115cb50758e87cd1c94d60503270add3c263f.nq.gz
│   ├── f4c0ea47f03d7a1172d2c4f2260d2e65e0b283dc.nq.gz
│   ├── f519d26ee6809a4c7237c6a0225d11d370d0ab50.nq.gz
│   ├── f76137342b2a41fea3a766427373b52d767723ff.nq.gz
│   ├── f804958546c0d973deb8482f5a2e22f34501e52c.nq.gz
│   ├── f875436acb267c630d0158e250384f8ad80aa038.nq.gz
│   ├── f90b58af9682caa19f921897db274277c8de681a.nq.gz
│   ├── fb0e56e8a3952ecb57d1cc3e48381de159e84c85.nq.gz
│   ├── fc3d93099fdfc3bfb09fb4cb9e26610a918fd874.nq.gz
│   └── fca8a8402def6f661b4d4953dd025f64d1a2f8e9.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
└── filetree
    └── 95b37d2263eb60e8d6967239e166f6932724d5fc.nq.gz

10 directories, 200 files
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

[spacetelescope/webbpsf](https://github.com/spacetelescope/webbpsf)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
