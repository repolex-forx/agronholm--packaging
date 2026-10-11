# Repolex Knowledge Graph of agronholm/packaging

RDF knowledge graph data for [agronholm/packaging](https://github.com/agronholm/packaging), parsed by [repolex](https://repolex.ai).

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
rlex download agronholm/packaging
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3e67fc775e93166600c84a5183ab6a86afff84b5
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3e67fc775e93166600c84a5183ab6a86afff84b5
│           └── chunk-001.nq.gz
├── blob
│   ├── 05e554a64c244d96c21dd2d8ce06f0060b65cac9.nq.gz
│   ├── 0888fb6967ef3c3055ccbc6d7f7609984d842cec.nq.gz
│   ├── 08f651fbd8dae57028d57721f7e9983053771a1e.nq.gz
│   ├── 0cad38ae541f129496681f96c88e02312eae98e6.nq.gz
│   ├── 1480b2aa767c4f80fbbcc76b39a661a9bf4b62fc.nq.gz
│   ├── 1a6a9a262085e722edc724028f024b7d5adf4248.nq.gz
│   ├── 1dfd23fa3c0eb944358b1eee0b7c241c79da3cd3.nq.gz
│   ├── 210ff0e486e3863421cead6dcd8713bbb247019a.nq.gz
│   ├── 2390d8c809eea1d6587357cdad25ed4af134db32.nq.gz
│   ├── 2659b8ee25768ba38932177ae91d4f44a482917a.nq.gz
│   ├── 299a951cf11fd09eede8df0e3e95a77dfeea4a64.nq.gz
│   ├── 2adf336e5a09e67d7146d3b0c48d88f63d1d8da8.nq.gz
│   ├── 2bbe495f4694e665ea39d9d14dfec048df1e0729.nq.gz
│   ├── 2fa75f7abb715eb7cfbd871919c56035b2bae35a.nq.gz
│   ├── 42ce7b75c92fb01a3f6ed17eea363f756b7da582.nq.gz
│   ├── 444eb7967a8c3e00e5fd3936b5758b4dedb1301b.nq.gz
│   ├── 454ba21c8f42038b78cd8518ac0e75237f0ab068.nq.gz
│   ├── 46066ad2ded1af7c68a4f5d4d3ccc66933b89f43.nq.gz
│   ├── 46bc2613086732e34b8863b7ea562ffb6918865b.nq.gz
│   ├── 4e01206a1446804e6722e74c163d63e6606c873d.nq.gz
│   ├── 4e068c9567def3564f238a76fe7ab46b569f33e5.nq.gz
│   ├── 4e5c0396b94d8f3c6b5ef6fcd1cc67317edd3e85.nq.gz
│   ├── 4f6aca04341fb524fafe006abddaa61d3c65d28c.nq.gz
│   ├── 5071561560ca52c6a1b000ca59a44558b2f2d907.nq.gz
│   ├── 5412a08349ed53c868988ba2139660f26d15adc5.nq.gz
│   ├── 554059fc8f6cf09b4593e3ec5bda2d77615cb5a3.nq.gz
│   ├── 565b0521d0c2cdbfe493d19765b04d5c119fa7eb.nq.gz
│   ├── 5677c0e89bd9c84b10b0239a0c26a799d3e646b8.nq.gz
│   ├── 59996e28c27516a7342a0f0b8052e0205455b65a.nq.gz
│   ├── 59db7412d509294f913ce0bd5886d14d853f0369.nq.gz
│   ├── 5e591c3ec5dde987c61ed21c0d7fa52582dc1b34.nq.gz
│   ├── 5e9899fc07609f37f5251f0da5a5af97d4d79234.nq.gz
│   ├── 60c4bec6ca251d481825ef1f99fbafdc8edac914.nq.gz
│   ├── 658836a96f9476916a29a61b916838e62b7010f6.nq.gz
│   ├── 6667d2990858447607f9fe21057a6e230a0caa8d.nq.gz
│   ├── 6b46ddc66d0f2d85e4f55a133a46505d04f56441.nq.gz
│   ├── 6cdbe1909b397b28f05a7e84ba8ea0f69ae5e77d.nq.gz
│   ├── 6dacfd1b16db596433ad2855751c950777187c4f.nq.gz
│   ├── 6f62d44e4ef733c0e713afcd2371fed7f2b3de67.nq.gz
│   ├── 7362d62fab7b4a88eeb7c5a793d9c90c2109d64b.nq.gz
│   ├── 767f0885fd2f4915bcbb9568f1060be401c59467.nq.gz
│   ├── 775b51fd7ea90df396a538ee491c693a8fb62da3.nq.gz
│   ├── 7ac7bb69a5325a6d9866885f2266539e8413a3c9.nq.gz
│   ├── 84e5bec868a123b2535e2a35ef16d2a0c5c26e35.nq.gz
│   ├── 87c86eefdadc9918168528ae023370e31171198c.nq.gz
│   ├── 883da23c96d1ef8cf28a0dc02a4e6c1c7d6d013a.nq.gz
│   ├── 89d041605c006e326a67f399a58a1fec8eb24acf.nq.gz
│   ├── 8dc94e9f0a32ad07aac91dc76f918d856fbea68b.nq.gz
│   ├── 90a6465f9682c886363eea5327dac64bf623a6ff.nq.gz
│   ├── 934d9f6f8496111775a490baf5c38d7965caf3fb.nq.gz
│   ├── 965ab3003af97dc37d31878feeff574b59dae17b.nq.gz
│   ├── 9821fc254bf5b47d3ba801294299706376ac1f43.nq.gz
│   ├── 9907b9c94ef7ea0eedbc4d11121887983449ad6f.nq.gz
│   ├── 9c94ae315dcb83c43219175d8519f68bedb79b2f.nq.gz
│   ├── 9d683b40247cd7bd8d91519ae41c1bacdea61a28.nq.gz
│   ├── a779538ebd712eaa23677f39b290634da979c53d.nq.gz
│   ├── a79b860e5e89008f67d80034ab2c459162d0656d.nq.gz
│   ├── acd2b94c7f46c2ba174c16865636d9433c4a70a0.nq.gz
│   ├── b0896e1f764bb6dd4bdaed053e9c60b4eebbb477.nq.gz
│   ├── b20b071ec7d995dd8e6d1a4fbe9fbf3624d22f51.nq.gz
│   ├── b4da79ee09a873846eb9278dc7affd1b319b8c72.nq.gz
│   ├── b509336233c2fafe4185a49da5909c8bbb38dfd7.nq.gz
│   ├── bf57ee1d9e1282ddd4ae914375d593eac402ff26.nq.gz
│   ├── c0d78f86eb739a5b5479dbfdaffe23dd12f14e1a.nq.gz
│   ├── c1238c06eab95f8c90c393383a703aa3b8c366a5.nq.gz
│   ├── c476c7512de7aa728304520265e4ce4120b75e7b.nq.gz
│   ├── c4e9578889efc3eee73f12a0d8df70fe89ddd67e.nq.gz
│   ├── c7f5b0b5e5bb69550d594b8d181f6f881356e404.nq.gz
│   ├── cc651cf60de5ee7ed9753982bdd271f53672f348.nq.gz
│   ├── d05637a6f53263ac1b0b006799382e87ddf92d7e.nq.gz
│   ├── d2bf30b56319ba862c5c9a1a39a87c6d1cb68718.nq.gz
│   ├── d33da5bb8bd7d2f86ae242a45918b180c82283f3.nq.gz
│   ├── d70261b717941b6388c6f75d0d64d7a54e24eae9.nq.gz
│   ├── daf85d34737e237b7d1473929363340fb7402e3c.nq.gz
│   ├── e658ec0861881cd21c92eaef73020d38763eb2fe.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e802dac033fbef16f1a4a99a1af4cc4a9c87d0c0.nq.gz
│   ├── eb8dc844d285dadecdce8be98cffd8bc39310595.nq.gz
│   ├── ef446bb0c2e9f20ab5e996f336c0ae7ccd1417ea.nq.gz
│   ├── f433b1a53f5b830a205fd2df78e2b34974656c7b.nq.gz
│   ├── f6bcd380bb18d6c8f25d52af97d79020eba4e569.nq.gz
│   ├── f7a02180bfec6bb27e895c735c92d9119c5823b9.nq.gz
│   ├── f7fdb00029ee217beac1f61d6ad36f2dd7f0ad36.nq.gz
│   ├── ff1d540a30c6df244d013bf411ad8ea63eb3f16f.nq.gz
│   └── ff2ca31a7beaf9c16f4f2df1fd81b6ac601d1b9c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 3e67fc775e93166600c84a5183ab6a86afff84b5.nq.gz
└── tag
    └── tag.nq.gz

11 directories, 91 files
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

[agronholm/packaging](https://github.com/agronholm/packaging)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
