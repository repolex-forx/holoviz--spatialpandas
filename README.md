# Repolex Knowledge Graph of holoviz/spatialpandas

RDF knowledge graph data for [holoviz/spatialpandas](https://github.com/holoviz/spatialpandas), parsed by [repolex](https://repolex.ai).

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
rlex download holoviz/spatialpandas
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 36240a117d814363f5d581f675a28c639e0895bc
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 36240a117d814363f5d581f675a28c639e0895bc
│           └── chunk-001.nq.gz
├── blob
│   ├── 031f29950b8516f4d7d47148c96dc2ae5648ee23.nq.gz
│   ├── 058d99e138f92c00716022989051899efeb1cfe4.nq.gz
│   ├── 07b4649e1dc3c8cb49881790d292f011c6fc1211.nq.gz
│   ├── 07b6b4e5a5a671b92d8b63f321c247fde59d3d25.nq.gz
│   ├── 080c15d172132b3947f7ca66c8c03395cf19ae13.nq.gz
│   ├── 08adeec17012270fc99725e4ef24de69542ff824.nq.gz
│   ├── 0adde645d79eba7078e4466b8eb47ce818bfc3aa.nq.gz
│   ├── 0bea18048d7e24a873f808faaa7d8ad0b4dd741b.nq.gz
│   ├── 0c093ab736f971b064467e0517eabd9d07b5cf06.nq.gz
│   ├── 115c1b789ffb065ac1462b8454aba3128cb63a10.nq.gz
│   ├── 1257402d5f154e99fc722ff77703f65ae37337ea.nq.gz
│   ├── 1805e3465983c84b8ab8765c080df2e3a0d5fe0e.nq.gz
│   ├── 1dcb5138a5aaa6543639667de7da971d231c69a0.nq.gz
│   ├── 21639f95b6b2fe33e5e683c851f754223b1146f0.nq.gz
│   ├── 2599d6962850b447245ccbc1ddf0fb2767237d06.nq.gz
│   ├── 2659c40b73cf71a4474b2cdc7af698dbf913de08.nq.gz
│   ├── 2687c50ec40f257e03ab8c17f92d4df528eddb6c.nq.gz
│   ├── 28ffddbdd89e0ee42ee64f7abcc6b8079e1131bc.nq.gz
│   ├── 2987ce64ebbda368326781e0e1a1df50bd9b6a2c.nq.gz
│   ├── 29ce3705602b804b9edb43cf32d7c78edc07d695.nq.gz
│   ├── 2aac000161ce0c60c9fe9e9c21cafbbbae6cab1f.nq.gz
│   ├── 2b1e2ef6d7162be6b880a120314f17289f0330f9.nq.gz
│   ├── 2d39a451aaf87b89a66bd4b00564aeee09867f37.nq.gz
│   ├── 330973b0a168e256b485625e4ce10a7364f8ec36.nq.gz
│   ├── 36740aeaa9e8c6bbe9b1405cfa2de1e2c2c16e41.nq.gz
│   ├── 36f6f909a56861a4088595332edc56ecbcd32dc0.nq.gz
│   ├── 37831c2d061ddeb1e832d68f55b15ec677753a11.nq.gz
│   ├── 3ae3882158556a5d578f46f8a442e1b9dbf0101f.nq.gz
│   ├── 3b45640a23e9f081c0b7cf9234728099c055000f.nq.gz
│   ├── 3c93eeb48c8744dbd5adfe555138eae34a3b8092.nq.gz
│   ├── 437004fddb0c19a26b0081d5ed99b65c3ba72f23.nq.gz
│   ├── 484722981dc6ec71e1766fa1204931d334d98296.nq.gz
│   ├── 4c198bbcce38ab2e07799e08ec2d9b0bd6cd26f4.nq.gz
│   ├── 534bb2ae8b0b18cf23ec56268c66cf179499c7ba.nq.gz
│   ├── 54911e05e5efb41b93b471c147080a081b82c0aa.nq.gz
│   ├── 5560d11eea87f45d3743401b199b212783c17360.nq.gz
│   ├── 58e00b5bb5c44c43163c8bdbdf01b0c6041789b3.nq.gz
│   ├── 5abcec467f2c8955c044a91986bbedb08ed8b628.nq.gz
│   ├── 5f26616fc3d27d7f48881fac1b1176121b4a619b.nq.gz
│   ├── 64bbebb87236c88443d0704a895d21e4de94b280.nq.gz
│   ├── 65880b0781b8bff62c9b58c9ed1ecb3aecc63fee.nq.gz
│   ├── 6814421faccfc2441af1fe75069a30a5b436b151.nq.gz
│   ├── 69c01442abbfbcb0237b106f8a15559f0c4c7797.nq.gz
│   ├── 6dd2b12490a2e241ae4f18737cd0afb477d37e81.nq.gz
│   ├── 6de7aedcc6653deb7afbcd010431b19bda76ede0.nq.gz
│   ├── 72de94156d58ab472c177ccab5203a70efca1409.nq.gz
│   ├── 758cd6f083c368b1c0a3d3769ec0e27e41cdd78e.nq.gz
│   ├── 7744b84c6b71216ba7aa4361676b30336cab4db7.nq.gz
│   ├── 77e3c60f36dd94309fb6568ea885e9a1695c37a8.nq.gz
│   ├── 79a7eb11a4cc7fd23fdf660613c0d2f73cf995ca.nq.gz
│   ├── 7b418ce8bdbd1c4c4bdcb0c37efffc8a104778e2.nq.gz
│   ├── 7eac35bdc5eccf964ba0d49d4024783623b29845.nq.gz
│   ├── 8833f0297c26d1edafe263fb74b7b4934dbc57f8.nq.gz
│   ├── 8a5c011584cc9fb9663413ad0d76e6d9ee0139a5.nq.gz
│   ├── 8bfd2c52544c71275c40317818ad33e83833ae5f.nq.gz
│   ├── 8c1041ec56e389e98d68ec64fd5042a75eeb35c3.nq.gz
│   ├── 8c742aeb789c2c17de24140e0cc249f576570b88.nq.gz
│   ├── 8e09e1a7ab4a4d2fd64eec6cb06ca512d97bac54.nq.gz
│   ├── 8f3a048c575b6be5503f337ed0d0110eab9e1e28.nq.gz
│   ├── 8f587386213912db80bf867970b48f707cb1652e.nq.gz
│   ├── 90088231a079309fb287f2bab92a5e2c14e0b2b7.nq.gz
│   ├── 91397ca6ac8cf54767e5ab2c5f2efdcf76f9f859.nq.gz
│   ├── 916c7e0dddce119d2e472b326ae5f64c2a43e973.nq.gz
│   ├── 929540491aa1fc1d42d8ae0a827b34c35f31c4ac.nq.gz
│   ├── 98295b17682193d333a7c9bfd3b5e02712a494b8.nq.gz
│   ├── 9c0c4e462542f9fe6ba65736796074d41bf74a28.nq.gz
│   ├── 9e22d11951de250422846937f33d9f598d5bee03.nq.gz
│   ├── 9f9f67488462bf1c5ca935860d7ffd3dce5fab10.nq.gz
│   ├── a867e670de7033a4edf3221ab6b14f8926be9be8.nq.gz
│   ├── a86cce02856170ea01d764bfe0c696031baffed8.nq.gz
│   ├── a9cfc4cea0ef79db42142a2a93adc65e090cbe56.nq.gz
│   ├── b1c3b4fb8dcd83ea00f7a33d1184b4155b164855.nq.gz
│   ├── b230c79ef94ebef4832e3735ccc1e8d2a3ab7af5.nq.gz
│   ├── b553a4c13314ad63266e050cec9dc7da4df0ab86.nq.gz
│   ├── bb3338abbc0f774aa3db93aa0961c512882aa0e2.nq.gz
│   ├── be565e50bcf8666e9e30bb8fc6bb13fae6e34798.nq.gz
│   ├── be9bdf5efe41690876a7e7a0d12303e352a579a2.nq.gz
│   ├── bea59078b3a79f65b713270c0bb0133fae3bec9b.nq.gz
│   ├── c477a9cc82fbd7880cc7eada9506ad3b22ce1696.nq.gz
│   ├── cb5ee58303851dd5126b22484d74e9e3493e02a8.nq.gz
│   ├── d42820a8a1cba70e56e2117568ec22fb37446da8.nq.gz
│   ├── d62d9ec30128a8a1d9a1740e8b0c89ad6ae43f1b.nq.gz
│   ├── d85eedbe505e46da767f9027a606f9c3faec843d.nq.gz
│   ├── dc652360ecc6b2b01c1615966330faec2c492437.nq.gz
│   ├── ddf13445f34d583bb42bb3534b04bcea0825aa61.nq.gz
│   ├── dec2071a41147ec2a77b2af1e1b13b405f7d533d.nq.gz
│   ├── dfe9919f3f73c95f1db9ea04b16e2eef8c94ff7b.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e77062fbdd54b0162afaf21568e0efdcc43bc7ab.nq.gz
│   ├── e80003c415bce53bb7e0f4f48a813bca79ab04f1.nq.gz
│   ├── e96416fc997e4f3fbf96829564299509ddbb342d.nq.gz
│   ├── eb17fd35358afd41d58db6fc20aff8132404e3cd.nq.gz
│   ├── eb693221da2847ff439bc34741afa2866edb6f4e.nq.gz
│   ├── ef9c30d347e9ed11719022db3cf42d3a61be73a0.nq.gz
│   ├── f148f0bf07b98c5f54bbc20968c7016315c7e653.nq.gz
│   ├── f6e53be8d8835a797bb2940824b459a32461cd4b.nq.gz
│   └── fec81e77520a2b6bdd4ed4e3f679e25821efb5c1.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 36240a117d814363f5d581f675a28c639e0895bc.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 105 files
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

[holoviz/spatialpandas](https://github.com/holoviz/spatialpandas)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
