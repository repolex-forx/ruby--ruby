# Repolex Knowledge Graph of ruby/ruby

RDF knowledge graph data for [ruby/ruby](https://github.com/ruby/ruby), parsed by [repolex](https://repolex.ai).

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
lexq download ruby/ruby
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 995b59f66677d44767ce9faac6957e5543617ff9
│   │       ├── chunk-001.nq.gz
│   │       ├── chunk-002.nq.gz
│   │       ├── chunk-003.nq.gz
│   │       ├── chunk-004.nq.gz
│   │       ├── chunk-005.nq.gz
│   │       ├── chunk-006.nq.gz
│   │       ├── chunk-007.nq.gz
│   │       ├── chunk-008.nq.gz
│   │       └── chunk-009.nq.gz
│   ├── lsp
│   │   └── 995b59f66677d44767ce9faac6957e5543617ff9.nq.gz
│   └── repolex
│       └── 995b59f66677d44767ce9faac6957e5543617ff9
│           ├── chunk-001.nq.gz
│           └── chunk-002.nq.gz
└── blob
    ├── 0002886ca5b24f3f456231fd164d258266d114ed.nq.gz
    ├── 0014a876ed743ee594da156c2aeac6978ad3d57a.nq.gz
    ├── 00164ad90b2004f8d097f58e0872dcb91ffcb573.nq.gz
    ├── 001a73eb51380904162310d26109ab2c7ce9d15c.nq.gz
    ├── 001d9513b29fb22ae1fb63962709a9ea69af5747.nq.gz
    ├── 0020235fddb792c4534ed06d8ca19206c7eaa4a1.nq.gz
    ├── 002044cfa1a59071e536e6e15eb71579f3e26073.nq.gz
    ├── 0021136793b92828bd92b570bfae8ea6ee99abcf.nq.gz
    ├── 0024c780b909d309de9097f4ea569c28a487d928.nq.gz
    ├── 002dbaa3cc22d22323c2592c771caa5d403d0fba.nq.gz
    ├── 002f2a14ebed146994542c98d35137a7d64e11de.nq.gz
    ├── 0036137f020eb705caae7f173d5f4e2593b092fb.nq.gz
    ├── 003749bf3a9fc1325f6f05573ab12f7e9cd050e0.nq.gz
    ├── 003995945ba6b65dc1966f38ed713e555f066cdd.nq.gz
    ├── 0042b9ac4c5ab72a9867d13b5718f87cd01923ea.nq.gz
    ├── 004ac62737fc06ab20415e170d1192598c3cd6c5.nq.gz
    ├── 004eec310fcd5271767e2ea6fea0227c2d553c5e.nq.gz
    ├── 004fa4bf678bf8c4bc885b080e6c7339c142540e.nq.gz
    ├── 0056403e5800ff9d4fbd31ebd6b974d4370deb78.nq.gz
    ├── 005670becc23cd302fa4574a66a23c40b6eb135f.nq.gz
    ├── 00579238a6eede7870531ee6740677923c0c8270.nq.gz
    ├── 005927cd054cd960b85203fedeca6cfd0054d9e2.nq.gz
    ├── 005b1d0d9082defff80b0214b460e6a24eb99c98.nq.gz
    ├── 00634dc7f43f1005aac7a5582983ac512ea4d9a9.nq.gz
    ├── 0063d9a8fa6a8b3b8432203f9dd925cd2a03fa0b.nq.gz
    ├── 0069f3c703d47fc01d939de4360d6ff6659fa0ec.nq.gz
    ├── 006afeb2ccb1a25b0dbf9e6ea16b9ec55658e633.nq.gz
    ├── 00723a7517dc6c8e7858a7cc30d1769ad99e2b2a.nq.gz
    ├── 0072822c06d0e5f738e7dde92b0393a9e896c14a.nq.gz
    ├── 00765ac6dd6813ec752888d7b686615b9d2d696e.nq.gz
    ├── 00804d786adaa3889ee8111a79a01b108d498aaf.nq.gz
    ├── 0086708d23b0a62c016bb9d102f68f38792597a8.nq.gz
    ├── 0088bb39fa53990c305f74fe36425fb558a712bb.nq.gz
    ├── 00897669836c2a1df208c0fa251b990d8f7bbf66.nq.gz
    ├── 00905412758bcea6733b6c0c2e013e5bf33101e6.nq.gz
    ├── 0092e204683881a6728e99bb82ee022c79951d7f.nq.gz
    ├── 0092f5200337fa43f2aab2dc809df85f9574c276.nq.gz
    ├── 0095c1a1190c006fc9e286db15bbcbc8c52bb0b6.nq.gz
    ├── 00975aef4ecfaa06556b6fd5ee5679e6cd795106.nq.gz
    ├── 0097fd1808145ff442b591d5efd0503b5fadc94e.nq.gz
    ├── 009826c3d660c1a3c7455fce8041470b6f8a69ad.nq.gz
    ├── 009d55f72d7fec31a7c3e5619187b9b4a90e7233.nq.gz
    ├── 009f19429fffdcb864643322996d79b17c9f6b36.nq.gz
    ├── 00a454ba7265ea63ea4aeb4924c2dd95d81626b1.nq.gz
    ├── 00b1f02a8e01895b93de09ed4ee4f6e56d0cdd39.nq.gz
    ├── 00c33367dc695e7acc9ecbe99d35e1358db87bc7.nq.gz
    ├── 00c455a45c8f6f2a9caa937dc0c11ad9b4644605.nq.gz
    ├── 00c856e79bab7f6b17cc7f48e80e13e6b02fd99d.nq.gz
    ├── 00cc40ca56937fcb6493e5944da7287ddf8215ac.nq.gz
    ├── 00d19d588af508f9e026fd1a0080da632ac6d699.nq.gz
    ├── 00d7941a61eaa0b9c0d7416e3dc7c8194df90bc4.nq.gz
    ├── 00da4834bf0f057bf3ffd724c1fb494b6547ea11.nq.gz
    ├── 00eb9239940e816cc218cf035699ac64b9fe88dc.nq.gz
    ├── 00ef9fdba05bc011d74833f95d77f544ca34a4d4.nq.gz
    ├── 00f1fdff471e9e812dee4a5ca717662680ed01b2.nq.gz
    ├── 00f2c57205d04f5fc07598f3109c230bfc15c1f7.nq.gz
    ├── 0101eb6a643bce295d17d9b91ef6bcd16739a586.nq.gz
    ├── 01066d29300671cd9fb1fbd01f46968e15e18e82.nq.gz
    ├── 010ecefe353ee0e51c6a1ed6b08fba553d974aa0.nq.gz
    ├── 0113b9da2de19c724ed9e8f7363c80e8dd900660.nq.gz
    ├── 01156867b056094b57c6adb1d83a37f579834802.nq.gz
    ├── 011622988c4dac7e82e66aef6cdc03d39154fda3.nq.gz
    ├── 011a2135016e65dc396a62d2ebe9ca66c2a5f1a5.nq.gz
    ├── 0122b2726cc465ef13927b47a6216728e4258a14.nq.gz
    ├── 0127a66a2e2eda7752e9ee5bc5528a8c202b39a3.nq.gz
    ├── 01281063cdade08684d529fe75f884af08e58e8f.nq.gz
    ├── 0129e255da9dad59fe24931ff92a81f57d9de613.nq.gz
    ├── 014153e0b4afbec2f80e96eeb72d1669597feef8.nq.gz
    ├── 01497e9c425afde3bdb34af6bacda80e99d7ea30.nq.gz
    ├── 014ba83b16af6adb7da88d98bc264568b9212091.nq.gz
    ├── 015107413fcef00956706c5bd20838b736bf7439.nq.gz
    ├── 015386a9026cf3ce371585b1b33925fcc037c28b.nq.gz
    ├── 0156642ef258973aeae4086e0d7af22d9109322f.nq.gz
    ├── 015711bdabbcb491a10648c18d680073cc747d15.nq.gz
    ├── 015894b3a13e2ec8fe737ce3f045a987c2988400.nq.gz
    ├── 015caaf3bbff489c2ebcece015b01673de0a7fdf.nq.gz
    ├── 0163d24d46a2d3c6523509c62489f2283aa31eb4.nq.gz
    ├── 01654c509488628fcd0860c8eb0fc8ba41cd6fde.nq.gz
    ├── 01658e1b60594c4544284604c608f2af792c96df.nq.gz
    ├── 016bd94fe09337b0fe69b8e761842e6d1abb4e19.nq.gz
    ├── 0172c4ee897a40d5d2e65f66b3cf211b840d9993.nq.gz
    ├── 017873cc908873b14e4519e4094d6e516d52ca21.nq.gz
    ├── 017aa9bef72fbc0771cfe2f8f3b7193678d056f1.nq.gz
    ├── 017ba7eec9eb1b272369144ed19bcc59f7460d2a.nq.gz
    ├── 0181801c2d1a73c42f9ae8a999d7413a59f410e5.nq.gz
    ├── 018757db41fdf6cd8a2a5331dc7b17e6f27806c6.nq.gz
    ├── 018c49dbebbd8ac4fcfafad8e588ba2f7f22b151.nq.gz
    ├── 01a03d538f8216cc589c03158b0f90ab6790f27f.nq.gz
    ├── 01a29c6ab48a1812b0e076f0a3da9857b8bb1d41.nq.gz
    ├── 01ab06152d68a87db11947a5cd2a8bc253133cd4.nq.gz
    ├── 01ab4aab2fe46de93d1350b118d446ae66efe610.nq.gz
    ├── 01b42bcc52b4fa69aed396eb066aec575b144bc3.nq.gz
    ├── 01b57ce9e8e4364c38e04763bcaa8d181d8f2517.nq.gz
    ├── 01b8aa8f4d4ae46c4c2c4f877c6cf03e4b5e3a1e.nq.gz
    ├── 01bad64ce742861d536ac24a55961897770b8cf3.nq.gz
    ├── 01be61a9dcdb4a17ec272bab5ede333736649b03.nq.gz
    ├── 01c7505ef226bc087142a444326d2660ba832d31.nq.gz
    ├── 01cf923c71cfef9d8660e62e82017cad5be98c11.nq.gz
    ├── 01d72dbe859ec42c1aad43f17e8cdcf8a3e34bea.nq.gz
    ├── 01d7430df871bf1c596130f4a87f1603976e588e.nq.gz
    ├── 01df5f67192ec75c11ec5651061ef1d2633fadc2.nq.gz
    ├── 01e5cc68f6eadcd54a58992bba878bd273584846.nq.gz
    ├── 01e685134aef9dd132890a746cd282a0c5a95556.nq.gz
    ├── 01e7e0629a903f450383ad036d37eed8ae5160ca.nq.gz
    ├── 01fa0992ba8ce0c705b292b4700374ca38dc7203.nq.gz
    ├── 01fc8f8fb99f5eed95dd038ca9abd292147eae3d.nq.gz
    ├── 01fe23805624056c72a7fd693c8b485703073c85.nq.gz
    ├── 020212ebd8a378013154f52aebc522819759f9bc.nq.gz
    ├── 0207fa6a8649179fed71182a5cb3d9277ed2b58b.nq.gz
    ├── 0209b2d2fc097fe64910f124bc65add27dfe8f41.nq.gz
    ├── 020d3cce85d562b5bde42c2b60c535a6d97ae188.nq.gz
    ├── 020f5469973c06ac73be528b3ec9ade34b849844.nq.gz
    ├── 0214681604a42a598c89086268a0c995c4d51635.nq.gz
    ├── 02150f30ce012d3e4265d1a1f6a13f2c5b8e55ad.nq.gz
    ├── 02151eebbcc678bc178a98eb27b98fad95820b90.nq.gz
    ├── 021bb682c14dd7433747bab32c0976b127684273.nq.gz
    ├── 021fd435fe88e3df09d8833ff974457779bac365.nq.gz
    ├── 021fe7d90fdc13ff43f3a71e8911e724af419359.nq.gz
    ├── 022662a00b5f300d7779d423204dc6098d70f1e2.nq.gz
    ├── 0233118f4b42c8e218bd875e0bcab628ff3e1dea.nq.gz
    ├── 023361b90f230691d3880dd6a7bd89fd2fffc314.nq.gz
    ├── 02348084f84109f2f0abdefd8997b7613e9da83e.nq.gz
    ├── 02390e76e33b61e276fc1493fe8d062a558cb900.nq.gz
    ├── 0242653528b746e666067e3289753b5679ee19d4.nq.gz
    ├── 02435b419e026d1202be726d6837c6100ddfd2be.nq.gz
    ├── 024732fa7a59435dc34b519f2e2d36bbee0ac702.nq.gz
    ├── 0247f330d944039b5c1d3cd875b2f2bd5a44d4e8.nq.gz
    ├── 025386107f668ce8057045e06bfb65642c2ba0c8.nq.gz
    ├── 0259402b233b957d4967365239cddbbbee46e392.nq.gz
    ├── 0261f78a01e2c6b0883f56fe1a179a6d02b4acaa.nq.gz
    ├── 026252a13d16b18c4553665b874123a2ccd138cb.nq.gz
    ├── 02693c277bd262fe11f6c663333305292035929e.nq.gz
    ├── 02699e271e7c3d3e460fb7e8bcec39fc3084e7ee.nq.gz
    ├── 026e454b13cabfff93e1a388d79db04d9b34dd49.nq.gz
    ├── 026f753d411fd81da389e6fcc3d989754e43677e.nq.gz
    ├── 0270596a070b1b19fceb7d8f474b101b8cb1d746.nq.gz
    ├── 02726744d3b5b0b663f516119cf337a739e271a0.nq.gz
    ├── 0274a378f565c265fb16a70fa959b71ba54b8931.nq.gz
    ├── 0278bcede2172122a7d4cc98ecc5e46bee3c9538.nq.gz
    ├── 027c2395a718895e6a1535e04149fed4fa84df79.nq.gz
    ├── 027cf5a245a55037c68e5b734ff012b0f518e985.nq.gz
    ├── 027dc4e380a05ae8400136062617aff5625e4c04.nq.gz
    ├── 0281cd66683c67857e1b36bad0a1275ba2a9947c.nq.gz
    ├── 0283460e468bb4ee5b5473b98a965cf7f5922425.nq.gz
    ├── 02921ab8bf43a8c42de549b0a517e871be6e2db9.nq.gz
    ├── 029da08c46f622c5b9440be6a7ba446d58ceccad.nq.gz
    ├── 029f811637b534a6c44eee3422ea3f47aa91201c.nq.gz
    ├── 02a7103f89f89b304fd8e0309ef8a797c5f36751.nq.gz
    ├── 02a713474e6e051263ca4e23d23806347f4ba84a.nq.gz
    ├── 02ae07a3be5ffb47301f1d2e513216525ffdd0f8.nq.gz
    ├── 02af649d0909a4516c4af16d55210f9fe1042cec.nq.gz
    ├── 02af831855e8aedca9892862c33a1d0b0ac87967.nq.gz
    ├── 02bf47d5381efb0288f38c0b51488d38f00c1142.nq.gz
    ├── 02ca0422301d5a69b10910f1510c4f44b769361d.nq.gz
    ├── 02d28c91bab49115087f321d6483152c44f8934e.nq.gz
    ├── 02d5c9122133456c5b9c4423e9315830e511e80e.nq.gz
    ├── 02d88e960c112a49bbd57c84e0ffe6c9425b870e.nq.gz
    ├── 02df9f97da58ac4c623237cec9bbd298f32c2af2.nq.gz
    ├── 02e1c0bcb0f291201d09bdf02342ec1081ca7643.nq.gz
    ├── 02ea4d4e71998dbcebe30da6fb4975bbfcf22c1b.nq.gz
    ├── 02f2badc9e32e89e56e776acf2397335ec8134c8.nq.gz
    ├── 02f542efc0792047ef99317bdcab45613e1ce02f.nq.gz
    ├── 0301ce074c26bfb7c36448287f72a08a1bd9ab76.nq.gz
    ├── 03024a640eff0a041617aeb4eb6b8ac215930e95.nq.gz
    ├── 030302ced6cc37d8d69afaad098229d18df4e818.nq.gz
    ├── 03056669f63bd0a19074a60110db9c6f76ee76ff.nq.gz
    ├── 030c3cc3d18be982fae2acd0d8fe8c8a6f922141.nq.gz
    ├── 030eeeeb68464088d6bf48b2aabb1cca53672a84.nq.gz
    ├── 03166e10ee48668dd1137d9ab612efd4c3387469.nq.gz
    ├── 0318ac26ff0500528ad7a0292dae75c19d4b4610.nq.gz
    ├── 032124287cc3fcbdde85b3f8369f4f5644b4b7d3.nq.gz
    ├── 032258509759be02819d33963725de17c7a06883.nq.gz
    ├── 0322c136db4a647f5b1383fdd0d8282a7d82924b.nq.gz
    ├── 0324b3f1f4453f87e7414a4a80f51807a570be58.nq.gz
    ├── 0329c1eec321eb7bdebbb0c99703060967d212e2.nq.gz
    ├── 032bcfaebb7542b2d3bd4e47d6db60bfff535f81.nq.gz
    ├── 0332b44dde29e22b9b322d655662f0b96ecb0b50.nq.gz
    ├── 0334f953f6c20a1cc253470860884007fae30a08.nq.gz
    ├── 033e830fac31c3b906e397b8afb175b42ea70121.nq.gz
    ├── 034905f74e7d86c58e0cda62680e704c233719db.nq.gz
    ├── 034ce348cbf94405f2d8caafd01dca1d32fb03b2.nq.gz
    ├── 0350b62660519a8958af4ce70f15127497d14534.nq.gz
    ├── 035b45ec99a1468c563db4c4d4c64781da84c36d.nq.gz
    ├── 035d31bd9828e3d7f93ad6c0d6e51a991ec8f9c8.nq.gz
    ├── 035f02c70b6769a64dff287c617aec817d96b723.nq.gz
    ├── 03663dbb0b7ff13ff47f88b3aff8f3a6076c862f.nq.gz
    ├── 036c6b7f8c714fbf6c8830ddcfd2732e2133f9c8.nq.gz
    └── 036c855c4e3f229c6882be07c967aaf272932a36.nq.gz

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

## Source repository

[ruby/ruby](https://github.com/ruby/ruby)

---
*Parsed on 2026-09-09 by [repolex](https://repolex.ai)*
