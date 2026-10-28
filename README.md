# Repolex Knowledge Graph of huggingface/upskill

RDF knowledge graph data for [huggingface/upskill](https://github.com/huggingface/upskill), parsed by [repolex](https://repolex.ai).

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
rlex download huggingface/upskill
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── eec8ab46f970a880e4d21cfd41dff50ac08c6847
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── eec8ab46f970a880e4d21cfd41dff50ac08c6847
│           └── chunk-001.nq.gz
├── blob
│   ├── 031a2ebdbce6af5fda700848d4c9565c0b922b81.nq.gz
│   ├── 088a9c61e6fb3e5f05f461c1a0020a6eaf7de105.nq.gz
│   ├── 0f5640867c3b7064f7c8f8711ddd3ec1c3bc0730.nq.gz
│   ├── 137c85f250556a369f746b4d1e2d779c4ec93462.nq.gz
│   ├── 13941eac85936f907f3e1adc06cbaa52ad921ab7.nq.gz
│   ├── 189d04441c5fa259d4c46018d260232e704b6fe1.nq.gz
│   ├── 190161aae14631c5d9438fe3c0085e56abb87298.nq.gz
│   ├── 1ba2ab0249329bedd3512d8b683ce74e94fa27e7.nq.gz
│   ├── 208ad3ed4a40e2434a537eb0ad26dbbe039765af.nq.gz
│   ├── 240d2e4357c5fdcb977713e81726c25327426b29.nq.gz
│   ├── 243079e5468a2f7ed11aa5b78cb80aef83068364.nq.gz
│   ├── 26e19808583632014096c929325b48315c778287.nq.gz
│   ├── 275096a969d5d23020d3c5ee1e15ec52c8e4fb68.nq.gz
│   ├── 286a8286abe2a0c3f982f5f4bf533f78661e81cc.nq.gz
│   ├── 29ec02d248505e85f916c89aeca6b40d814523d9.nq.gz
│   ├── 2ba01cb090427cd43f1667554438fec1c1c96816.nq.gz
│   ├── 2c7f6805a421c58382f46c017cf9b6736f2ef4b8.nq.gz
│   ├── 2ea9088e7cd7816c70d556dd99081062173ecbfa.nq.gz
│   ├── 2f34ed3f1e8a2c5f0e1a7023e09169be60a5f799.nq.gz
│   ├── 3704833c9fd1854457d1401b559c13918b169594.nq.gz
│   ├── 39fa78f72c86a04f07cb497f2d8c69e5aa2c2488.nq.gz
│   ├── 3e95b719050df0be96da5d3a8bc40c769328777b.nq.gz
│   ├── 468f1e46ce1bab49e3f28041c2bffbf7e3994900.nq.gz
│   ├── 48d8b6811dcc72e5e49b98bdf070d6085f24fc4b.nq.gz
│   ├── 4bbc146cd81770ab56b28a74011c83ece94486eb.nq.gz
│   ├── 52da53d598a0823769a17e07e28d095a0625ade6.nq.gz
│   ├── 56769f03b65e1f4f32327e42e313377881e53411.nq.gz
│   ├── 5a8cf4cd65e4194e09eb3435e6c02293e98bffbf.nq.gz
│   ├── 607a6a1f6205469ccace6c14cc983c5f515dc240.nq.gz
│   ├── 6501d03d8afbed9a9c6b503024929262316883d1.nq.gz
│   ├── 6aa6a90b47a3ed8477369f21e9e89101801a37d7.nq.gz
│   ├── 6ed73f94e630de2ffa03d75e7a641e120d70ac76.nq.gz
│   ├── 70b1902cb7720e477d36dd44fe075af3b2c09a05.nq.gz
│   ├── 75f563d179b5593327f9786716bf3b7e3667b232.nq.gz
│   ├── 76ce77278a4946f0818e3114a7b91d15e453d3eb.nq.gz
│   ├── 775e753f7b676333401cd98099a0589c55b7b8f9.nq.gz
│   ├── 79329594ffd56d3b3e0b80d4ddebac3a62b6b9f9.nq.gz
│   ├── 83b6dad337eef0479e6aad13b202fe6c8476ca69.nq.gz
│   ├── 83c43ede39bbaf5f7cdd2cf2fa328c7f641cfc26.nq.gz
│   ├── 8ff399949195474aeea09dfeb9a37e6aa676f897.nq.gz
│   ├── 902e2a60ec6cdcbd234db2ef17a8f6dfff52c790.nq.gz
│   ├── 908e3a00797a820b46c2054879862a933799d8d2.nq.gz
│   ├── 916d7ba50d45b751fea5e0e9380e7c8aea746adb.nq.gz
│   ├── 9554543799ad156da0e227d7a2032d3e19deac4c.nq.gz
│   ├── 9657040682b31627b978474fe5224b4eda2beba9.nq.gz
│   ├── 9788ee84a42102ecb0d9d27f2cdc9b2ddd983719.nq.gz
│   ├── 98cb0e793f60a1b4e05e22db1c828101b38b6a8b.nq.gz
│   ├── 98e757f17cd6f470b342b7399a8eb5c313e9ca25.nq.gz
│   ├── 99c63f64e976aeafb8707094de5c8f9f5ced252c.nq.gz
│   ├── 9d8aedea2e85e70e5c5c3160337796e649ccbecc.nq.gz
│   ├── a595a93d9ceebf4d5c6b779d008952d0331dfa10.nq.gz
│   ├── a59ba13f83a3d19533e36e20179af966450293f3.nq.gz
│   ├── a71322f5a7fdcd0e4b4fa058e4fbdb7418f58d43.nq.gz
│   ├── a7357aa195f3d35876fe9a7447fdfbc2f72e1599.nq.gz
│   ├── aba57666c2a527983920ebd12706619ba66aaf18.nq.gz
│   ├── b80da7fd4e6b1121af0e2b7f15327d52d1fde5fd.nq.gz
│   ├── bbf545ec69421a9ed70b96c1d0e8c50d6d5a227c.nq.gz
│   ├── d3bad5e9b29886cf5e9cc0b51e64ec772139b05c.nq.gz
│   ├── d4423e4fdf6affd20b55284ff1ac45aa8e2847f1.nq.gz
│   ├── d7b381d8240a3d78a006204ecd6c417e8354c147.nq.gz
│   ├── e321bcc64c98681baf08db75e4f3f913fbea53f4.nq.gz
│   ├── fb2f0c520c56a800e38c4ae735561d6fb0107532.nq.gz
│   ├── fed7d082f5582417a2df68ce1ccf664fe1c629b5.nq.gz
│   └── fef26bed04ae45696a931ff74de6aa42bef5455d.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── eec8ab46f970a880e4d21cfd41dff50ac08c6847.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 72 files
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

[huggingface/upskill](https://github.com/huggingface/upskill)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
