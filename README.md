# Repolex Knowledge Graph of databrickslabs/blueprint

RDF knowledge graph data for [databrickslabs/blueprint](https://github.com/databrickslabs/blueprint), parsed by [repolex](https://repolex.ai).

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
rlex download databrickslabs/blueprint
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── bb6f3c9f4c4f8bb6e17692ce541721fd8440cd0b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── bb6f3c9f4c4f8bb6e17692ce541721fd8440cd0b
│           └── chunk-001.nq.gz
├── blob
│   ├── 015569027e866ac89eb73703abc028b7a81b503a.nq.gz
│   ├── 0a5a8d3b74351444a2f275594ed186d42df96606.nq.gz
│   ├── 0c2b21664098f5ed3e60adf391fd085e968b4ea6.nq.gz
│   ├── 100bc636d48a055a74f2fad190bd3633dd090e1a.nq.gz
│   ├── 18bb596e152cdcc8e383a9962629ea68566489e1.nq.gz
│   ├── 1971eddeaa49174216bb8c805b0fdd71c9568a9f.nq.gz
│   ├── 1c4e8feb7a388072006266dc1df6ecd1e7deab71.nq.gz
│   ├── 1eb0b9c32aa74d4e6b8147d0a64457112e12352b.nq.gz
│   ├── 1ef9b75848826ed28aec8cde3ca8aab9ab6a7769.nq.gz
│   ├── 21f162ef3b9b19546b065ae6dda7db38573354f5.nq.gz
│   ├── 261edbcba63d8ab868799ff2bb802af12d0ad9b4.nq.gz
│   ├── 28c0ef3d823021c05da3773e74c7e4faa0da6b63.nq.gz
│   ├── 317775febdbacaaddde8dd42dc30dba04f5d370f.nq.gz
│   ├── 3385639e6ebcac66c75b38eea198c2eb264ec88a.nq.gz
│   ├── 344b8669895d927ae47dff1090879280a9117e21.nq.gz
│   ├── 3489332d9ace60b0b6b7961b5d1c4dcc65dee9a8.nq.gz
│   ├── 3ffb9c384dd3b407dcbadeb1e74fcda4a96fe6ab.nq.gz
│   ├── 4204b2abdf6bd10ee90a53d13c84e2715d910637.nq.gz
│   ├── 449a1bb960dd218faaebdcead4543843c123c0ac.nq.gz
│   ├── 481122edf8a81ad61ccb6ba3d03bcbc1518655b1.nq.gz
│   ├── 493f7415d73d5d2a0875222a1c7296000935cccc.nq.gz
│   ├── 4d7c8cba63e4efb6cd78820f2037c6079164e23e.nq.gz
│   ├── 4f37e6e5f4446890d0fa96180f47e32714b6a1a4.nq.gz
│   ├── 50bad49ddecf80a9a588cde1789ec68b490501fb.nq.gz
│   ├── 51dd0d638f49bd57db37285b004e4bc343c48e33.nq.gz
│   ├── 52b67a2926bac53aea7fe60a9a0846a5ace522c9.nq.gz
│   ├── 5609e81f13ede848bb0833c5d18d1def3d04b4d7.nq.gz
│   ├── 5d5a00081961126c0c6ecc58f5765f5d4a3e4f32.nq.gz
│   ├── 5d9bede37e82149bf29d912ebe7751bf252a6f42.nq.gz
│   ├── 607c882e50660e852999abcfb34284bb31b7e0ab.nq.gz
│   ├── 677759f1cd1bcbe3db6057b992a3d03dbbf09ae1.nq.gz
│   ├── 679ab0fca097839a81bdce9dad85aecd2c866f64.nq.gz
│   ├── 6834db1c885c46ea6dd6655453216ae296e925a8.nq.gz
│   ├── 6cd56f3809dce017f2a528cc6af317883f955de8.nq.gz
│   ├── 73d85d36981c19db467ef38ad04ad99446f253d3.nq.gz
│   ├── 75c211061e7bdba1f2c6790a356d642404ac4d92.nq.gz
│   ├── 7c064a8c288264d84079ef5a8f79387608c5ec46.nq.gz
│   ├── 7f8d102075bd9f2f101a1bbd8d2c3510c9ae60b8.nq.gz
│   ├── 80cd9e166c8135211d282707d3c6db4b6ba7969e.nq.gz
│   ├── 82c7b5144fa3094f4c8371830c46aa4c21134d9b.nq.gz
│   ├── 8357a235380680ec8a9b13c16623a752b883999f.nq.gz
│   ├── 8397d636c4352146f10f597d1ce8fa9f8ae57000.nq.gz
│   ├── 84eb1333369cb8a1da9897551798d4bff88d1fdc.nq.gz
│   ├── 8659416dacfd486244badd4636434b3f14b785f8.nq.gz
│   ├── 870b46560cf64148a53e1128adf126453348d4c5.nq.gz
│   ├── 8753536b1433b0125d829db1216f4e012942e9ba.nq.gz
│   ├── 8ac865eaac10296947675e599fc156130dc915f4.nq.gz
│   ├── 8c5533487d82c8fdc02d55c597a1035c7020d0d4.nq.gz
│   ├── 8e77d401d80ed146b7df36f054c136bc6bf6619f.nq.gz
│   ├── 8ee7a597f623bd5c543f575731bdea46f89ec45f.nq.gz
│   ├── 90c4472751df3a9f2d57fb9b215cbb8326a6db59.nq.gz
│   ├── 91289b4fb82cb264dfe84e840de64dc3b7ba7ffd.nq.gz
│   ├── 9191898a8f45f23f41cc270cd7d86f8ecc84cb8f.nq.gz
│   ├── 93f49f4ff8632743e3aeea540cbc446e96dd6f60.nq.gz
│   ├── 95769456334bbc013ba44ac77bcc95a13cba7c85.nq.gz
│   ├── 9e41c3c1e3e1712b530a46f726a96b45514229ca.nq.gz
│   ├── a3ee204e84f1011f07f1a4fd951ffe28843eab6f.nq.gz
│   ├── a643ecdecfd7a2397a9fee6753998c9ae3366b5a.nq.gz
│   ├── aa82a5874dad9ecddbfe3e6db305d49275720710.nq.gz
│   ├── adb2aa0fed0afd6d514bf0fb42c6078e14789933.nq.gz
│   ├── af1c74f2997f2030a330773a0da343a1020dca23.nq.gz
│   ├── af73d951b3490d468ded314263cbaa0b122b1fd2.nq.gz
│   ├── b207664ae34d8cb1688c515ce55ebbd73af33b7d.nq.gz
│   ├── b4f6bed8366a270e24cb4e0f6ca5d47a388cb0ec.nq.gz
│   ├── b779a2346a7d850c237ccf9f6310886d5e54dd74.nq.gz
│   ├── bbbfe4886fbd0691df6bee02141da419f0535adf.nq.gz
│   ├── c12300e257f7a8fe3bc0ce16989c5d83fcb2e052.nq.gz
│   ├── c24cd231aece15dc9ec3752a41eea03dc9dc5d79.nq.gz
│   ├── c4606214563d7977dc74d70abf4f39e2f4e5bffe.nq.gz
│   ├── c5ea0d0b091d060369795e72e9945fe3606c5f0c.nq.gz
│   ├── c6c07bb2eec91570670723861ebe8391f75cdb8d.nq.gz
│   ├── c8cfe3959183f8e9a50f83f54cd723f2dc9c252d.nq.gz
│   ├── cbf5aa818a517511e419876598ff09d94894cab3.nq.gz
│   ├── cca62bc1a777097c31baa85364cdf137de0d6a57.nq.gz
│   ├── d4979d227ba7ed2d2d600cdb13b2b6d2edc31b3e.nq.gz
│   ├── d59d68efdd7f20d125b9e665269997b0e13c7dad.nq.gz
│   ├── d9960d4a5e070b12ef94e7d357564a8ee015efd5.nq.gz
│   ├── d9b922aeddef20efff6980696baca802aba9410e.nq.gz
│   ├── de3ce1b793707a2ec79b0ead6a30f9f5c4d85b90.nq.gz
│   ├── e0c7311c24101f7a6a9d5b7f49f7b4ac1b9a79e8.nq.gz
│   ├── e4f247daaa2d3e3d4e4a46b34af01c4ad18996d6.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8b825c4ad8ccbda5c8c5cfa18b217385e11f6b9.nq.gz
│   ├── e9bde9750803b7020f00a87c27e41c63aea7eedd.nq.gz
│   ├── ea370a8e55e9af5fcda45d1f12372a47d86f1a69.nq.gz
│   ├── ec6bdc76a358260c8c7ed30572f42445e319700d.nq.gz
│   ├── f1293d156dfdaead72c483a808313a6e1cfb0543.nq.gz
│   ├── f2d2d091968634ca2af11472ec70e41caa95524b.nq.gz
│   ├── f3f1b99da35045906e70817f23408048b5dc7297.nq.gz
│   ├── f551d7accbf1b5a8fbc3d76a0312bc744da7fed9.nq.gz
│   ├── f65528449b5aa20a25e97d1d8b59fef3e1602deb.nq.gz
│   └── f82a5436b6df34e4bcfc3ef47b17cd06bebd65e1.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── bb6f3c9f4c4f8bb6e17692ce541721fd8440cd0b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 100 files
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

[databrickslabs/blueprint](https://github.com/databrickslabs/blueprint)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
